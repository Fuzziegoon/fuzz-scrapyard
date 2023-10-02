```This is my edit of an edit of qb-scrapyard. ```

```I forked it from https://github.com/Mustachedom/qb-scrapyard```

```Shoutout to Mustachedom for the original fork of this!!```

 I switched parts exchange to a ped. added configurable item for parts exchange as well as configured removal of said item. added a minigame for exchange with configured choice of remove item!

## Dependencies 
https://github.com/dsheedes/cd_keymaster


## how to install 

```
["car_door"] 					 	 = {["name"] = "car_door", 			  	  		["label"] = "car door", 			["weight"] = 2000, 		["type"] = "item", 		["image"] = "car_door.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false, ["combinable"] = nil,   ["description"] = ""},
["car_tires"] 					 	 = {["name"] = "car_tires", 			  	  	["label"] = "car tires", 			["weight"] = 2000, 		["type"] = "item", 		["image"] = "car_wheels.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false, ["combinable"] = nil,   ["description"] = ""},
["car_hood"] 					 	 = {["name"] = "car_hood", 			  	  		["label"] = "car_hood", 			["weight"] = 2000, 		["type"] = "item", 		["image"] = "car_hood.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false, ["combinable"] = nil,   ["description"] = ""},
["car_trunk"] 					 	 = {["name"] = "car_trunk", 			  	  	["label"] = "car_trunk", 			["weight"] = 2000, 		["type"] = "item", 		["image"] = "car_trunk.png", 			["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false, ["combinable"] = nil,   ["description"] = ""},
["car_headlights"] 					 = {["name"] = "car_headlights", 			  	["label"] = "car_headlights", 		["weight"] = 2000, 		["type"] = "item", 		["image"] = "car_headlight.png", 		["unique"] = false, 	["useable"] = false, 	["shouldClose"] = false, ["combinable"] = nil,   ["description"] = ""},
```

add these to items.lua

add the images to your inventory

turn Config.GKS to true if you use that phone
if you use dpemotes turn Config.rpemotes to false
Change the location for Config.breakdown and you should be done!
