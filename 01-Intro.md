### What is Three.js?
- It is a high level javascript library for creating and rendering 3D models in Web browser. It simplifies the 3D graphics creating and rendering without low level WebGL knowledge.

### What is Graphics Processing?
- For rendering 3D models in the computer screen needs to calculate millions of calculation in a real time. Computer needs to know informataion like position, location, every vertex of an object etc.
- For handleing thses heavy stuff ```GPU``` came into picture.

### What is GPU?
- GPU stands for Graphics Processing Unit. It is a special kind of hardware. it can run simple calcutions parallel. It is designed in a way that it can handle 3D rendering. 

```Note``` : Computers needs to calculate millions of calculation to display 3D modal. It take very much effort to cpu. that's why GPU came into picture. GPU is a harware specially designed to calcuate simple calculation to display 3D modal.

### What is WebGL?
- WebGL is a javascipt Api to render 3D graphics in the web browser. WebGL provides language to communiate with GPU and to provide instrction to render 3D graphics.
- WebGL takes a lot effort to learn and use it. Learning curve of WebGL is very high. Now ```Three.js``` came into the picture.

### What is Three.js?
- Three.js is javascipt library which is built on  the top of WebGl. Three.js abstract the complex apis and simplfy it for the developers so that we can more focus on Development instead of learning WebGL.

## Tech to Learn Three.js
- Knowledge
    - JavaScript
    - Basic Math
- Tools
    - Chrome
    - VS Code
    - Blender (To create 3D Modal)

## Structure of a Three.js App
<img src="https://res.cloudinary.com/saurabhbackend/image/upload/v1726143139/Screenshot_from_2024-09-12_17-39-58_mddbax.png">

- ```Scene``` : Scene hold eveything that can be seen by the user.
- ```Camera``` : Camers is what user is going to see at the given point of time.
- ```Renderer``` : It takes an information from the Scene and camera. put together all the info and the generate the image or series of images for the user.  