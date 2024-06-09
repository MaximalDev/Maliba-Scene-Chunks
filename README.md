# Maliba-Scene-Chunks
Maliba Scene Chunks is a powerful and lightweight Unity package that streamlines the process of loading and unloading scenes dynamically based on contextual triggers. By utilizing load zones, this package ensures an optimized and seamless experience, allowing for unnoticeable transitions between scenes. (Inspired by Bonelab's patch 4 update)

# What's the benefit in using this over enabling and disabling objects in one scene?
Scene Chunks allow for significant resource optimization compared to enabling and disabling objects within a single scene. While disabled objects still consume memory, an unloaded scene doesn't allocate resources. This difference becomes increasingly pronounced in large-scale or complex environments, where Scene Chunks can substantially reduce the memory footprint and improve overall performance by only loading the necessary scenes for the current gameplay area.
