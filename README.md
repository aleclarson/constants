
# statics v0.0.1 [![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

```coffee
_ = require "statics"

# Define new constants.
_ foo: bar: 1

# Access existing constants.
_.foo.bar

# Throws an error if you try to overwrite existing constants.
_ foo: bar: 1
```
