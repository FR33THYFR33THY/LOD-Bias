# LOD-Bias

## Description
LOD Bias (Level of Detail Bias) is a graphics setting that adjusts how detailed textures appear at different distances.

## Requirements
- Nvidia GPU
- Direct X or Open GL games<br>
  Contact me if anyone finds a way for Vulkan

## Alternative For AMD GPU'S
- In registry<br>
Contact me if anyone finds a way

## Why
- DEFAULT<br>
  Depends on driver implementation<br>

![1](https://github.com/user-attachments/assets/774d97ad-926b-4bab-87fd-49ecfae5d1ab)


- POSITIVE<br>
  Textures will look worse, potential performance gain<br>

![2](https://github.com/user-attachments/assets/683b6678-9efb-47ba-9941-a1c0c4fa012e)


- CLAY<br>
  Visually less distracting, potential performance gain<br>

![3](https://github.com/user-attachments/assets/7061faec-3946-42b9-a9ea-a799db182e59)


- NEGATIVE<br>
  Textures will look better, potential performance loss<br>

![4](https://github.com/user-attachments/assets/4b47f6b2-5b81-40ae-ba30-a48a9a4b764b)


## Ban?
This involves merely adjusting a graphics setting. If game developers disapprove, it's their responsibility to address it.<br>
For instance, Rainbow Six Siege allows you to launch the game but displays a warning and restricts online play.<br> 
Conversely, Counter-Strike 2 completely prevents you from launching the game.

![5](https://github.com/user-attachments/assets/3c4df444-0c51-4bec-8e26-de437bc4104e)
![6](https://github.com/user-attachments/assets/3ff97b3c-b19e-4429-be4c-1b9f061e8d35)

## Note
For some game engines, you'll need to manually apply the LOD settings in inspector using the game profile.<br>

![7](https://github.com/user-attachments/assets/21a4ada0-2dda-49a1-be8c-eeaa29f58252)


Additionally, you might need to enable the read-only option to prevent the game engine from overwriting the setting.

![8](https://github.com/user-attachments/assets/e47e85dc-0130-4067-a2f1-b7be7d576354)


Some DX12 games may require the shader cache files to be deleted before LOD optimization is applied. 

## Comparisons
![9](https://github.com/user-attachments/assets/10c605c9-a5ff-4abf-858a-c1cb2d37afdc)


![10](https://github.com/user-attachments/assets/7b7b78bf-0204-425e-987b-7fde4ee2abc9)



## Benchmark
7800x3d 4090<br>
OBS NDI game capture<br>

![11](https://github.com/user-attachments/assets/d1e5e6f6-6dfe-4257-aabb-19eca4c357e1)


It's unusual that there appears to be no scaling between these settings in multiplayer titles.<br>
I observed a similar pattern with XDefiant and Rainbow Six Siege.<br> 
However, I opted to use Modern Warfare 2 as it's a more consistent benchmark.<br>

![12](https://github.com/user-attachments/assets/15c63735-c7d1-43de-9f57-72f30ac82824)

![13](https://github.com/user-attachments/assets/d900ef11-5223-44c4-9998-567f40c7e680)


## Video
[Video](<https://youtu.be/o7O-DODzD5g>)

[![Video](https://img.youtube.com/vi/o7O-DODzD5g/maxresdefault.jpg)]([https://www.youtube.com/watch?v=o7O-DODzD5g](https://youtu.be/o7O-DODzD5g))
