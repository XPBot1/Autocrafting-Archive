# Shulker Box Dyer
<img alt="image.png" src="images/image.png?raw=1" height="300px">

**Authors:** *CommandLeo*

**Endorsed by:** *XP_Bot*

**Tags:** *Tested & Functional*

**Original post:** [View on Discord](https://discord.com/channels/856232076252282890/1534584887258910880)

A contraption that accepts as input shulker boxes of any color and turns them into shulker boxes of a specific color at hopper speed. Unlike other designs, this one works even when you input shulker boxes of the same color as the desired output.
## Features
- Accepts input shulker boxes of any color
- Turns them into shulker boxes of a specific color at hopper speed
- Works even when you input shulker boxes of the same color as the desired output
## Notes
The crafter has all slots locked except for two. The first slot is empty, while the second one contains the dye item.
Here is the sequence of actions that occur when running the contraption:
 - The input shulker box is put in the first slot of the crafter.
 - The top dropper inserts a dye item into the crafter if there's space available in the second slot, otherwise it doesn't do anything.
 - The crafter triggers: if the crafting attempt is successful, the output goes into the dropper on the right and immediately gets sent back into the first slot of the crafter (the rails ensure the correct update order). Otherwise no dye is consumed and the input shulker box stays in the first slot of the crafter.
 - The hopper under the crafter is briefly unlocked so it can pull out the shulker box.
## Compatibility
[1.21+]

## Resources
- [ACS010_CommandLeo_Shulker_Box_Dyer.litematic](attachments/ACS010_CommandLeo_Shulker_Box_Dyer.litematic): MC 1.21.1, Size 4x5x3 blocks
