# xali's Better grass

This repository is gonna be used to store multiple texture pack related to grass.

---

## Compatibility
I'll be using compatibility value to help you quickly understand what to expect when downloading a texture pack. Lower compatibility index does not mean that the resource pack is bad. This is purely informative. Some really complete pack might get a lower score but doesn't require as much texture pack. Also not that this is for JAVA texture pack only. Bedrock has a different structure.

### 5/5 
The pack use standart format and consist of only models, blockstates or non texture related changes. Its should be compatible with almost any texture pack.
### 4/5
The pack implement that might get broken or broke other texture pack because it use non standart format or is using custom textures. Packs having mod requirement should also fall upon this categories. Overall the texture pack should still be able to be used without any issues.
### 3/5
Resource pack that heavily change the game and relly heavily on mods will fall upon this categories. When there is a lot of texture with a unique style, it will be more likely to break the immersion especially making it fall upon this categories.
### 2/5
This categories is for resource pack that are likely to break when paired with other packs. It might the pack has a unique style with only certain textures that does not fit with vanilla or because it use some CTM mechanics that affect a lot of blocks and aren't easily modifiable.
### 1/5
This is for texture pack with really poor compatibility. It will be for texture pack that might have a lot of mod requirement that might not be well know or for texture pack that are for server purpose only. 
### 0/5
This categories is kept exclusively for texture pack that include every Minecraft textures in their pack. This a copyright infringement first of all and it will need to be at the bottom of the list to be use with any texture pack. It will also not be compatible with any other texture pack with a score of 0/5.

---

## Resource Pack

### Vanilla v1
This is the most simple one of the bunch with a compatibility of close to 5/5. It simply replace the `grass_block` sides with the top texture. It should work with any texture pack that is using standart format.

### Vanilla v2
This is to give some more details to your game with a compatibility close to 5/5. It replace the `grass_block` sides with the top texture and it use the `grass_block_side_overlay` textures as falling grass under the block. It is taking advantage of the cullface to hide this texture so it shoudl not create any z-fighting.

### CTM v1
Similar to Vanilla v1, it replace `grass_block` sides textures with top texture, but it also use CTM to create overlay over other blocks. Because of the custom overlay texture, compatibility will fall to 3/5 making

### CTM Fast
This one is really similar to Optifine Fancy better grass or LBG Fast. There is some connection when a grass block is placed in diagonal to another one. Currently the only issue I could find is grass block over air block will have the `grass_block_top` texture on it's side instead of `grass_block_side_overlay. Compatbility should still be to 5/5 since it should be compatible with any texture pack with the only requirement is to have a CTM mod.
