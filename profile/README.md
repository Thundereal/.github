<p align="center">
  <a href="https://thundereal.org"><img src="thundereal-mark.svg" width="88" height="88" alt="Thundereal"></a>
</p>

<h1 align="center">Thundereal</h1>

<p align="center"><b>Parametric 3D CAD. Everything you dreamed of. And then some.</b></p>

<p align="center">
  <a href="https://thundereal.org">Website</a> &middot;
  <a href="https://github.com/Thundereal/ThunderealCAD">Source</a> &middot;
  <a href="https://github.com/Thundereal/ThunderealCAD/discussions">Discussions</a> &middot;
  <a href="https://github.com/Thundereal/ThunderealCAD/issues">Report a bug</a>
</p>

Thundereal is FreeCAD rebuilt where it counts:

- **A live renderer** -- physically based materials, shadows, glass and
  water, surface finishes with threads that look cut, MaterialX and Blender's
  Cycles, all in the window you model in, live while you edit.
- **A kernel that finishes the job** -- its own fork of OpenCASCADE, fixing
  the thickness, fillet and draft cases that fail upstream.
- **A model with a memory** -- every step kept in the document's transaction
  log, with versions, branches, merge and shape diff on top.

Open source (LGPL-2.1-or-later). Opens FreeCAD files and keeps FreeCAD's
Python API. Linux, Windows and macOS, and browser and mobile through sharing.

Thundereal is a fork of [FreeCAD](https://www.freecad.org), grown out of the
Link branch where `App::Link` and the first topological naming fix started.
It is an independent project: please report its bugs
[here](https://github.com/Thundereal/ThunderealCAD/issues), not upstream.
