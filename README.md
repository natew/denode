DeNode
======

DeNode is short for Debug Node, it's a tiny wrapper around [Electron][1] that lets you debug your [Node][2] apps using Chrome Dev Tools :tada:

## Installation
```
npm install -g denode
```

## Usage

```
denode
denode ./index.js
denode `which browserify`
```

To reload the app, simply press CTRL + R on Linux/Windows and CMD + R on Mac OSX.

## Screenshot

<img alt="DeNode" src="https://cloud.githubusercontent.com/assets/4278113/14556652/03b0c480-02ae-11e6-949a-85334b9adbc0.png">

## License

DeNode is licensed under the terms of MIT License, see the LICENSE file for more info.

[1]:http://electron.atom.io/
[2]:http://nodejs.org/