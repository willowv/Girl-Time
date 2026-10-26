# Dev Notes

## Observations
- Purchase vs Sell Trades and Useful early game trades might be a bit off
- Bounties still feel a little wonky maybe

## Issues
- Something might be up with world generation, every now and then I see terrain that looks pretty janky
- Panda, Camel, and Sheep textures are messed up for some reason. Currently working around by reskinning sheep and removing camels from the game :grimacing:
- Village icon does not display on the map when all the way zoomed in; not sure why

### Historical
- Removed ChoiceTheorem's Overhauled Villages because the 1.20.1 version has a pretty serious issue where decor spawns at every possible building location along roads. This results in roads being lined with an absurd number of lamps. While the issue was addressed in future versions, those were never backported to 1.20.1. Will consider revisiting if I update the modpack to run on 1.21.1, which I believe is where current Estrogen development is happening.
- Lithostitched has a better method for guaranteeing the inclusion of bounty boards and waystones in village generation, so the respective mods have been configured to not handle their spawning. I instead handle it via Lithostitched json in the Girl Time Worldgen mod.

## To Do
- [X] More Villager names
- [X] Update loot tables or find good redistributable loot mods
- Reduce village loot especially; you get wayyy too much stuff currently
- [X] Tweak village sizes (will need to override CTOV datapack most likely) to make villages smaller
- [X] Turn off vanilla villages? They're just not very pretty in comparison and are missing the bounty board and waystone
- [X] Replace slurp bags with bundles
- [X] Try adding seamless trading back in? I genuinely don't know why I removed it, seems to work fine
- [ ] Update voices resource pack on Modrinth and recommend the Quieter Mobs mod as accompaniment
- [ ] Reduce the weight of or remove the Villager laugh sound
- [X] Remove dynamic sound culling; Quieter Mobs is sufficient on its own
- [X] Look at WTHIT as an alternative to Jade, see what's different about it

## Ideas
- Trading skill tree which gives you the trading post, sales table, request table, decrees, and bounty boards, maybe global reputation as well?
- Talking villagers - see Living Villages mod where name labels are changed to simulate captioned speech
- No sleeping in the rain
- Better pet AI (doesn't light itself on fire???)
- Horse Pokeball kinda mod instead of Horse Whistle - carry your horse with you

### Horse Transport Mod
- Use an item to store a horse, despawning it and keeping the entity data on the item
- Use the item again to summon the horse, clearing the data from the item