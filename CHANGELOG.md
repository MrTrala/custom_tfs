Changelog
===============

### 2016-12-21
* Added Reset System
Example:
```lua
local player = Player(...)
player:getReset()
player:setReset(1)
```

### 2016-12-20
* Added Account Storage Functions
Example:
```lua
local player = Player(...)
player:getAccountStorageValue(1000)
player:setAccountStorageValue(1000, any_number)
```
