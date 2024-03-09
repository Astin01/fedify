<!-- deno-fmt-ignore-file -->

Fedify changelog
================

Version 0.2.0
-------------

To be released.

 -  Implemented [NodeInfo] 2.1 protocol.  [[#1]]

     -  Now `Federation.handle()` accepts requests for */.well-known/nodeinfo*.
     -  Added `Federation.setNodeInfoDispatcher()` method.
     -  Added `Context.getNodeInfoUri()` method.
     -  Added `NodeInfo` interface.
     -  Added `Software` interface.
     -  Added `Protocol` type.
     -  Added `Services` interface.
     -  Added `InboundService` type.
     -  Added `OutboundService` type.
     -  Added `Usage` interface.
     -  Added `NodeInfoDispatcher` type.
     -  Added `nodeInfoToJson()` function.

[NodeInfo]: https://nodeinfo.diaspora.software/
[#1]: https://github.com/dahlia/fedify/issues/1


Version 0.1.0
-------------

Initial release.  Released on March 8, 2023.