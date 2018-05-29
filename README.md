# WebRTC Recording

```
npm install -g serve
serve .
```

canvas2.html - Multi Video Stream Recording using Canvas ( Freezing on Mac Chrome )

canvas3.html - Recording MultipleVideo + Local Audio using RecordRTC

peermix2.html - Recording peer streaming (All Video + All Audio) using RecordRTC

## peermix2.html

It is using SimpleWebRTC demo for web conference and it's using RecordRTC (https://github.com/muaz-khan/RecordRTC) for multi-stream recording on each clients

For peermix2.html, it should work on https.

So you can use this command or use any other service (ngrok) for https

```
serve . -T
```
