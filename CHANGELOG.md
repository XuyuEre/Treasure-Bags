# Treasure Bags Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0] - 2019-05-08
### Added
- Treasure bags can now be used as ingredients in recipes. See wiki for details.
- Shaped and shapeless recipe types for treasure bags. This allows you to create recipes which craft specific treasure bags. You can, of course, combine this with treasure bag ingredients as well.
- JEI can distinguish treasure bags of different types
### Changed
- Treasure bags now display the data pack's ID in the tooltip. Unknown/invalid bags are also indicated in the tooltip.
### Fixed
- Bag types should now synchronize with connecting clients on both dedicated servers and LAN games

## [0.2.0] - 2019-03-31
### Added
- Opening a bag while sneaking will now open the entire stack
- Command, `/treasurebags give` which will give players treasure bags
- Command, `/treasurebags list` which will list all bag type ID's
- Loot tables for entity groups. These will make adding bag drops easier. These are located at `data/treasurebags/loot_tables/entity_group`. The groups are hostile (monster), peaceful (animals), boss, and player.
### Changed
- Like items from a bag will get stacked together (less chat spam) 

## [0.1.0] - 2019-03-28
First release
