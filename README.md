# Hi, I'm Roni

**Ronen (Roni) Avezov, software engineer.** About 4 years in the industry, a B.Sc. in Computer Science (Dean's List), and an M.Sc. in progress.

I like understanding systems from the ground up, and I build things that leave the screen: AI agents that talk to people, apps that ride on a motorcycle, and microcontrollers that react to the physical world.

### What I work on

**TerraGenie (Dimensional Perception Technology), 2022 to present.** I work on **spatial perception**, which means turning physical space into accurate, usable data. We provide a **geographic database as a service**, and we let **people who aren't surveyors take real measurements** themselves. Most of what I build sits between measuring hardware and the database:

- **Real-time GNSS middleware:** a low-latency pipeline between GNSS receivers and RTK servers that applies differential corrections and routes centimeter-accurate positions in real time. It covers NMEA, ECEF ↔ geodetic conversion, and the backend of a CORS reference-station network.
- **Total station integration:** software that drives optical measurement instruments, solves the instrument's position in the field in real time, and streams NMEA positions computed from live measurements.
- **Field measurement apps:** Android controllers (Kotlin) that talk to GNSS receivers, laser distance meters and our own ESP32 hardware over Bluetooth, serial and TCP, so anyone can collect survey-grade points.
- **LiDAR and point clouds:** drivers and servers for Velodyne and Ouster scanners, ICP registration, and a custom k-d tree for O(log n) nearest-point queries.
- **Laser measurement:** integrating the Leica 3D Disto into our own measuring software.
- **[web-map-service.com](https://web-map-service.com):** a Web Map Service I architected that turns DWG and DXF CAD files into live spatial data. It comes with a dedicated client, an orthophoto uploader and AutoCAD plugins (C#).
- **Backend:** highly available servers on Tomcat behind Nginx, built to keep response times low under heavy data loads.

### Selected projects

My work at TerraGenie is proprietary, so none of it is on this profile. What you see here is what I build at home, for fun, because I can't help it. These are the side projects I chose to share with the world:

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

- **Languages:** Kotlin, Java, C, C++, C#, Python, JavaScript, x86 and MIPS assembly
- **AI:** LLM agents, multi-agent orchestration, agentic workflows, tool calling, Claude and Gemini APIs
- **Backend:** Ktor, Tomcat, Node.js, Nginx, Docker, high-availability systems
- **Databases:** PostgreSQL, MySQL, SQLite (Room)
- **Mobile:** Android SDK, Jetpack Compose, Coroutines
- **Embedded and hardware:** ESP32, ESP-NOW, Raspberry Pi, Arduino, GNSS receivers, total stations, LiDAR
- **Spatial:** GNSS/RTK, point clouds, CAD → GIS, geographic databases
- **Architecture:** Clean Architecture, MVVM and MVI

### Education

- **M.Sc. in Computer Science**, The Open University of Israel (2026, in progress)
- **B.Sc. in Computer Science**, The Open University of Israel (2020–2023), Dean's List

### Service

Combat soldier, Golani Brigade (regular and active reserve duty).

### Outside the code

Motorcycles, which is where TractionControl came from.
