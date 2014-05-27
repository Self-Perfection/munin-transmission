This is preliminary version of lightweight munin plugin for monitoring of transmission bittorrent client throughoutput and torrent count. Currently only netrc auth is supported.

TODO:
- [ ] Set up proper licensing lines (???) GPLv3????
- [ ] Add user/password authorization support;
- [x] Allow setup without specifying hostname. Use localhost in such cases;
- [x] Switch to bash and bash arrays for proper handling of special characters (e.g. spaces) in user/password/netrc file path;
- [ ] Write documetation for munin-doc;
- [ ] Write nice README.md;
- [x] Switch to parsing strings with bash regular expressions and other embedded features to drop sed dependency.
- [ ] Allow auto config. Check if there is available transmission rpc on localhost:9091.
