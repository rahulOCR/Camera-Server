# Video Server

WebRTC video Server for 4G/5G Video transmission. It is just a Mesh architecture (every participant sends and receives its media to all other participants).

## Getting Started

In Terminal type:

```bash
# Clone from Github
git clone https://github.com/rahulOCR/Camera-Server.git myproject

# Change directory
cd myproject

# Install NPM dependencies
npm install

# Start app
npm start

```

## Project Structure

| Name                    | Description                                                  |
| ----------------------- | ------------------------------------------------------------ |
| **public**/js/webrtc.js | Main webrtc logic.                                           |
| **public**/js/main.js   | Js for using webrtc.js.                                      |
| **public**/css/main.css | Style                                                        |
| **public**/index.html   | Landing page.                                                |
| server.js               | Sample server for webrtc signaling using socket.io.          |
| package.json            | NPM dependencies.                                            |
| package-lock.json       | Contains exact versions of NPM dependencies in package.json. |
