#WebRTC Signal Server

A simple signaling server for clients to connect and do signaling for WebRTC.

![Travis CI Status](https://travis-ci.org/dtsdwarak/webrtc-signal.svg?branch=master)

#URL
[http://webrtc-signal-server.herokuapp.com:80](http://webrtc-signal-server.herokuapp.com:80)

##Deploying
You can run it locally by using

```bash
$ npm start
```

You may also want to run this on Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/dtsdwarak/webrtc-signal/tree/master)

##Note
This has been configured to over HTTP. If you'd like to do the same over HTTPS, you may want to modify ```dev_config.json``` file

---
Forked from [andyet/signalmaster](https://github.com/andyet/signalmaster)
