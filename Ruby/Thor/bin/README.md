#Bin folder 

This is where your main directory executable will go. It should only reference
the main Thor executable in the 'lib' directory.

```ruby
#!/usr/bin/env ruby
require_relative "../lib/<file>"

<Your code>.start(ARGV)
```

