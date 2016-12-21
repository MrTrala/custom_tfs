Changelog
===============

### 2016-12-21
* Added Reset System [commit](https://github.com/brunominervino/forgottenserver/commit/49055485faef93a5ae2179117149a108604541a6)

```lua
-- Reset System
local player = Player(...)
player:getReset()
player:setReset(1)
```

### 2016-12-20
* Added Account Storage Functions [commit](https://github.com/brunominervino/forgottenserver/commit/1d84cba5a05f43eb0ce47897df390d3ff3298c0e)

```lua
-- Account Storage
local player = Player(...)
player:getAccountStorageValue(1000)
player:setAccountStorageValue(1000, any_number)
```
