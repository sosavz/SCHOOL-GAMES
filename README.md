# Playroom — private game updates

UNO and Mensch ärgere dich nicht for friends.

Get the initial Windows ZIP from the host. Accept your repository invitation, extract the complete game folder, and run **Set up private updates.cmd** once using your invited GitHub account. Then open **Start UNO Together.cmd** to check for updates and play.

Updates download from this private repository even while the host PC is offline. Multiplayer still needs a running host and a reachable network connection.

The launcher reads `latest.json` and verifies the versioned ZIP under `builds/` before installing. Local preferences, reconnect data and the runtime are preserved. No account credentials are distributed here.

Future versions must be published here before friends can receive them. The owner can ask the game-development chat to publish the next tested release.
