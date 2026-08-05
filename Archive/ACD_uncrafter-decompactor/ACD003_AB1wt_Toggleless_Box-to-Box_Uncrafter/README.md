# AB1wt Toggleless Box-to-Box Uncrafter
<img alt="AB1wt_Toggless_Box-to-Box_Uncrafter.png" src="images/AB1wt_Toggless_Box-to-Box_Uncrafter.png?raw=1" height="300px">

**Authors:** *Knoxelton*

**Endorsed by:** *XP_Bot*

**Tags:** *Untested, box loading*

**Original post:** [View on Discord](https://discord.com/channels/856232076252282890/1534591774964711637)

A toggle-less box un-compacting/crafting setup that moves redstone blocks into dust from a box to a box at 375 boxes per hour, with global output into shulker boxes and silent operation except during the breaking sequence.
## Features
- Crafts at 8gt, output at 9xhs Directly into a shulker box
- Completely toggle-less
- SS14 detection: once detected a sequence begins that is timed to break the box as soon as the last craft is input to build a full box
- Pause-able with a safety circuit to hold the pause if any slice is in the breaking sequence. Once every slice has broken its box it will pause
- Silent unless breaking sequence is active
- Recycles input boxes to be used for output
- Global output
## Considerations
- No first box placement at crafter
- Larger than other options due to toggle free approach
## Notes
Un-compacts blocks such as redstone blocks > dust from a box to a box, 375 boxes/h.

## Resources
- [ACD003_Uncrafter_Box-to-Box_AB1wt_ARRAY.litematic](attachments/ACD003_Uncrafter_Box-to-Box_AB1wt_ARRAY.litematic): MC 1.21.11, Size 13x16x16 blocks
  - 8 Slices tiled and operational
- [ACD003_Uncrafter_Box-to-Box_AB1wt_END.litematic](attachments/ACD003_Uncrafter_Box-to-Box_AB1wt_END.litematic): MC 1.21.11, Size 3x15x16 blocks
  - Leading edge slice with external components like pause circuit and box recycle
- [ACD003_Uncrafter_Box-to-Box_AB1wt_SLICE.litematic](attachments/ACD003_Uncrafter_Box-to-Box_AB1wt_SLICE.litematic): MC 1.21.11, Size 2x15x16 blocks
  - Middle and far end slices
