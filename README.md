# 3D-thing

**Skyshard**: a small 3D platformer made with [Three.js](https://threejs.org/). Roll a ball through 8 floating worlds, collect every shard in each one, and deal with the creatures in your way.

## Play

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

Three.js loads from a CDN, so you need an internet connection. The title screen lets you start from level 1 or jump to any world.

## Controls

| Key | Action |
| --- | --- |
| W A S D / arrow keys | Move (relative to the camera) |
| Space | Jump (press again mid-air to double jump) |
| Mouse | Look around (the pointer locks once you click to play) |
| Q / E | Turn the camera without the mouse |
| F / left click | Shoot (once you have the blaster) |
| Shift (mid-air) | Stomp (once you have the boots) |
| Esc / P | Pause |

## Worlds

1. **Sky Meadow**: grassy islands, clouds and moving platforms.
2. **Frozen Peaks**: snowfall and slippery ice.
3. **Ember Caverns**: a lava sea, crumbling platforms and bounce pads.
4. **Neon Void**: a starfield with neon outlines that mixes every platform type.
5. **Glowshroom Grove**: glowing mushrooms and fireflies. Introduces the blaster, hoppers and bats.
6. **Sunscorch Ruins**: a quicksand sea and desert ruins. Introduces stomp boots, turrets and saw blades.
7. **Thunderhead Keep**: rain and lightning. Introduces the shield.
8. **Crystal Core**: the final world, where the Shard Golem guards the last shards.

## Creatures

- **Spiky**: patrols back and forth.
- **Hopper**: jumps up and down in place.
- **Bat**: swoops at you when you get close.
- **Turret**: spits slow projectiles at you.
- **Saw blade**: orbits a platform.
- **Shard Golem**: a boss that chases you and throws rocks. Takes 6 hits.

## Pickups

Pickups appear from world 5 onward. Tools reset at the start of each world.

- **Blaster**: shoots bolts that lock on to creatures in front of you. Each pickup adds 12 ammo.
- **Stomp Boots**: slam down from mid-air. The shockwave hurts every creature nearby.
- **Shield**: blocks the next hit.
- **Heart**: an extra life, up to 5.
