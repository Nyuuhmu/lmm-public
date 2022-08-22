# LevelModifier Modifier
The LevelModifier Modifier is a tool made to view, edit and create LevelModifier (.dat) files for Driftcity. 

## Download

To download, click on any version listed under "Releases" to the right.

## Values

- **Left**: Value at zero points, usually the lowest/start value
- **Right**: Value at max points, usually the highest/end value
- **A, B, C, D**: Values that control the shape of the bezier curve. From 0.0f to 1.0f, think of them as percentages relative to your inputs and the values around it
  - A controls the value near 0%
  - B controls the value near 33%
  - C controls the value near 66%
  - D controls the value near 100%
- **Stop**: Point value at which the curve will stop and stay until the end
- **Step**: Value at which the curve increases after it hits the Stop value

## Notes
Make sure you select the correct Stage for whichever version you're working on. Stages have the following restrictions:

- **Stage 1**: 800/800/800/800 max points
- **Stage 2**: 1000/1000/1000/1000 max points
- **Stage 3**: 1600/1600/2500/1200 max points

## Curve Examples

- 0, 0, 1, 1

![img](https://puu.sh/JhpdJ/ac3e72ed74.png)

- 0, 1, 0, 1

![img](https://puu.sh/Jhpdt/0a5771f4bc.png)

- 0, 1, 1, 1

![img](https://puu.sh/JhpeT/296d8f0c86.png)

- 0, 0.33, 0.66, 1

![img](https://puu.sh/JhpdR/7e7bc9672c.png)

- 0, 0.33, 0.66, 1 (Stop: 600)

![img](https://puu.sh/Jhpg5/5a1e8fc97a.png)

- 0, 0.33, 0.66, 1 (Stop: 600, Step: 0.05)

![img](https://puu.sh/Jhpgh/8474e646f2.png)

- 0, 1, -1, 0

![img](https://puu.sh/Jhpeu/c024903cf4.png)

