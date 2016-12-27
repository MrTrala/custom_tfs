Changelog
===============

### 2016-12-26
* Added Store System by OTX Team [commit](https://github.com/brunominervino/forgottenserver/commit/ae72873aee1afc0760e1ead9aa8291d78b66d7a2)

### 2016-12-23
* Added Function to NPCs deducts money from Bank Account of Premium Accounts by Mkalo [commit](https://github.com/brunominervino/forgottenserver/commit/8bdfa3596bb864b3e5217e17819e1b67b6e93f9c)

* Added Monster:onSpawn(position) Event (Based on Feature by Xeraphus [OTLand]) [commit](https://github.com/brunominervino/forgottenserver/commit/ad21e49300e167fb291d2009543e66640cbcb566)
```lua
-- Example
function Monster:onSpawn(position)
	local maxHealth = math.random(self:getHealth())
	self:addHealth(-maxHealth)
    return true
end
```

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
