# This is an api wrapper made for roblox luau executor to secure your script

Logging in example:
```lua
local spectre = loadstring(game:HttpGet('https://thisrepo.com'))() 

spectre.apikey = "aa2b1a-55kl4a-44aqp1"
```
# This logins using your credentials which can be gained by buying or asking me for a key

Whitelisting people and securing your script using spectre/astralguard
```lua
local spectre = loadstring(game:HttpGet('https://thisrepo.com'))() 

spectre.apikey = "aa2b1a-55kl4a-44aqp1"

 --<table, boolean> spectre.authenticated('key-example') <str> -- this requires a key otherwise it will be automatically invalid
 --this returns a table which is the expiration, boolean as valid
local UserKey = "test-key-abcd"
local IsAuthenticated = spectre.authenticated(UserKey) -- Example the database has these keys authenticated: {a,b,c}
if IsAuthenticated then
  print('true authenticated')
else
  print('false failed')
end
```
