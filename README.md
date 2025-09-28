# 🏠 ZeroScene: A Zero-Shot Framework for 3D Scene Generation from a Single Image and Controllable Texture Editing

![teaser](https://cdn.jsdelivr.net/gh/xdlbw/Home-of-pictures@master/D:%5CPicGo%5CImage202509281146960.jpg)

> we propose a novel system **ZeroScene**, which leverages the prior knowledge of large vision models to accomplish both single image-to-3D scene reconstruction and texture editing in a zero-shot manner. ZeroScene extracts object-level 2D segmentation and depth information from input images to infer spatial relationships within the scene. It then jointly optimizes 3D and 2D projection losses of the point cloud to update object poses for precise scene alignment, ultimately constructing a coherent and complete 3D scene that encompasses both foreground and background. Moreover, ZeroScene supports texture editing of objects in the scene. By imposing constraints on the diffusion model and introducing a mask-guided progressive image generation strategy, we effectively maintain texture consistency across multiple viewpoints and further enhance the realism of rendered results through Physically Based Rendering (PBR) material estimation.

