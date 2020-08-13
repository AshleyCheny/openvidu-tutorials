[![License badge](https://img.shields.io/badge/license-Apache2-orange.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Documentation Status](https://readthedocs.org/projects/openviduio-docs/badge/?version=stable)](https://docs.openvidu.io/en/stable/?badge=stable)
[![Docker badge](https://img.shields.io/docker/pulls/openvidu/openvidu-server-kms.svg)](https://hub.docker.com/r/openvidu/openvidu-server-kms)
[![Support badge](https://img.shields.io/badge/support-sof-yellowgreen.svg)](https://groups.google.com/forum/#!forum/openvidu)

[![][OpenViduLogo]](http://openvidu.io)

openvidu-insecure-react
===

Visit [docs.openvidu.io/en/stable/tutorials/openvidu-insecure-react/](http://docs.openvidu.io/en/stable/tutorials/openvidu-insecure-react/)

[OpenViduLogo]: https://secure.gravatar.com/avatar/5daba1d43042f2e4e85849733c8e5702?s=120

Start web app locally
```
npm install && npm start

Start server locally
```
docker run -p 4443:4443 --rm \
    -e OPENVIDU_RECORDING=true \
    -e OPENVIDU_RECORDING_PATH=/Users/recordings \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v /Users/recordings:/Users/recordings \
openvidu/openvidu-server-kms:2.15.0
```