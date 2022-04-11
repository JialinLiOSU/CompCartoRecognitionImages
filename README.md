# Images for computational cartographic recognition training and testing 

Images in this repo are used to train and test machine learning models for identifying maps and for recognizing geographic regions and projections on the map. These images are stored in different folders that are organized for the three purposes. The folders and images are summarized below. Online maps and images vary significantly in their sizes. For example, in the category of world maps for region recognition, the sizes range from 315x160 to 4096x2906 pixels, and maps for China vary from 283x178 to  2250x1447 pixels. Maps in the syntheticMaps folders are generated using Python. These are supplementary maps for training and testing. Their size ranges are listed below.

- map identification - Images in this folders are used to train the model to identify whether an image is a map.
  - maps - Map images are stored in this folder.
    - onlineMaps - This folder contains maps found from Google images.
    - syntheticMaps - Supplementary map images generated are included here. The sizes of these images range from 385x584 to 960x720 pixels.
  - nonMaps - Images that are not considered to be maps are stored here.
- region recognition - Maps in this folder are used to train and test models to recognize regions on the map.
  - China maps - Maps labelled as mainland China are stored in this folder.
    - onlineMaps - Maps collected from Google images are here.
    - syntheticMaps - Supplementary maps generated using Python are stored here. Their sizes range from 774x371 to 883x611 pixels.
  - Other maps - Maps labelled as other regions are stored here.
    - onlineMaps - Maps collected from Google images are here.
    - syntheticMaps - Supplementary maps generated using Python are stored here. Their sizes range from 107x101 to 252x264 pixels.
  - South Korea maps - Maps labelled as South Korea are here.
    - onlineMaps - Maps collected from Google images are here.
    - syntheticMaps - Supplementary maps generated using Python are stored here. Their sizes range from 458x584 to 704x615 pixels.
  - US maps - Maps labelled as United States are here.
    - onlineMaps - Maps collected from online sources are here.
    - syntheticMaps - Supplementary maps generated using Python are here. Their sizes range from 774x297 to 1009x453 pixels.
  - world maps - Maps labelled as world are here.
    - onlineMaps - Maps collected from online sources are here.
    - syntheticMaps - Supplementary maps generated using Python are here. All images have the same size of 960x720 pixels.
- projection recognition - This folder stores images used to train and test model to recognize the projection on a map.
  - EqualArea_Projection_Maps - Map images labelled as the [cylindrical equal area projection](https://en.wikipedia.org/wiki/Cylindrical_equal-area_projection) (CEA) are stored in this folder.
    - onlineMaps - Maps on CEA found using Google images are stored here.
    - syntheticMaps - Supplementary synthetic maps on CEA are stored here. Their sizes are 960x720 pixels.
  - Equirectangular_Projection_Maps - Map images labelled as the [equirectangular projection](https://en.wikipedia.org/wiki/Equirectangular_projection) are stored here.
    - onlineMaps - Maps on equirectangular projection found using Google images are stored here.
    - syntheticMaps - Supplementary synthetic maps on equirectangular projection are stored here. Their sizes are 960x720 pixels.
  - Mercator_Projection_Maps - Map images labelled as the [Mercator projection](https://en.wikipedia.org/wiki/Mercator_projection) are stored here.
    - onlineMaps - Maps on the Mercator projection found using Google images are stored here.
    - syntheticMaps - Supplementary synthetic maps on the Mercator projection are stored here. Their sizes are 960x720 pixels.
  - Robinson_Projection_Maps - Map images labelled as the [Robinson projection](https://en.wikipedia.org/wiki/Robinson_projection) are stored in this folder.
    - onlineMaps - Maps on the Robinson projection found using Google images are stored here.
    - syntheticMaps - Supplementary synthetic maps on the Robinson projection are stored here. Their sizes are 1200x750 pixels.
  - Other_Projections_Maps - Maps labelled as in other projections (including Eckert IV, Hammer, Miller cylindrical, Mollweide, and sinusoidal) are stored in this folder.
    - onlineMaps - Maps on the other projections found using Google images are stored here.
    - syntheticMaps - Supplementary synthetic maps on other projections are stored here. Their sizes are 960x720 pixels.


