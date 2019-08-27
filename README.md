# How to set up Unity WebGL Template

執行 WebGL 時都會有 Unity Logo & Loading。目前此專案修改 Unity Logo 的部分。

需要更詳細的內容可以參考官方文件（[Unity Document][doc]）。

## Setting Up Your Template

1. Import [Unitypackage][release]

2. Set up Unity Player Setting 

    Edit -> Project Settings -> Player, On the WebGL tab -> Resolution and Presentation -> **Selcet LogoTemplates**

    ![image_1]

3. Change Your Logo
  
    Logo 規格建議不要太大張。

    Path: root/Assets/WebGLTemplates/LogoTemplate/**logo.png**

    ![image_2]

_____________________________________________________________________

[doc]: https://docs.unity3d.com/Manual/webgl-templates.html
[release]: ./build/release.unitypackage
[image_1]: ./images/logotemplate.jpg
[image_2]: ./images/setinglogo.JPG