# Tex Batch Adder

Load multiple images to add and configure as textures on the active object's active material.

## Installation

To get it working in your local Blender:
- save the contents of this repo in your Blender's `scripts/addon_contrib`
- run Blender
- open `User Preferences`
- select `Add-ons` and limit the supported level to `Testing`
- find and enable Tex Batch Adder

This addon was developed locally as a script run within Blender before it was packaged as an addon and stored in this repo. The original project is still part of my [Blender VSE Customizations](https://github.com/Botmasher/blender-vse-customizations).

## Structure

The code of Tex Batch Adder is divided between the UI (panel and operator) and the logic (`ImgTexturizer`). This is reflected in the file structure:
- `ui.py` for panel and operator
- `img_texturizer.py` for logic

The addon is configured and its classes registered through `__init__.py`.
