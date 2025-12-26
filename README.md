# Rubik Cube in Mathematica

![Rubik Cube solution](Rubik_Cube_Solution.gif)

Mathematica notebook that generates the topology of a Rubik’s cube and provides
a set of functions to visualize the cube, reset it, apply single or multiple
moves, scramble it from the solved state, and store and visualize a trajectory.
The notebook also includes a final section that allows exporting a GIF of a
given trajectory.

The cube moves are encoded as strings representing the 12 unique possible moves:

```wolfram
"DIH"  (* Inner right circle, clockwise *)
"DIA"  (* Inner right circle, counterclockwise *)
"DEH"  (* Outer right circle, clockwise *)
"DEA"  (* Outer right circle, counterclockwise *)
"IIH"  (* Inner left circle, clockwise *)
"IIA"  (* Inner left circle, counterclockwise *)
"IEH"  (* Outer left circle, clockwise *)
"IEA"  (* Outer left circle, counterclockwise *)
"AIH"  (* Inner top circle, clockwise *)
"AIA"  (* Inner top circle, counterclockwise *)
"AEH"  (* Outer top circle, clockwise *)
"AEA"  (* Outer top circle, counterclockwise *)
```

## 🛠️ Technologies
- Wolfram Mathematica
- MaTeX package (LaTeX for Mathematica)
