
# GE Home Appliances (SmartHQ) Changelog

## 0.6.9

- Added additional fridge controls [#200]

## 0.6.8

- Added Dehumidifier [#114]
- Added oven drawer sensors
- Added oven current state sensors [#175]
- Added descriptors to manifest [#181]
- Bugfix: Fixed issue with oven lights [#174]
- Bugfix: Fixed issues with dual dishwasher [#161]
- Bugfix: Fixed disconnection issue [#169]


## 0.6.7

- Bugfix: fixed issues with dishwasher [#155]
- Added OIM descaling sensor [#154]

## 0.6.6

- Bugfix: Fixed issue with region setting (EU accounts) [#130]
- Updated the temperature conversion (@partsdotpdf)
- Updated configuration documentation
- Modified dishwasher to include new functionality (@NickWaterton)
- Bugfix: Fixed oven typo (@jdc0730) [#149]
- Bugfix: UoM updates (@morlince) [#138]
- Updated light control (@tcgoetz) [#144]
- Dependency version bumps

## 0.6.5

- Added beverage cooler support (@kksligh)
- Added dual dishwasher support (@jkili)
- Added initial espresso maker support (@datagen24)
- Added whole home water heater support (@seantibor)

## 0.6.3

- Updated detection of invalid serial numbers (#89)
- Updated implementation of number entities to fix deprecation warnings (#85)

## 0.6.2

- Fixed issue with water heater naming when no serial is present
- Initial support for built-in air conditioners (@DaveZheng)

## 0.6.1

- Fixed issue with water filter life sensor (@rgabrielson11)

## 0.6.0

- Requires HA 2021.12.x or later
- Enabled authentication to both US and EU regions
- Changed the sensors to use native value/uom
- Changed the temperatures to always be natively fahrenheit (API appears to always use this system) (@vignatyuk)
- Initial support for Microwaves (@mbcomer, @mnestor)
- Initial support for Water Softeners (@npentell, @drjeff)
- Initial support for Opal Ice Makers (@mbcomer, @knobunc)
- Initial support for Coffee Makers (@alexanv1)
- Updated deprecated icons (@mjmeli, @schmittx)

## 0.5.0

- Initial support for oven hoods (@digitalbites)
- Added extended mode support for ovens
- Added logic to prevent multiple configurations of the same GE account
- Fixed device info when serial not present (@Xe138)
- Fixed issue with ovens when raw temperature not available (@chadohalloran)
- Fixed issue where Split A/C temperature sensors report UOM incorrectly (@RobertusIT)
- Added convertable drawer mode, proximity light, and interior lights to fridge (@groto27, @elwing00)
## 0.4.3

- Enabled support for appliances without serial numbers
- Added support for Split A/C units (@RobertusIT)
- Added support for Window A/C units (@mbrentrowe, @swcrawford1)
- Added support for Portable A/C units (@luddystefenson)
- Fixed multiple binary sensors (bad conversion from enum) (@steveredden)
- Fixed delay time interpretation for laundry (@steveredden, @sweichbr)
- Fixed startup issue when encountering an unknown unit type(@chansearrington, @opie546)
- Fixed interpretation of A/C demand response power (@garulf)
- Fixed issues with updating disabled entities (@willhayslett)
- Advantium fixes (@willhayslett)

## 0.4.1

- Fixed an issue with dryer entities causing an error in HA (@steveredden)

## 0.4.0

- Implemented Laundry Support (@warrenrees, @ssindsd)
- Implemented Water Filter Support (@bendavis, @tumtumsback, @rgabrielson11)
- Implemented Initial Advantium Support (@ssinsd)
- Bug fixes for ovens (@TKpizza)
- Additional authentication error handling (@rgabrielson11)
- Additional dishwasher functionality (@ssinsd)
- Introduced new select entity (@bendavis)
- Miscellaneous entity bug fixes/refinements
- Integrated new version of SDK

## 0.3.12

- Initial tracked version