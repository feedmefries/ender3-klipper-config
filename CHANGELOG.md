# Changelog

All notable changes to the Ender 3 Klipper firmware configuration will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.
## [1.3.0](https://github.com/feedmefries/ender3-klipper-config/compare/v1.2.1...v1.3.0) (2023-02-18)


### Features

* local-only moonraker authorization configuration ([50a395f](https://github.com/feedmefries/ender3-klipper-config/commit/50a395f18e1c23200f81592bd03a2715cc1c726a))

## [1.2.1](https://github.com/feedmefries/ender3-klipper-config/compare/v1.2.0...v1.2.1) (2023-02-12)


### Bug Fixes

* only clear bed if an object was freshly printed ([8ca0a64](https://github.com/feedmefries/ender3-klipper-config/commit/8ca0a64dd8eb0bfea4f3bfc6986a9e0edc90b371))
* rehome before unload_filament and load_filament if necessary ([3f328fc](https://github.com/feedmefries/ender3-klipper-config/commit/3f328fc3347c1fa4b17741d35305227c9ca696b5))
* set blower fan to 100% when running load_filament or unload_filament ([cd39307](https://github.com/feedmefries/ender3-klipper-config/commit/cd39307fb8ad31ce601c158f159caac1f8f88c87))

## [1.2.0](https://github.com/feedmefries/ender3-klipper-config/compare/v1.1.0...v1.2.0) (2023-02-12)


### Features

* 4.2.2 board pins configuration template ([30d5d7f](https://github.com/feedmefries/ender3-klipper-config/commit/30d5d7ff0ebdbf0de0b96fe7456aec7203501c13))
* 4.2.2 stock display configuration template ([c50ea37](https://github.com/feedmefries/ender3-klipper-config/commit/c50ea378fd0cdff4b69350de762dbc3f92766418))
* add config/machine_specific dir for machine-specific configuration files ([1bd9b84](https://github.com/feedmefries/ender3-klipper-config/commit/1bd9b84eb2f0d32a7974cc7d0f5596a555c1192f))
* output status message to display by default ([af30490](https://github.com/feedmefries/ender3-klipper-config/commit/af30490aa79417346cef5b689bca3e58db9a7a98))
* safe firmware restarting ([58059fb](https://github.com/feedmefries/ender3-klipper-config/commit/58059fbb2d33b64b09718385c21ad7a7020ca44d))
* set bed mesh level probe count to 8x8 ([53e1164](https://github.com/feedmefries/ender3-klipper-config/commit/53e116429d609c5c60155af49c3325b52f67397c))
* v4.2.7 board pin configuration template ([ecaf22d](https://github.com/feedmefries/ender3-klipper-config/commit/ecaf22d0341ef00b25b56fcaf591a26c73866b28))


### Bug Fixes

* cool hotend with toolhead fan when cancelling or ending a print ([b471dcb](https://github.com/feedmefries/ender3-klipper-config/commit/b471dcb32daa0621b09daba3bfb26a30e4fc0465))
* increase end print retraction to 5mm, pause print retraction to 2mm ([281d037](https://github.com/feedmefries/ender3-klipper-config/commit/281d037ca377bcf96e9e383afcb8c7ed7407e577))

## [1.1.0](https://github.com/sethlessard/ender3-klipper-config/compare/v1.0.1...v1.1.0) (2023-01-27)


### Features

* use machine-specific z_offset values for bl touch probe ([18e251e](https://github.com/sethlessard/ender3-klipper-config/commit/18e251e1404886cc7e77ef10f95cde3221aa4ee6))

### [1.0.1](https://github.com/sethlessard/ender3-klipper-config/compare/v1.0.0...v1.0.1) (2023-01-27)


### Bug Fixes

* park after print_cancel or print_end ([#5](https://github.com/sethlessard/ender3-klipper-config/issues/5)) ([8f8abad](https://github.com/sethlessard/ender3-klipper-config/commit/8f8abadc970ef2316a71b7ed5305b37fba698570))

## 1.0.0 (2023-01-27)


### Features

* 0.6mm nozzle ([f0c240a](https://github.com/sethlessard/ender3-klipper-config/commit/f0c240a413ac641ec020c6fd576248f0604b1af2))
* clear_bed macro, print queue prerequisites ([c63b6dc](https://github.com/sethlessard/ender3-klipper-config/commit/c63b6dcb4aa03b336c730103d3a1fd7f8b2366d8))
* configurable prime line ([e5e0043](https://github.com/sethlessard/ender3-klipper-config/commit/e5e0043b00522cacfdd54b4b5c8a162cf4b0f73d))
* faster bed leveling ([e9fd7c8](https://github.com/sethlessard/ender3-klipper-config/commit/e9fd7c8e0b08dee912e7743d09f7b6cc435ade63))
* petsfang v2 + bl touch ([ae228e4](https://github.com/sethlessard/ender3-klipper-config/commit/ae228e4a8d8243d215ff76fef766873b2456c8b1))


### Bug Fixes

* always home before print ([c95fdad](https://github.com/sethlessard/ender3-klipper-config/commit/c95fdadf9be1dca0cc68386b897fe8c577d66ba1))
* bed position ([f5ce760](https://github.com/sethlessard/ender3-klipper-config/commit/f5ce76018e7502d636c1806676da228e5a77f86f))
* increase prime line height for bed clearing ([eb10d85](https://github.com/sethlessard/ender3-klipper-config/commit/eb10d854642775d6f9e9d5dda371e55b2867049d))
* increase sweep speed ([8fc11b9](https://github.com/sethlessard/ender3-klipper-config/commit/8fc11b98ef38176d5e57f3c5d0ca88d98b9345d7))
* load/unload macros ([01d8a78](https://github.com/sethlessard/ender3-klipper-config/commit/01d8a78c41b54e85d61798078ea58bcb4000f547))
* probe z_offset, slow movement speed to 200mms ([39bb129](https://github.com/sethlessard/ender3-klipper-config/commit/39bb129e9745a9a5881a53e9f77f292f060ba23d))
* slower bed clearing (20mm/s) ([404469f](https://github.com/sethlessard/ender3-klipper-config/commit/404469ff8b1da81c6ae5c290dcba39eb3770a3b2))
