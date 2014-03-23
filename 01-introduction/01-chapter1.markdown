#Examples of Arturo

![doodle](http://lh5.ggpht.com/RopvIWl9bL64nCazZchxZRoM6kc_sdazPU4TX_PG7KOHerceJUOIvN8xzLVQqx_u6u4gMrx8EIS9w6tLW1EY9aLP0AWa1kKb_LDTOSsg)

```elixir
  module Somemodule
    def function(msg) 
      IO.puts msg
    end
  end
```

Trigger Commit Test.

##Ruby Code
```ruby
    module Something
        class << self
            alias_method :original_method, :old_method
            def original_method(*args)
                old_method(*args)
            end
        end
    end
```
##Javascript Code
```javascript
    var Git = {};
    Git.user = function(user_name) {
        ..
        return user;
    }
```


## fin!
