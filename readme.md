## Modified GLTFCore for importing OpenRooms dataset into UE5

Before building UE5 on linux, copy the 4 files in this github repository to their 
corresponding locations in the UE5 source directory.

```
cp ExtensionsHandler.cpp {UE5_source_dir}/Engine/Plugins/Editor/GLTFImporter/Source/GLTFCore/Private/GLTF/ExtensionsHandler.cpp
cp ExtensionsHandler.h {UE5_source_dir}/Engine/Plugins/Editor/GLTFImporter/Source/GLTFCore/Private/GLTF/ExtensionsHandler.h
cp GLTFAsset.h {UE5_source_dir}/Engine/Plugins/Editor/GLTFImporter/Source/GLTFCore/Public/GLTFAsset.h
cp GLTFNode.h {UE5_source_dir}/Engine/Plugins/Editor/GLTFImporter/Source/GLTFCore/Public/GLTFNode.h
```