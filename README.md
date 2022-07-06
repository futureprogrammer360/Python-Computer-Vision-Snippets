# 📸 Python Computer Vision Snippets

[![Downloads](https://img.shields.io/packagecontrol/dt/Python%20Computer%20Vision%20Snippets)](https://packagecontrol.io/packages/Python%20Computer%20Vision%20Snippets)
[![Tag](https://img.shields.io/github/v/tag/futureprogrammer360/Python-Computer-Vision-Snippets?sort=semver)](https://github.com/futureprogrammer360/Python-Computer-Vision-Snippets/tags)
[![Repo size](https://img.shields.io/github/repo-size/futureprogrammer360/Python-Computer-Vision-Snippets)](https://github.com/futureprogrammer360/Python-Computer-Vision-Snippets)
[![License](https://img.shields.io/github/license/futureprogrammer360/Python-Computer-Vision-Snippets?style=flat-square)](https://github.com/futureprogrammer360/Python-Computer-Vision-Snippets/blob/master/LICENSE)

[Python Computer Vision Snippets](https://github.com/futureprogrammer360/Python-Computer-Vision-Snippets) is a collection of [Sublime Text](https://www.sublimetext.com/) snippets for computer vision and image processing in Python.

## 💻 Installation

The easiest way to install Python Computer Vision Snippets is through [Package Control](https://packagecontrol.io/packages/Python%20Computer%20Vision%20Snippets). After it is enabled inside Sublime Text, open the command palette and find **Package Control: Install Package** and press `ENTER`. Then, find **Python Computer Vision Snippets** in the list. Press `ENTER` again, and this package is installed!

## 📈 Snippets

* [Imports](#imports)
* [OpenCV](#opencv)
* [Pillow](#pillow)

### Imports

Import snippets start with `i` followed by the package/module's import alias.

| Trigger  | Description             |
|----------|-------------------------|
| `icv2`   | `import cv2`            |
| `iImage` | `from PIL import Image` |

### OpenCV

| Trigger             | Description             |
|---------------------|-------------------------|
| `circle`            | `cv2.circle`            |
| `cvtColor`          | `cv2.cvtColor`          |
| `destroyAllWindows` | `cv2.destroyAllWindows` |
| `imread`            | `cv2.imread`            |
| `imshow`            | `cv2.imshow`            |
| `imwrite`           | `cv2.imwrite`           |
| `line`              | `cv2.line`              |
| `putText`           | `cv2.putText`           |
| `rectangle`         | `cv2.rectangle`         |
| `resize`            | `cv2.resize`            |
| `rotate`            | `cv2.rotate`            |
| `VideoCapture`      | `cv2.VideoCapture`      |
| `waitKey`           | `cv2.waitKey`           |

### Pillow

| Trigger     | Description           |
|-------------|-----------------------|
| `convert`   | `Image.convert`       |
| `crop`      | `Image.crop`          |
| `fromarray` | `PIL.Image.fromarray` |
| `open`      | `PIL.Image.open`      |
| `resize`    | `Image.resize`        |
| `rotate`    | `Image.rotate`        |
| `save`      | `Image.save`          |

The snippet files are in the [`snippets`](https://github.com/futureprogrammer360/Python-Computer-Vision-Snippets/tree/master/snippets) folder of [this GitHub repository](https://github.com/futureprogrammer360/Python-Computer-Vision-Snippets).
