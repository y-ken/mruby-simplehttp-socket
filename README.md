# SimpleHttp Class for mruby

SimpleHttp has forked from iij/mruby.

## dependency

* mruby-io https://github.com/iij/mruby-io
* mruby-socket https://github.com/iij/mruby-socket
* mruby-pack https://github.com/iij/mruby-pack
* mruby-http https://github.com/mattn/mruby-http

## example

```ruby
p SimpleHttp.new("127.0.0.1", 80).request("GET", "/index.html", {'User-Agent' => "test-agent"})
```

## License
under the MIT License:

* http://www.opensource.org/licenses/mit-license.php
