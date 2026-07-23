<img width="1104" height="586" alt="screen2" src="https://github.com/user-attachments/assets/e50ad23c-c3f2-4cd9-aaed-39b20123cc17" />
Single HTML file with a zoomable data canvas containing bubbles.

Features:

* Move, resize, rename, re-parent, and delete bubbles.
* Supports an extremely deep hierarchy, with a maximum depth approaching `Number.MAX_SAFE_INTEGER`. At such extreme depths, JavaScript floating-point precision limitations may cause non-deterministic-like behavior. Fun to watch and 100% safe.
* Save and load data locally or from files.

Data files are encrypted with a password using a simple XOR-CBC encryption algorithm.

Like rectangles more? Check this repository:
https://github.com/OneTimePads/RectangleDataCanvas/tree/master
