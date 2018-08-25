# Steps to install nn your own server

* ```npm install --production```
* ```node server.js```, should run on port localhost:9001 or process.env.port
* Heroku takes care of SSL, for self-deployed solutions make use of LetsEncrypt or similar SSL services & then update the cert locations in server.js file.


## License

[RTCMultiConnection](https://github.com/muaz-khan/RTCMultiConnection) is released under [MIT licence](https://github.com/muaz-khan/RTCMultiConnection/blob/master/LICENSE.md) . Copyright (c) [Muaz Khan](http://www.MuazKhan.com/).
