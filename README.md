# nodejs-cardgame
A real time multiplayer in browser card game

Another project to practice and learn! My focus this time will be on planning and design, rather than jumping in and writing code right off the bat.

### Fundamental guidelines

- Server retains control, clients have restricted power
    - Don't let the client tell the server, for example, what cards it has in its hand. The client may only pick from a set of legal options the server provides. The server will reject uncompliant client messages, eliminating the potential for hacked clients. 
- Maintain a clear game state and history
    - Keep clients in sync. Perhaps use a plaintext history for the game.
