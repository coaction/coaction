coaction - no code in here (yet)
========

Cooperative Action Framework

--
Bad quality, without sound and uncutted video http://www.youtube.com/watch?v=H1ZRCIV7cBk

Sorry for that, no time for more at this moment. In that demo, we can see that coaction is able to mimic sailsjs framework behaviour, reading it's config files, like routes and policies, using waterline type based models (but not waterline itself, it actually uses jugglingdb with redis adapter), server-client models sync + how to effortless levarage [Consolidator](https://github.com/consolidator) events mechanism to sync coaction events across multiple server instances using dnode protocol (one of few consolidator-pubsub bridges) - NOTE: web client in this demo is angularjs based app which uses 'shoe' (sockjs) and 'dnode' for client-server websockets communication which is provided by [Consolidator-Websocket](https://github.com/consolidator/consolidator-websocket) module.

As of 3 January 2014, video is outdated. [Consolidator-Model](https://github.com/consolidator/consolidator-model) has moved database adapter specific code into separate module, so models for ie. jugglingdb or node-orm2 can be defined using waterline model structure (bi-directional translation is just an idea for now, not that crucial atm, so it will be available only if someone will send a PR).
