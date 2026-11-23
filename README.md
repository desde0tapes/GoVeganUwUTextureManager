<img width="1394" height="798" alt="gjakejgkej4g" src="https://github.com/user-attachments/assets/e49c43e2-bfd2-4127-9dc6-51e382a12e0e" />


# GoVeganUwUTextureManager
BombRush Cyberfunk Map Texture Swapper with Extra QOL play settings.

## Latest Update (v0.3)

* **Map Emissions Attachment feature added!** Include a PNG with the `_NewEmission.png` suffix in your selected texture pack and it will add as an emission texture to any map!
* **SkyboxSwap feature added!** Include a PNG with the name `SkyboxSwap` in your selected texture pack and it will override any skybox of the map! *(doesn't work for 6-faced skyboxes in custom maps)*

---

## Previous Features

* **DIRTY TAGGING IS BACK!!!** This Pre-Patch mod brings back from the early BRC the ability to repeat graffiti tagging the same spot during the same combo without the need to touch the floor, or just tag the same spot over and over while in the air/grinding, etc.
* **NoBoostTrail / TURNS OFF BOOST'S TRAILS + PARTICLES** *(has to be paired with transparent spark textures on UABEAvalonia [included].)*
* **HARDERCHARGE aka Boost Multiplier!** Set a ratio for both earn or waste boost to make the game feel more grindier or easier!

---

## Old v1 Features Still Intact

* **MAP TEXTURE PACK MANAGING.** Quickly activate map texture packs from the community or make your own!
* **HideCypherSpot** Hides the cypher spot upon entering a stage.

---

## Important If You Are Updating

1. Delete your config file (it will create a new config file when you start the game, so it can correctly add the new options). It is called `com.desezerotapes.govegantexturemngr.cfg`, located in your `config` folder inside `BepInEx`.
2. Add and replace the new files from the zip in your same Plugin folder. That's it!

---

## Install Instructions

1. Just extract the `.zip` in the `Plugins` folder of your `BepInEx` folder.
2. Run the game once to generate necessary files and close.
3. Run game again. *(Hideout floor should be darker, meaning it worked; you can delete the ground texture of the Untitled pack from now on)*

*(It's the same process for the Lite version; the folder should be "GoVeganTextureManager" too.)*

---

## What is the Texture Manager?

So I kinda wanted to do this tool for activating texture packs for maps 'cause troubleshooting textures for my map retextures was getting kinda hard 'cause I run a very slow PC, so restarting over and over was getting outta hand, plus the people wanting to swap the vanilla maps' textures faster might find it useful.

This makes the hurdle of editing, loading, and saving assets / map textures via UABE to be made entirely within Windows Explorer instead and completely automatic and sortable for different texture packs at the same time easily.

**tl;dr You can quickly swap vanilla and custom recolored map textures anytime without messing with the internal files. It basically pre-scans the stage's texture names and compares it to the selected Active Pack; if no matches, it uses the vanilla one, otherwise it swaps the texture.**

Works for Vanilla or Mapstation maps.

### How to add Texture Packs

* Just drop into the `Packs` folder your desired Texture packs, or use the default `"Untitled"` pack.

![Texture Packs Folder](https://ia601904.us.archive.org/25/items/692db-1577b-646/692db1577b646.png)

* For reading a new Texture Pack, go to r2modman settings or config manager in-game and type the folder name including capitals to select the desired pack! *(Just reload the stage to see the changes / When adding/editing mid-game, a few textures might need a full game restart)*

**NOTE:** Textures should have **EXACTLY** the same name as the original file (you can check those with UABEAvalonia or any asset inspector). For example: `Hideout_GroundsAtlasTex.png` (with no string numbers).

![Texture Naming Example](https://dn721809.ca.archive.org/0/items/692da-28903cb-9/692da28903cb9.png)

### Currently Supported & Unsupported

**Currently the texture manager works for swapping textures before entering any stage on:**
* All Map Textures (Walls, floors, cars, pickups, etc.)
* Skyboxes
* Billboards
* Cypher dance spot

*(Even works on custom maps—just has to match the texture name and be inside your selected pack.)*

**Doesn't work for:**
* The UIs
* The sun
* Pedestrians
* Characters textures or gears

*(These are still changeable with UABEAvalonia, DripRemix, or by dropping assets like always.)*

You can test a Texture Pack with my [Abandoned Texture Pack](https://gamebanana.com/mods/641494) downloadable [here](https://gamebanana.com/mods/641494).

---

## SkyboxSwap Details

**INSTRUCTIONS TO USE:** Include or make a folder with a PNG named `SkyboxSwap.png` with your desired skybox, and it will override any stage's skybox upon load *(doesn't work for 6-faced skyboxes of custom maps)*.

You can either make a new folder with only your Skybox that you want to swap:

![SkyboxSwap Folder Example 1](https://archive.org/download/gkaw4ig/gkaw4ig.png)

![SkyboxSwap Folder Example 2](https://archive.org/download/gjkae-4gkeaj-4g-1/gjkae4gkeaj4g%201.png)

Or include it in any texture pack folder, overriding the skybox of any vanilla map and most custom maps, with no need to match the skybox file name at all!

![SkyboxSwap Inside Pack Example](https://archive.org/download/jgawkjg3/jgawkjg3.png)

---

## Map Emissions Attacher

**INSTRUCTIONS TO USE:** Include a PNG with the `_NewEmission.png` suffix in your selected texture pack and it will add as an emission texture to any map!

For example if you want to make a "night" version of a map that lacks an Emission Texture, add in your selected pack the same texture with your emissions using the same name file but add _NewEmission to the end of it.

<img width="741" height="565" alt="image" src="https://github.com/user-attachments/assets/18846808-869b-4669-90ea-1ab416cd4ea3" />


---

## NoBoostTrail Details

![NoBoostTrail Example](https://ia801003.us.archive.org/24/items/screenshot-2433/Screenshot%20%282433%29.png)

**HOW TO GET THE FULL NoBoostTrail NOR PARTICLES EFFECT (Hide remaining spark effects on boost pack)**

Just use the 2 attached transparent spark textures and replace them with UABEAvalonia.

The sparks are barely noticeable in-game originally, so after this switch, the NoBoost mod comes in very handy and works in hot-swap mode.

*(The trail effect needs a full game restart to turn back on after disabling once.)*

Refer to [this tutorial](https://gamebanana.com/mods/577264) to learn how replacing textures on UABEAvalonia works.

---
