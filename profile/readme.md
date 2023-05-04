# The Spartan Project

We are like ms edge. Just look at the name. We are not a part of Microsoft.

## enjoy our code and NerdOS :-)

## discord

https://discord.gg/invite/R5bgPEkFMe
## NerdOS-RoadMap

```mermaid
graph TD
A[Journaling];
B-->C[FAT32];
B-->D[EXT2];
A-->B[Custom filesystem];
E[Bitmaps];
F[Fonts];
B-->E;
E-->F;
E-->G[GUI];
F-->I;
I-->H[GUI Games];
E-->I[LibGUI];
I-->J[Porting things];
H-->J;
G-->J;
B-->L[LibC];
L-->J;
C-->M[USBs];
D-->M;
L-->P[Userspace];
C-->O[Initrd];
O-->L;
L-->O;
O-->P;
```
