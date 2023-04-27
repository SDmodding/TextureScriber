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
