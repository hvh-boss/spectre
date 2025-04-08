# This is an api wrapper made for roblox luau executor to secure your script

Logging in example:
```lua
local astral = loadstring(game:HttpGet('https://thisrepo.com'))() 

astral.apikey = "aa2b1a-55kl4a-44aqp1"
```
# This logins using your credentials which can be gained privately or publicly.

Simulating game anticheat/decaying winter anticheat detections 
So you can bypass it your own without worrying about getting banned
```lua
local astral = loadstring(game:HttpGet('https://thisrepo.com'))() 

astral.apikey = "aa2b1a-55kl4a-44aqp1"

local simulator = astral.simulate()

simulator.trigger('output') <string::type>, you can also do 'kick'
```
