# dot_density_map_bosnia
This R script creates a dot density map of Bosnia and Herzegovina, where each dot represents a fixed number of people, distributed across administrative regions. The approach offers an intuitive and visually engaging way to represent population distribution without relying on choropleth shading.

-Overview:
Using spatial population estimates at the administrative level, the script generates randomized points (dots) within polygons, where the number of dots is proportional to the total population of each unit. These dots are then overlaid on a minimalistic basemap for a clean, informative visualization.

-Key Elements:
Generation of randomized spatial points using st_sample()

Use of geom_sf() for administrative boundaries and point plotting

Coordinate transformation and reprojection for proper cartographic display

Styled using ggplot2 with customized color palette for both basemap and dot layer

-Tools & Packages:
Built using sf, ggplot2, rnaturalearth, dplyr, and tidyr.

-Applications:
Suitable for demographic visualization, cartographic storytelling, and public policy communication, especially where relative population size and distribution need to be quickly grasped.

![BIH_dot_density](https://github.com/user-attachments/assets/f3f7d909-d610-494f-acd7-97fbf135ec62)

