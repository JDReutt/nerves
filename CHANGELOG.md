# Release Notes

## Nerves 0.3.2
* Bug Fixes
  * Support for elixir 1.3.0-dev
  * Invoke `nerves.loadpaths` on preflight of `mix firmware` and `mix firmware.burn`. Fixes `ERROR: It looks like the system hasn't been built!`

## Nerves 0.3.1
* Enhancements
  * Perform host tool checks before executing scripts

## Nerves 0.3.0
* Enhancements
  * Added nerves_bootstrap archive
  * `mix firmware` Create firmware bundles from mix
  * `mix firmware.burn` Burn Firmware bundles to SD cards

## Nerves 0.2.0
* Enhancements
  * Added support for 0.4.0 system paths
