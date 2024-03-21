# hub_anarchyville
 
![aville01](https://i.imgur.com/EvbrNFu.jpg)

## Intro
**Anarchyville** is an exterior city block that uses **loading-door-map-transitions** to connect the **exterior** "open world" with completely separate maps that act as the **interiors** of the buildings.

A concept similar to the buildings in **GTA Online**, **Zelda: Ocarina of Time**, & many other games.  (Nearly identical to what you're used to in GTA Online.)

## Interior Maps (Insides of Buildings)

- Completely separate maps that act as building interiors.
- Each building's interior is a different map made by a different person.
- Should have windows & doors at locations *similar* to what exterior shows.
- Loading-door-map-transitions are used for entering/exiting.
- Not limited to only 1 loading door.

Each completely separate interior map is created by a different individual **developer**. Just like in GTA Online - the interiors are *reminiscent* of what the building looks like on the exterior, but do not actually need to match perfectly.

The **loading-door-map-transitions** mean that the city block is un-loaded when you enter a building.  And it means that interior maps need to have loading doors of their own for exiting back out into the city.


## Overworld Map (Exterior City Block)
The city block that has all of the different building exteriors is like an open world and must be kept very optimized, so Anarchyville has a low-poly & low-detailed art style.

The **CITY PLANNER** is in charge of building the exterior and composing the buildings into a somewhat-coherent city. All of the streets connecting things, the sidewalks, the street lamps - the CITY PLANNER is in charge of all of this. (It is all inside `hub_anarchyville.vmf`.)

However, the exteriors of each building is actually a **Hammer++ VMF instance** that different individual developer creates for their building.

**This is how we build together in the same map!**

Each individual creates a the outside of **their** building in a special VMF with their name on it, **in addition** to creating the inside as a completely separate map.

Exteriors should be *somehwhat* optimized & follow Anarchyville's art style, while on the interiors you can go as crazy as you like w/o worrying about lagging down the city at all.

## Building Exteriors (Instanced VMFs)
Inside of the `refs` folder will be a VMF with your name on it. If you don't have a VMF with your name on it, contact me (SM Sith Lord) on the Discord.

You should only modify/build in the VMF with your name on it. This VMF is **only** the exterior of your building. By default, it will have at least the basic shape of your building & some *suggestions* on where to put doors.

Anything you build in this VMF gets **instanced** into the city block.

You'll often want to see how your building looks inside of the city or even do a test compile. Open `hub_anarchyville.vmf` in **Hammer++** to do this. No changes need to be made - it should automatically show your building exterior in the city.

## Developers
There is a limited amount of space per-city block. This city block has 1 building still unclaimed - contact me in the Discord if you'd like to participate & claim it.

Additional blocks will be created when this block fills up. (Each block is itself separated with a loading-door-map-transition, so there's no limit to how many blocks we make.)

| Creator | Exterior | Interior |
| ------- | -------- | -------- |
|SM Sith Lord **(CITY PLANNER)**|![](https://i.imgur.com/ZKkTEra.jpeg)|![](https://i.imgur.com/9J4oHLX.jpeg)|
|ZombieW33d|![](https://i.imgur.com/K32n4vh.jpeg)|![](https://i.imgur.com/V4oCVkG.jpeg)|
|Xaphian|![](https://i.imgur.com/lZJPSAl.jpeg)|![](https://i.imgur.com/lkoK6xV.jpeg)|
|FunkyPixie|![](https://i.imgur.com/WorcNcX.jpeg)|TBD|
|MexC|![](https://i.imgur.com/6Zvv0vb.jpeg)|TBD|
|OkeDoke|![](https://i.imgur.com/ugLLKFR.jpeg)|TBD|
|Pux|![](https://i.imgur.com/DTLI9Wo.jpeg)|TBD|
|Dralloc|![](https://i.imgur.com/fYkvMyg.jpeg)|TBD|
|Eko|![](https://i.imgur.com/AeojxNj.jpeg)|TBD|

## Contributing
The GitHub repo to download the project files is at https://github.com/smsithlord/hub_anarchyville

If you click the big **CODE** button, there is a **Download ZIP** link that appears. You want the contents of the ZIP to live at `aarcade_user/mapsrc/hub_anarchyville`.

To be clear - this means that the VMF itself would be at the following location if unzipped correctly: `aarcade_user/mapsrc/hub_anarchyville/hub_anarchyville.vmf`

When you've made changes to your VMF, you can either send me (SM Sith Lord) your VMF, or do a pull request on the GitHub repo.

If you need any help or have any questions, you can hit me up on the Discord or on my Twitch stream.
