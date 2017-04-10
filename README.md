# node-red-contrib-fast-test [![Build Status](https://travis-ci.org/spookyd/node-red-contrib-speed-test.svg?branch=master)](https://travis-ci.org/spookyd/node-red-contrib-speed-test)

> Test your download speed using [speedtest.net](https://speedtest.net)

## Install

Ensure you have [Node.js](https://nodejs.org) version 4+ installed. Then run the following:
I had problems with the normal install mechanism. The follwoing worked for me:

* go to directory of .node-red
 -> pi@raspberrypi:~ $ cd .node-red/node_modules
* download source files directly from github
 -> pi@raspberrypi:~/.node-red/node_modules $ git clone https://github.com/herwig-/node-red-contrib-speed-test.git
* go to downoaded directory -> pi@raspberrypi:~/.node-red/node_modules $ cd node-red-contrib-speed-test
* install -> pi@raspberrypi:~/.node-red/node_mdues/node-red-contrib-speed-test $ npm install



## Usage

Currently, no configuration is needed to use this node.
An input is required to fire the speed test; any input will trigger a new test.
After the test is complete, the results can be found in the message, ``` msg.speedResults ```.


## Related

- [speedtest.net](https://github.com/ddsol/speedtest.net) - Test your internet connection speed and ping using speedtest.net


## License

MIT © [Luke Davis](https://lucky13.technologies)
