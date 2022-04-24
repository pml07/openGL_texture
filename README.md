# OpenGL_hw1
###### tags: `openGL`


### Environment & Libraries
---
* OS：Windows 10
* visual studio 2019
* [cmake](https://cmake.org/download/) 3.23
* openGL 3.3
* [glfw](https://www.glfw.org/) 3.3.6
* glad
* glm 0.9.9.8
* imgui 1.77
* stb_image 2.25
* tinyobjloader 0.9.20


### 編譯過程
---
#### glfw
* 將glfw解壓縮後新增`build`資料夾
![](https://i.imgur.com/DRtOFIC.png)
* 設置cmake路徑
* Configure & Generate
![](https://i.imgur.com/iftHLs3.png)
* 用visual studio執行`GLFW.sln`
![](https://i.imgur.com/WStG8uw.png)
* 專案設為`x64`
* ==INSTALL右鍵 建置==


#### sample code
* 新增`build`資料夾
![](https://i.imgur.com/9FaweCv.png)
* 設置cmake路徑
* Configure & Generate
    * ==其中，glfw3_DIR & glm_DIR 的路徑須注意==
![](https://i.imgur.com/ezso3XA.png)
* 專案設為`Release`及`x64`
* ==Homework01 右鍵INSTALL==
* build完成後會產生4個檔案
![](https://i.imgur.com/Cteu79h.png)
* 開啟cmd cd至此層資料夾
* 執行`./Homework01 "resources/model/Utah_teapot_(solid)_texture.obj" "resources/texture/uv.png" "Shader/BasicVertexShader.vs.glsl" "Shader/BasicFragmentShader.fs.glsl"`
* 即可run the sample code

> 詳細過程可參考投影片
