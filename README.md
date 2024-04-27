# JyotiYatra

Under construction! Not ready for use yet! Currently experimenting and planning!

Developed by Akshat Shukla

## Overview

JyotiYatra is a Python library for streaming video and audio data over networks. It is currently in the planning and experimental stage and not ready for production use. The library aims to provide an easy-to-use interface for setting up streaming servers and clients for various media sources.

## Installation

JyotiYatra is not yet available for installation. Stay tuned for updates on how to install it once development progresses.

## Usage

### Creating A Server

```python
from JyotiYatra.streaming import StreamingServer

server = StreamingServer('127.0.0.1', 9999)
server.start_server()

# Other Code

# When You Are Done
server.stop_server()
```

### Creating A Client

```python
from JyotiYatra.streaming import CameraClient, VideoClient, ScreenShareClient

# Choose One
client1 = CameraClient('127.0.0.1', 9999)
client2 = VideoClient('127.0.0.1', 9999, 'video.mp4')
client3 = ScreenShareClient('127.0.0.1', 9999)

client1.start_stream()
client2.start_stream()
client3.start_stream()
```

## Examples

You can find example code in the `examples` directory to help you get started with using JyotiYatra.

## Contributing

Contributions are welcome! Feel free to open an issue or pull request on the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

