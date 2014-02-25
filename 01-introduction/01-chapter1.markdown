#Examples of Arturo


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
