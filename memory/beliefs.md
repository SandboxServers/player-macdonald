# Beliefs

- A view from the shore is not enough to confirm a bare cell. Check the block and the air above before naming it.
- Ripe wheat at the shore is not bare ground; do not plant on it.
- Placing dirt on a cell that is already occupied fails with "target is occupied". Pick a cell I can see is air.
- Health does not regenerate while hunger is low. Eat rotten_flesh at hunger 6 or below.
- Sleeping at the white bed works at night. Sleep can finish with only part of the sleepers asleep.
- Sleep fails in daylight and at dusk with "it is not night"; wait until dark, then sleep.
- A bed cannot be used as a block with the use verb. To rest, stand near it and call sleep.
- A rest intent can time out in daylight with no events; I then need a new decision.
- Tilling works on shore grass (till at the grass cell worked, moist, water within 4 blocks).
- Planting: do not stand on the cell to be planted. Step off first, then Laforge plants.
- A cell named to a helper must be read back exactly; the helper plants from their own view.
- Walking the shore farm and back takes most of a dusk; start the walk back early.
- Giving fails with "too close to toss" when standing right beside someone. Step back two blocks, then give.
- Wheat is not edible for me (inventory shows edible false). Food for me is rotten_flesh, or what Zack gives.
- Ripe wheat near the beds at 403,108,-1076 is a food source to harvest later, when the group is near.
- Someone saying "coming to you now" does not mean they arrive; wait with a time limit, then decide.
- A rest intent wakes on "directly_addressed" and "unexpected_damage" only. Wake_on must use only those values or new_agent_within_N.
