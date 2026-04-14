# Wire Curtain Playground 〰️

A Pen created on CodePen.

Original URL: [https://codepen.io/NiklasKnaack/pen/dPpqEgW](https://codepen.io/NiklasKnaack/pen/dPpqEgW).

A little experiment simulating a hanging curtain made out of multiple wires.

Each wire consists of connected points (Verlet-style physics), influenced by gravity and constraints. All wires are then stitched together into a surface using triangles, creating a flexible curtain-like structure.

On top of that, a simple lighting model (ambient + diffuse) is applied, using a fake Z-offset per wire to simulate depth and shading — no real 3D involved.

You can interact with the curtain using your mouse, tweak physics and lighting parameters via the GUI, and switch between different render modes (wireframe, shaded, checkerboard).

Built with vanilla JS, typed arrays and a focus on performance.

Have fun playing with it :)