# Changelog

## 2.0.0-a1 02/03/2026
  - [NEW] Initial release as standalone phpBB extension
  - [NEW] Extracted from bbGuild core as part of the game plugin architecture
  - [NEW] Implements `game_provider_interface` — registers FFXI with bbGuild via tagged services
  - [NEW] `ffxi_installer` extends `abstract_game_install` with clean array-based table names
  - [NEW] `ffxi_provider` supplies game metadata (nations, Allakhazam URLs, JP region)
  - [NEW] Game images served from plugin directory
  - [CHG] Installer uses `$this->table()` helper instead of direct property access
  - [FIX] Legacy `game_id` string concatenation bug corrected to use variable directly
