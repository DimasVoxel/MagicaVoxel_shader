# Moisture Magica voxel Shader
Repository for magica voxel shader.

## Installation

Install the shader by copying the file `moisture.txt` into the `shader` directory of your MagicaVoxel installation. 

## Usage

After installing the shader you should see them in the shader menu.

Use them according to the description below and try mixing them up for better results. You can ask me anything on [twitter](https://twitter.com/EKremlinois).

### Moisture Shader

Inspired by [shader by patStar](https://github.com/patStar) (thanks!).
This shader lets you create the effect of moisture on your voxel buildings.

![...](shader2.png?raw=true "Title")

There are 6 parameters:

| Parameter | Range | Description |
| ------ | ------ | ------ |
| Modo | 0 to 1 |Moisture will spread downwards (0) or upwards (1) .|
| Avance | 0 to 1 |How quickly moisture will spread in each execution.  |
| Random Seed | 0 to 1000000| Using the shader on the same scene will always yield the exact same result as long as you don't change this value. Play with this to yield different patterns on the same scene. |
| Additional Colors | -255 to 255 | You may paint the different layers of your plant in different colors. The base Color will be the selected color but you can define a range of colors following or preceding the selected color here. |
| Avance Colors | 0 to 1 | How quickly other colors will appear in your moisture. |
| Unif Colors | 0 to 1 | Larger values give you more additional colored moisture, lower values will keep colors more unified. |

### Tips

![...](shader3.png?raw=true "Title")
