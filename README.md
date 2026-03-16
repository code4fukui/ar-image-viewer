# AR Image Viewer

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple AR viewer to display 2D images in a 3D space.

## Demo
https://code4fukui.github.io/ar-image-viewer/

## Features
- Displays 2D images in 3D space
- Supports customizable size, position, and orientation of the image
- Utilizes A-Frame, a web framework for building virtual reality (VR) experiences

## Usage
The AR image viewer can be customized using the following parameters in the URL:

- `src`: URL of the image to be displayed
- `w`: Width of the image in meters
- `h`: Height of the image in meters
- `x`: X-coordinate of the center position in meters
- `y`: Y-coordinate of the center position in meters
- `z`: Z-coordinate of the center position in meters

For example, to display an image with a width of 5.4 meters, a height of 1.4 meters, and positioned at (0, 1.5, -1.8), the URL would be:

```
https://code4fukui.github.io/ar-image-viewer/?src=./img/sabae-candidates-2023.jpg&w=5.4&h=1.4&x=0&y=1.5&z=-1.8
```

## License
MIT License — see [LICENSE](LICENSE).