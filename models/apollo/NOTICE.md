# Lab robot

Model: Apptronik Apollo description (MJCF), from MuJoCo Menagerie
https://github.com/google-deepmind/mujoco_menagerie/tree/main/apptronik_apollo
License: Apache-2.0 (see LICENSE in this folder).

Changes: the visual STL meshes were merged, decimated from about 1.39 million to about
276 thousand triangles, and exported with the body tree as one GLB (Blender). Collision
geometry, actuators and sensors were left out. The joint tree and link names are unchanged.
