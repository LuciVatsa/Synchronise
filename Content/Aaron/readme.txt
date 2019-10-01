How to Use BlinkBlocks
======================

1. BlinkBlocks will snap toward other BlinkBlocks that blink at the same rate. This snapping is
   referred to as syncing in the blueprints. But BlinkBlocks cannot sync when near BlinkBlocks of
   a different blink period, so these must be pushed away. Once a set of BlinkBlocks are all synced,
   a Door listening to them can open.
2. There are three blueprints you'll want to use: BlinkBlockFast, BlinkBlockSlow, and Door.
	a. BlinkBlockFast blinks red and quickly
	b. BlinkBlockSlow blinks blue and slowly
	c. Door can be placed anywhere and (in the editor) told which BlinkBlocks it cares about.
	   Once all of the BlinkBlocks the door has in its list say they are synced, then the 
	   doors will slide aside.
3. Place BlinkBlockFasts and BlinkBlockSlows where you want them; you don't have to use both types,
   but you'll need at least two of each type you use. Then place a Door wherever you want to open 
   up once the right BlinkBlocks are set.
4. Once the player has made all blocks synced (again, close to another with the same blink period
   and not near another with a different blink period), the Door can open.