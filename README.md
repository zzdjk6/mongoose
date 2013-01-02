Project Mission
---------------

Project mission is to provide simple, functional, embeddable web server to
make it easy for application and device developers to implement web interface for their
application and devices, and to offer a simple development environment.

Overview
--------

To accomplish it's mission, Mongoose keeps balance on functionality and
simplicity by carefully selected list of features:

- Liberal, commercial-friendly [MIT license](http://en.wikipedia.org/wiki/MIT_License)
- Works on Windows, Mac, UNIX, iPhone, Android, and many other platforms
- Support for CGI, SSL, SSI, Digest (MD5) authorization, Websocket, WEbDAV
- Lua server pages (PHP-like functionality using Lua), see [page.lp](https://github.com/valenok/mongoose/blob/master/test/page.lp)
- Resumed download, URL rewrite, IP-based ACL, Windows service
- Excluding files from serving by URI pattern (file blacklist)
- Download speed limit based on client subnet or URI pattern
- Small footprint: executable size is 50 kB on Linux 2.6 i386 system
- 130 kilobytes Windows executable with all of the above and no dependencies
- Simple and clean embedding API ([mongoose.h](https://github.com/valenok/mongoose/blob/master/mongoose.h)). The source is in single [mongoose.c](https://github.com/valenok/mongoose/blob/master/mongoose.c) file to make things easy.
- Embedding examples: [hello.c](https://github.com/valenok/mongoose/blob/master/examples/hello.c), [post.c](https://github.com/valenok/mongoose/blob/master/examples/post.c), [upload.c](https://github.com/valenok/mongoose/blob/master/examples/upload.c), [websocket.c](https://github.com/valenok/mongoose/blob/master/examples/websocket.c)
- Extensive documentation in form of [User Manual](https://github.com/valenok/mongoose/wiki/UserManual)

Questions can be asked at
[mongoose-users@google.com](http://groups.google.com/group/mongoose-users) mailing list.


Keep Sergey happy
-----------------

Since 2004, Mongoose is being constantly improved by me, Sergey Lyubka. My other software
I give to the community for free is [Super Light Regular Expression library](http://code.google.com/p/slre).
I have a [books wishlist](http://amzn.com/w/1OC2ZCPTQYIEP?sort=priority) on
Amazon. If you feel grateful for the stuff I've done, you can buy me a book! Many thanks to all who
already did so: T.Barmann, D.Hughes, J.C.Sloan, R.Romeo and 4 others.
Appreciated guys, you keep my brains going!
