# GRIDRUNNER asset pack

Stills, cutouts, textures, and Dream Loop targets. No game code.

```
library/     catalog stills
cutouts/     photo-extracted PNGs with alpha
textures/    PBR albedos / normals
targets/     scene stills
dream-loop/  TRELLIS inputs
```

Grab via **Code → Download ZIP**, or clone:

```
git clone https://github.com/jalapenoseed/GRIDRUNNER-assets.git
```

## 3D objects (`models/`)

These are GLBs exported from the in-game meshes (photo-extruded camel, 3D cone, signs, adobe house).

They are **not** TRELLIS / Fal photogrammetry. That step needs `FAL_KEY`. Drop a Fal key in the game env and the Dream Loop jobs in `.dream-loop/fal-jobs.json` will replace these with real image-to-3D meshes.

| file | what |
|---|---|
| `camel.glb` | extruded from the camel still |
| `cone.glb` | 3D traffic cone |
| `sign-*.glb` | pole + extracted sign face |
| `adobe-house.glb` | stucco house + roof |
| `camp-chair.glb` | camp chair |
