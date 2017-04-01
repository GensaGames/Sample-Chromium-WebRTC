# Sample-Chromium-WebRTC

It's purely Chromium Android WebRTC sample, which located in WebRTC source. Project already contains one of the latest build (debug, based 27.03.2017), with all libraries. We used ABI build ARM-V7. But **Main Point** here, it's just updated WebSocket connection, with new changes of third-party library - autobahn. 

### Flow of building this Sample

- Sync latest WebRTC source
- Extract sample from "examples" folder
- Build WebRTC .so and jar. libraries
- Get together Sample source and Libs

### Note

Some devices (or network types) still receiving error with unsecure connection. It's known issue, which ignored for now. You can check other and working Android WebRTC Sample in my Repositories (will be updated soon).
