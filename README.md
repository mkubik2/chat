# chat-example

This is the source code for a very simple chat example used for
the [Getting Started](http://socket.io/get-started/chat/) guide
of the Socket.IO website.

Please refer to it to learn how to run this application.

You can also spin up a free IBM CLoud Runtime to test it out:

[![Deploy to IBM Cloud](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/mkubik2/chat)

This sample was enriched by a manifest.yml:
```
---
applications:
- name: WhoChats
  memory: 128M
  host: whochats
```

Besides, the application is deployed on [Now](https://zeit.co/now): https://socketio-chat-example.now.sh/
