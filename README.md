# qb-vehiclekeys
qb-vehiclekeys compatible with qb-lock
all credits go to FjamZoo#0001, i just fixed some errors like hotwire and when lockpicking all vehicles doors unlocking, randomized the amount of circles and the speed
credits to https://github.com/JustLazzy](https://github.com/JustLazzy)
updated by Hipsher#7013 to work with most recent qb-core

## Dependencies

 + qb-lock https://github.com/Tex27/qb-lock
 + qb-core https://github.com/qbcore-framework/qb-core
 + boosting hack https://github.com/Lionh34rt/boostinghack


## Add Item
Go to your qb-core/shared/items.lua and add this line

--security device
	['security_system_device']       = {['name'] = 'security_system_device',        ['label'] = 'Security System Hacking Device', ['weight'] = 100,    ['type'] = 'item',       ['image'] = 'security_system_device.png',		['unique'] = true,      ['useable'] = true,     ['shouldClose'] = true,   ['combinable'] = nil,   ['description'] = 'This device look sus'},
 
