# RecipeBook Changelog

## Unreleased

- Right-click a recipe with drop/pickpocket sources to open a popup listing every creature that drops it, with zone and drop rate. Click any NPC in the popup to set it as your AddressBook waypoint target.
- Replaced MaNGOS-derived phase data with RecipeMaster TBC's hand-curated annotations across all 12 professions
- Jewelcrafting world-drop designs now show drop zones (scraped from Wowhead) and work with zone/continent filtering
- Fixed phase dropdown only being clickable on the right side of each entry

## v1.0.0 - Initial Release

- Browse all TBC profession recipes grouped by source type (Trainer, Vendor, Quest, Drop, etc.)
- 12 professions supported including Jewelcrafting
- Continent and Zone filtering with Auto-detect
- Phase filtering (Phases 1-5) with zone-based phase inference
- My Faction filter to hide opposite-faction recipes
- Search bar for quick recipe lookup
- Known recipe tracking via profession window scanning
- Hide Known toggle (auto-enabled for known professions)
- Collapsible source categories
- Waypoint integration via AddressBook + TomTom
- Shift-click to link recipes into chat
- Recipe names colored by item quality
- World drop detection (10+ NPC threshold)
- Minimap button via LibDataBroker
