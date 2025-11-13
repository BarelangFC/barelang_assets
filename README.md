# BFCBotK — URDF model (2025)

This repository contains the BFCBotK URDF and mesh files. The BFCBotK model and meshes are in the `BFCBotK/` folder.

Preview:
![URDF preview](./Screenshot%20from%202025-10-27%2020-26-07.png)

Instructions and Tips
- URDF Viewers that you can use:
  - https://gkjohnson.github.io/urdf-loaders/javascript/example/bundle/
  - On VSCode, You can use extension URDF Visualizer, etc.
- STL Viewers:
  MeshLab, FreeCAD, Mesh viewers, Blender. Meshlab instalation below:
  https://en.ubunlog.com/meshlab-install-this-3d-mesh-editor-on-ubuntu/

  Note: If you want to convert URDF to mjcf, simplify each STL. You can do this using MeshLab with Filters->Remeshing, Simplification and Reconstruction->Simplification: Quadric Edge Collapse Decimation.

- Files of interest:
  - BFCBotK/BFCBotK.urdf
  - Meshes: all `.STL` files in `BFCBotK/`