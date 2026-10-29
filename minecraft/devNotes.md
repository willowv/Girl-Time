# Dev Notes

## Observations
- Purchase vs Sell Trades and Useful early game trades might be a bit off
- Bounties still feel a little wonky maybe
- Vanilla villages spawn with more villagers than they have beds and workstations, which seems silly

## Issues
- Something might be up with world generation, every now and then I see terrain that looks pretty janky
- Panda, Camel, and Sheep textures are messed up for some reason. Currently working around by reskinning sheep and removing camels from the game :grimacing:
- Village icon does not display on the map when all the way zoomed in; not sure why
- Baby sheep are uhh... vertical? it's honestly hilarious but definitely a bug.
- Handheld map texture gets all janked up with photon
- The auto icons from antique atlas don't propagate into surveyor so they don't show on the Dead Reckoning compass
- The custom villager buildings have some villagers that don't use Data Trades somehow. Not that big a deal but weird.

### Historical
- Removed ChoiceTheorem's Overhauled Villages because the 1.20.1 version has a pretty serious issue where decor spawns at every possible building location along roads. This results in roads being lined with an absurd number of lamps. While the issue was addressed in future versions, those were never backported to 1.20.1. Will consider revisiting if I update the modpack to run on 1.21.1, which I believe is where current Estrogen development is happening.
- Lithostitched has a better method for guaranteeing the inclusion of bounty boards and waystones in village generation, so the respective mods have been configured to not handle their spawning. I instead handle it via Lithostitched json in the Girl Time Worldgen mod.

## To Do
- [ ] Put all the special villager buildings into a shared structure set to make them distance from each other
- [ ] Add translation strings for Additional Fishing
- [ ] Make sure all the BOP wood can be used for crafting tables, chests

## Ideas
- Trading skill tree which gives you the trading post, sales table, request table, decrees, and bounty boards, maybe global reputation as well?
- Talking villagers - see Living Villages mod where name labels are changed to simulate captioned speech
- No sleeping in the rain
- Better pet AI (doesn't light itself on fire???)
- Horse Pokeball kinda mod instead of Horse Whistle - carry your horse with you
- Maybe dagger gift is two daggers?
- Maybe cravings should specifically be for higher saturation things
- Maybe leatherworker sells backpack size upgrades? crafting them feels a little silly
- Maybe villagers don't buy things; you only get emeralds through bounties and loot (except they all still want estrogen)

### Horse Transport Mod
- Use an item to store a horse, despawning it and keeping the entity data on the item
- Use the item again to summon the horse, clearing the data from the item