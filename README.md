```mermaid
graph LR
    A[VLC Media Player] -->|HTTP API| B[VLC Discord RP]
    B -->|Rich Presence API| C[Discord]
    B -->|Metadata Analysis| D[Media Detection]
    D -->|TV Shows, Movies, Anime<br/>Music Videos, Audio| B
```
