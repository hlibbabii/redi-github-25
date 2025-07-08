# UCI Protocol Support

CheckMate++ fully supports the UCI (Universal Chess Interface) protocol, making it compatible with popular GUIs such as Arena and Fritz.

## Supported Commands

- `uci`
- `isready`
- `position`
- `go`  
- `stop`
- `quit`
- `delete`

## Limitations

Currently, the engine does not support:
- Pondering!
- Multi-PV (Multi principal variation)
- Engine options beyond basic hash size

These will be added in upcomming releases.

## Usage Tips

Make sure the GUI has permission to execute the engine binary. On Linux or macOS, you might need to run:
chmod +x checkmatepp
