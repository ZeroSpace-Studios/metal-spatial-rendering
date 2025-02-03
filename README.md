# Immersive Spatial Rendering with Metal in visionOS

This sample is a minimal example of rendering a fully immersive spatial experience with Metal, ARKit, and visionOS Compositing Services.

## Screenshots
![Example screenshot of spatial rendering](screenshots/01.png)

## Project Overview
This project demonstrates how to create an immersive spatial rendering experience using:
- Metal for high-performance graphics rendering
- ARKit for spatial awareness and tracking
- visionOS Compositing Services for seamless integration
- Environment mapping with HDR textures
- Custom Metal shaders for scene and environment rendering

## Features
- Fully immersive spatial rendering using Metal
- Custom shader implementation for scene rendering
- Environment mapping with HDR support
- Swift and Objective-C++ integration
- Mesh rendering with custom geometry

## Technical Details
The project is structured with the following key components:
- `SpatialRenderer`: Main rendering implementation
- `SpatialRenderingEngine`: Core rendering engine
- `Mesh`: Geometry handling and mesh operations
- Custom Metal shaders:
  - Scene shaders for main rendering
  - Environment shaders for HDR environment mapping

## Dependencies
- Xcode with visionOS SDK
- Metal framework
- ARKit framework
- Swift and Objective-C++ support

## Building and Running
1. Open the Xcode project in the `FullyImmersiveMetal` directory
2. Ensure you have the latest visionOS SDK installed
3. Build and run on a visionOS simulator or device

## Project Structure
```
FullyImmersiveMetal/
├── Core Rendering
│   ├── SpatialRenderer.{h,mm}
│   └── SpatialRenderingEngine.{h,mm}
├── Geometry
│   └── Mesh.{h,mm}
├── Shaders
│   ├── SceneShaders.metal
│   ├── EnvironmentShaders.metal
│   └── ShaderTypes.h
└── Resources
    ├── studio.hdr
    └── bluemarble.png
```

## License
This project is licensed under the terms found in the LICENSE file.
