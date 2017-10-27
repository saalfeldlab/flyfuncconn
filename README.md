# flyfuncconn
Resources for fly functional connectome

## Usage
### AntsBigWarpTransform
Applies a series of transformations including a thin plate spline defined by landmarks from BigWarp, and an affine and displacement field from ANTs.
```
java <java args> forFFC.AntsBigWarpTransform <source image file> <target space image file> <big warp landmarks csv> <output> <affine> <displacement field> <number of rendering threads>
```
