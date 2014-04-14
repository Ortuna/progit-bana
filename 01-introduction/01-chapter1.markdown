#Examples of Arturo

```elixir
  module Somemodule
    def function(msg) 
      IO.puts msg
    end
  end
```

Trigger I'm changing this word Stuff.

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
