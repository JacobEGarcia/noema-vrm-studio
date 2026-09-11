# NOEMA
A browser-native living avatar studio inspired by Kiratchi's Blender-free VRM workflow. Describe a character, tune its visual language, preview a rigged procedural avatar with blink, gaze, idle motion and hair physics, and export a VRM-ready package manifest.

## Run
Serve this folder over HTTP (`python3 -m http.server`) and open it in a WebGL-capable browser.

## Production path
The UI and interactive avatar preview are complete. Real prompt-to-VRM geometry requires a server-side Tripo API connection. The client is deliberately key-free for safe public deployment.
