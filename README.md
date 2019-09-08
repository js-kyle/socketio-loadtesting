## socketio-loadtesting 🚀

This repository contains the tutorial files which companion my blog post on how to loadtest socket.io WebSocket applications. A live version of this application can be previewed at https://socketio-loadtest.herokuapp.com, and artillery.io loadtesting configuration files are found in the `load-test` directory. Usage instructions are in my blog post, [https://medium.com/@kyle_martin/load-testing-socket-io-web-applications-and-infrastructure-3e96011898e0](https://medium.com/@kyle_martin/load-testing-socket-io-web-applications-and-infrastructure-3e96011898e0)

To run the application:

```
$ npm install
$ npm start
```

The example socket.io application will be available on the configured `PORT`, otherwise it will default to port `8080`.

![loadtesting example](assets/example.gif "Loadtest example")

