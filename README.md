# 🏘️ Infinite Villages Everywhere!
**Turn your world into one endless, sprawling city lol like the congested Manila. 🥲️👌️** 

> This datapack overrides the default structure generation to spawn villages in **every single available chunk**.  
> No more empty plains—just an infinite ocean of houses, farms, and villagers.

---

## ⚙️ CRITICAL SETUP! (If you don't know how to fully utilize this)
For this datapack to work, you **MUST** set your world to **Superflat** and use the **Plains** biome. Villages cannot spawn in the default "Classic Flat" biome.

### 1. Create New World
Select **World Type: Superflat**.

### 2. Customize the Preset
Go to **Customize -> Presets** and paste this **exact** code into the box:
`minecraft:bedrock,2*minecraft:dirt,minecraft:grass_block;minecraft:plains`

*(If you don't do this, the biome will be "Minecraft:Plains" by default, which is good, but if you leave it as "Classic Flat", no villages will spawn maybe!)*

### 3. Add the Datapack
Click **Data Packs**, drag the zip file in, and ensure it is on the **Selected** (right) side!

### 4. If you're in the world and see the villages everywhere?
Then you're good and set to go!
But first make sure it's enabled when not enabled, if not...
Then do this: `/datapack enable "file/Villages Only World.zip"` to ensure it's working properly!

---

## 🛠️ Technical Details
*   **Structure:** `minecraft:village_plains`
*   **Separation:** 1 chunk
*   **Spacing:** 2 chunks
*   **Format:** Hybrid `pack.mcmeta` supporting formats 48 to 105

Heavily inspired by my thoughts lol and there's one for [Planet Minecraft](https://www.planetminecraft.com/data-pack/the-infinite-village/) as a great alternative for this!
