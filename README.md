# BlenderVoxelExporter
Triangle mesh voxelizator, export script.

# Usage
### Note: 
These steps might only work on linux. Windows/osx machines were not tested.
I suggest using blender version 2.7.x
## Build and install python c++ extension
The extension is the core of voxelizer. It gets all the required data from blender and does the voxelization, file output.

Build by running these commands terminal:
```
python setup.py build
```

Install the built script:
```
python setup.py install
```

## Install blender script
To install blender script simply zip the 'voxel_export' script and using blender menu install it like normal addon.

## Use it!
If all went fine you should have new export option available.
