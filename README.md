### WebGl Demos
Demos created while following [Math DesLauriers's](https://github.com/mattdesl/workshop-webgl-glsl) ***Advanced Creative Coding with WebGl and Shaders*** course on [FrontendMasters](https://frontendmasters.com)

Install the `node_modules`:
```bash
$ yarn add
```
If you don't have `npx` run the commands with `./node_modules/.bin/canvas-sketch`
##### Creating a new file:

```bash
$ npx canvas-sketch <file> --new --template=three
```

##### Rendering a file
```bash
$ npx canvas-sketch <file>
```
Access http://10.0.0.3:9966/ to view the rendering. 
The page will hot reload when changes are saved to the file.
##### Downloading Output
To download, click the rendering within the browser then press `cmd + shift + s`. 

Modify the settings object to change the output dimensions, pixel density, fps and duration.

By default downloads are saved as images.

#####  Video
Install ffmpeg:
```bash 
$ yarn add @ffmpeg-installer/ffmpeg --global
```

Run `canvas-sketch` with a `--stream` flag.
###### MP4:
```bash
$ npx canvas-sketch <file> --stream
```

###### GIF:
```bash
$ npx canvas-sketch <file> --stream=gif
```

