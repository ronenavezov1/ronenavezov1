# Hi, I'm Roni

Software engineer. I build things that leave the screen: AI agents that talk to people, apps that ride on a motorcycle, and microcontrollers that react to the physical world.

### What I work on

At **TerraGenie** I work on **spatial perception**, which means turning physical space into accurate, usable data. We provide a **geographic database as a service**, and we let **people who aren't surveyors take real measurements** themselves. Most of what I build sits between measuring hardware and the database:

- **Field measurement apps:** Android controllers (Kotlin) that talk to GNSS receivers, laser distance meters and our own ESP32 hardware over Bluetooth, serial and TCP, so anyone can collect survey-grade points.
- **High-precision positioning:** RTK correction streaming (NMEA, ECEF ↔ geodetic), and the backend of a CORS reference-station network.
- **LiDAR and point clouds:** drivers and servers for Velodyne and Ouster scanners, plus point-cloud algorithms such as ICP registration and k-d tree search.
- **Laser measurement:** integrating the Leica 3D Disto into our own measuring software.
- **[web-map-service.com](https://web-map-service.com):** a product I developed that turns AutoCAD DWG drawings into a live Web Map Service, with an orthophoto uploader and AutoCAD plugins (C#) around it.

### Selected projects

| Project | What it is | Stack |
|---|---|---|
| [**date-with-roni**](https://github.com/ronenavezov1/date-with-roni) | My personal dating site, where a multi-agent LLM system talks to visitors on my behalf. Hard rules are enforced in code, token budgets are metered, and conversations live in RAM only. | Kotlin · Ktor · Claude · Postgres · Docker |
| [**SDR-Agent**](https://github.com/ronenavezov1/SDR-Agent) | An autonomous multi-agent sales development rep that qualifies inbound leads over email, with guardrails the LLM can't override. | Java · LLM agents |
| [**aiagent-lib**](https://github.com/ronenavezov1/aiagent-lib) | My own lightweight library for building LLM agents: a tool-calling loop, plus clients for Claude, Gemini and local models. | Kotlin |
| [**aigame**](https://github.com/ronenavezov1/aigame) | An AI party host with a living face. It listens by voice, recognizes who's speaking, and wakes up at random to hand out dares. | Kotlin · Compose Desktop · Claude |
| [**TractionControl**](https://github.com/ronenavezov1/TractionControl) | A real-time tire grip meter for motorcycles, with fighter-jet style audio cues through the helmet. | Android · Kotlin · Jetpack Compose |
| [**esp32_liser_system**](https://github.com/ronenavezov1/esp32_liser_system) | A battery PIR sensor that wakes from deep sleep and triggers a sweeping laser over encrypted ESP-NOW. | ESP32 · C++ |
| [**secure-file-transfer**](https://github.com/ronenavezov1/secure-file-transfer) | An encrypted client-server file transfer over a custom binary protocol, plus a DREAD-scored security review of my own implementation. | C++ · Python · RSA/AES |

### Tech

- **Languages:** Kotlin, Java, C++, C#, Python, JavaScript
- **AI:** LLM agents, multi-agent orchestration, tool calling, Claude and Gemini APIs
- **Backend:** Ktor, PostgreSQL, Docker, nginx
- **Mobile:** Android, Jetpack Compose
- **Embedded:** ESP32, ESP-NOW, Raspberry Pi
- **Spatial:** GNSS/RTK, LiDAR point clouds, laser distance measurement, CAD → GIS, geographic databases

### Outside the code

Motorcycles, which is where TractionControl came from.
