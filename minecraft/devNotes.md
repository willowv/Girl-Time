# Dev Notes

## Observations
- Purchase vs Sell Trades and Useful early game trades might be a bit off
- Bounties still feel a little wonky maybe

## Issues
- Antique atlas doesn't like shaders, is maybe incompatible with boat item view also
- Something might be up with world generation, every now and then I see terrain that looks pretty janky
- Some villages generate without an icon on the atlas and don't have waystones like they're supposed to; are they missing a tag?
- Panda, Camel, and Sheep textures are messed up for some reason. Currently working around by reskinning sheep and removing camels from the game :grimacing:

## To Do
- [ ] Make all pride tights craftable with dye
- [ ] Make peonies and rose bushes cuttable
- [X] More Villager names
- [ ] Update loot tables or find good redistributable loot mods
- Reduce village loot especially; you get wayyy too much stuff currently
- [ ] Turn off medium and large villages; I prefer player builds up the village vibe
- [ ] Replace slurp bags with bundles
- [ ] Try adding seamless trading back in?
- [ ] Update voices resource pack on Modrinth and recommend the Quieter Mobs mod as accompaniment
- [ ] Reduce the weight of or remove the Villager laugh sound
- [ ] Remove dynamic sound culling; Quieter Mobs is sufficient on its own
- [ ] Look at WTHIT as an alternative to Jade, see what's different about it

## Ideas
- Trading skill tree which gives you the trading post, sales table, request table, decrees, and bounty boards, maybe global reputation as well?
- Talking villagers - see Living Villages mod where name labels are changed to simulate captioned speech
- No sleeping in the rain
- Better pet AI (doesn't light itself on fire???)
- Horse Pokeball kinda mod instead of Horse Whistle - carry your horse with you

### Horse Transport Mod
- Use an item to store a horse, despawning it and keeping the entity data on the item
- Use the item again to summon the horse, clearing the data from the item