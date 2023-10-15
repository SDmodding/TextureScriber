# TextureScriber
Simply said a texture creation

### Config explanation
```xml
 <!-- Inside MediaPack you got list of resources which will be added to texture -->
<MediaPack>
  <!-- Just copy this to new line and change name of the file to add new resource -->
  <Resource ForceAlignSize="true">texture.png</Resource>
</MediaPack>
```
### Usage
Simply run `Script.bat` and name the texture name, but be aware. 

If you actually wanna use the texture and use with FileRedirector you need to name the texture as file path ex. `UI\options_controllers_TexturePack`, otherwise the texture wont load because Resource UID will mismatch!

## Resource Params
OutputName
 - Name of the texture instead relying on filename.

Suffix
 - Suffix for texture name.

Mipmaps
 - Unknown (Integer)

NumVolumeSlices
 - Unknown

ArraySize
 - Unknown

AlphaState
 - Options:
   - None
   - Blend
   - Modulate
   - Additive
   - PunchThru
   - Premultiplied
   - Overlay
   - ModulatedRGBSrcAlpha
   - Screen

Compression
 - Options:
   - None
   - A8R8G8B8
   - R5G6B5
   - A1R5G5B5
   - X8
   - X16
   - DXT1
   - DXT3
   - DXT5
   - DXT1_N
   - DXT5_N
   - BC6H_UF16
   - BC6H_SF16
   - BC7
   - BC7_SRGB

ResizeFilter
 - Options:
   - None
   - Box
   - Point
   - Triangle
   - Linear

TilingU & TilingV
 - Options:
   - Clamp
   - Mirror

Filter
 - Options:
   - Linear
   - Point
   - Anisotropic
   - Convolution

Aniso
 - x1, x2, x4, x6, x8, x10, x12, x16

MipMapBiasPreset
 - Options:
   - EagleEye
   - Slider0
   - Slider1
   - Slider2 
   - Slider3
   - Slider4
   - Custom

MipMapBias
 - Unknown
