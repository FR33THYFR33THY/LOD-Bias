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

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/13f6d883-f9c5-4eb9-a720-617ea5c68cfa)

- POSITIVE<br>
  Textures will look worse, potential performance gain<br>

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/936d6463-94f2-4079-87d0-9630baf41a1a)

- CLAY<br>
  Visually less distracting, potential performance gain<br>

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/1194172b-8504-42c5-8f25-dc5c0d9d1822)

- NEGATIVE<br>
  Textures will look better, potential performance loss<br>

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/8eda252d-dc8a-4552-b442-6db0063163a8)

## Ban?
This involves merely adjusting a graphics setting. If game developers disapprove, it's their responsibility to address it.<br>
For instance, Rainbow Six Siege allows you to launch the game but displays a warning and restricts online play.<br> 
Conversely, Counter-Strike 2 completely prevents you from launching the game.

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/b1ff017f-330c-406e-9d26-d7398e9ef660)
![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/5a014072-e3b0-4150-a6f4-b6cad4506b5b)

## Note
For some game engines, you'll need to manually apply the LOD settings in inspector using the game profile.<br>

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/9ff0e102-4a40-41d5-98d6-62e062691364)

Additionally, you might need to enable the read-only option to prevent the game engine from overwriting the setting.

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/0332a91e-bc8f-4402-89ec-042c11d623fa)

Some DX12 games may require the shader cache files to be deleted before LOD optimization is applied. 

## Comparisons
![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/230ac561-e2ea-42ca-b6da-5472a9d3d822)

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/235d9e5e-4968-4c42-ba75-9dab9eccc456)


## Benchmark
7800x3d 4090<br>
OBS NDI game capture<br>

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/875f5cb7-3e18-424f-9b9b-ea0bd69a3260)

It's unusual that there appears to be no scaling between these settings in multiplayer titles.<br>
I observed a similar pattern with XDefiant and Rainbow Six Siege.<br> 
However, I opted to use Modern Warfare 2 as it's a more consistent benchmark.<br>

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/0f65f8b6-a9a6-41f3-a604-5612d1b9ab46)

![image](https://github.com/fr33thytweaks/LOD-Bias/assets/168888348/04e917ff-f746-44ed-bddf-5e6775d7d70b)


## Video
[Video](<https://youtu.be/o7O-DODzD5g>)

[![Video](https://img.youtube.com/vi/o7O-DODzD5g/maxresdefault.jpg)]([https://www.youtube.com/watch?v=o7O-DODzD5g](https://youtu.be/o7O-DODzD5g))
