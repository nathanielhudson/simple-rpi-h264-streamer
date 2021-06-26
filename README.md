
Effectively a fork of [AvcServer]() with all the legacy dependecies hauled out and everything streamlined a little bit.
Stream realtime low-latency h264 video directly to the browser from a Raspberry pi.
Comes with a browser player, and streaming server.
Uses [Broadway](https://github.com/mbebenita/Broadway) browser decoder and player.


# Running 
```bash
npm install
npm run app

# browse to http://127.0.0.1:8080/ for a demo player
```

On my server I use PM2 and Caddy. 
 
# Credits
* [matijagaspar](https://github.com/matijagaspar)
* [h264-live-player](https://github.com/131/h264-live-player)
* [Broadway](https://github.com/mbebenita/Broadway)
* [urbenlegend/WebStreamer](https://github.com/urbenlegend/WebStreamer)
