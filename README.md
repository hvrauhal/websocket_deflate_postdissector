websocket_deflate_postdissector
=============

Wireshark postdissector for examining WebSocket packets encoded with permessage-deflate

---

INSTALLING:

1. you need Wireshark 2.0+

2. install `lua-zlib` library 
    
   * Ubuntu: `sudo apt install lua-zlib`
   * MacOS:

          brew install lua
          sudo luarocks install lua-zlib

3. copy `websocket_deflate.lua` to `~/.wireshark/plugins/`

4. that's it
