# SimpleHttp Class for mruby

SimpleHttp has copied from iij/mruby using mruby-socket and mruby-http

## example

```ruby
p SimpleHttp.new("127.0.0.1", 80).request("GET", "/index.html", {'User-Agent' => "test-agent"})
```

# License
under the MIT License:

* http://www.opensource.org/licenses/mit-license.php
