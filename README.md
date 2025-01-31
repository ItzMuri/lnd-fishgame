# lnd-fishgame

- Player have to hover the box over the fish with the Q or E keys and keep the fish in the moving box


```lua
shakeIntensity: number | default is 6

local success = exports['lnd-fishgame']:FishGame(shakeIntensity)

if success then
   lib.notify({
            title = "Fishing",
            description = "You caught a fish! 🎣",
            type = "success",
            duration = 5000
        })
else
   lib.notify({
            title = "Fishing",
            description = "The fish got away... 🐟",
            type = "error",
            duration = 5000
        })
end
```
https://discord.gg/dEv6tm2epA
