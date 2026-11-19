# renderer.info — cover

Album: BIA
Scene: route-owned R3F Canvas, original-size glTF model, and a fallback stage; no orbit controls or route-level lights are added. The `.glb` includes one exported punctual point light named `Point`, loaded by GLTFLoader. Shadows off; DPR cap [1, 1.5].
Unit cap, any scene: desktop ≤ 200 calls, mobile ≤ 80.

Pins: three@0.185.1, @react-three/fiber@9.8.2, @react-three/drei@10.7.9, react@19.3.1 (this repo's package.json).

The final model is not present yet. Add `public/models/bia.glb`, inspect it with `gltf-transform inspect`, and replace the pending row below with measured values from `/covers/bia?budget`. Do not use the fallback box to report model triangle counts.

| Run | Machine, date | Shadows | calls | triangles | geometries | textures | Accepted |
| --- | --- | --- | --- | --- | --- | --- | --- |
| cover fallback (no model asset) | pending | off | pending | pending | pending | pending | pending |
| cover with Blender .glb | pending | off | pending | pending | pending | pending | pending |
