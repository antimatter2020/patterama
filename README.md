# AHL→cell death model

    du/dt= D * laplacian(u,h) - decay * u + k * v
    dv/dt = Dc * laplacian(v,h) + grow * v - kc * u * v
# ![image](https://github.com/antimatter2020/patterama/assets/68374440/2f16ab6b-bdff-4a10-baa9-3a1bfc5c70c8)
# ![image](https://github.com/antimatter2020/patterama/assets/68374440/c3006a15-cbd1-41e4-9b87-2feb3275a8cd)
    

Cell diffusion:
$\frac{\partial u}{\partial t} = Du \cdot \Delta u - decay \cdot u + k \cdot v $

AHL diffusion:
$\frac{\partial v}{\partial t} = Dc \cdot \Delta v + grow \cdot v - kc \cdot u \cdot v$
