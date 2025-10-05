# Game-the-Small-Engineer
🧩 Game-the-Small-Engineer — A strategic open-source card game where shapes come alive! Fuse, corrupt, and battle Circles, Squares, and Triangles using math-driven attributes and creative tactics to master the geometry realm. Build, think, and play like a small engineer!

🧩 Game-the-Small-Engineer

Game-the-Small-Engineer is an open-source strategy card game about geometry, logic, and creativity.
You play as a small engineer who uses geometric shapes — circles, squares, and triangles — to battle, fuse, and evolve into stronger forms.
The game mixes math-based strategy with fun and imagination.

🎮 Game Overview

Each player starts with 4 cards.

Each turn, a player draws 2 cards.

Players can play 1 Shape card and 1 Special card per turn.

The goal is to use shape attributes and special effects to defeat your opponent.

🧠 2D Environment Rules

Shapes have three main attributes:

Perimeter – smaller is better (means the shape is more efficient).

Area / Perimeter – higher is better (represents efficiency).

Area / Perimeter² – fixed value; smaller is better (stability measure).

🔺 Shape Summary (2D)
Shape	Best Attribute	Weakest Attribute
Circle	Area / Perimeter	Perimeter
Square	Perimeter	Area / Perimeter²
Triangle (Equilateral)	Area / Perimeter²	Area / Perimeter
🧊 3D Environment Rules (Fusion of Same Shapes)

When you fuse two identical shapes, you create a 3D version (Sphere, Cube, Prism).

Attributes:

Surface Area – Best: Prism | Worst: Spherical

Volume / Surface Area – Best: Cube | Worst: Prism

Volume / Surface Area² – Best: Spherical | Worst: Prism

🔷 3D Environment (Fusion of Different Shapes)

When you fuse two different shapes, you create a Mixed Polygon Card:

Fusion	Best Attribute	Weakest Attribute
T + S	Perimeter	Area / Perimeter
S + C	Area / Perimeter	Area / Perimeter²
C + T	Area / Perimeter²	Perimeter
🧩 Special Cards

Fusion Card – combine two shapes to form a 3D or mixed shape.

X-Change Card – modifies shape strength based on the ratio of cards between players.

(Coming Soon) Shadow Card – corrupts shapes into distorted versions.

🚀 Future Plans

Add Shadow, Mirror, and Quantum special cards.

Expand with new shapes (Pentagon, Hexagon, Star).

Create a digital version of the game with AI logic.

Add multiplayer online play and deck customization.

🌟 Open Game Project

This is a community project — everyone can improve balance, add ideas, or build digital tools.
If you love math, geometry, and strategy — join us and become a Small Engineer!
