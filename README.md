triangulated-lamps
==================

script and model files for creating triangulated structures

this project requires the Windows version of Rhino 5 : http://www.rhino3d.com

you can create your own lamp, or any arbitrary shape by following the layer and geometry conventions in lamp base.3dm:
- draw a triangulated mesh and a layer called "mesh", make sure that mesh is the only object present on that layer
- draw (or extract from the mesh) all edges that will need to be joined (this will be every edge but those at the top where the lamp opens to the ceiling in the exmaple)
- place these lines on a layer named "edges", make sure no other objes are on that layer
- you can also draw an extra piece of geometry to help attach the lamp to the threaded lamp shade post present on most lamps and light fixtures
