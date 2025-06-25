## Vikit for FAST-LIVO2

Vikit (Vision-Kit) is a lightweight and efficient library providing essential camera models, mathematical utilities, and interpolation functions for the FAST-LIVO2 framework. 

📬 For further assistance or inquiries, please contact Chunran Zheng at zhengcr@connect.hku.hk.

### Supported Camera Models
Vikit supports the following camera models:

- Pinhole + Radtan
- Pinhole + Equidistant **(with OpenCV-based fisheye distortion correction)**
- Pinhole + ATAN
- Pinhole + Polynomial
- Omni + Polynomial

These models accommodate diverse camera configurations and distortion characteristics.

### Project Lineage
This repository is maintained as a downstream fork with the following lineage:
1. Original work: [xuankuzcr/rpg_vikit](https://github.com/xuankuzcr/rpg_vikit) by Chunran Zheng.
2. ROS2-compatible port: [integralrobotics/rpg_vikit](https://github.com/integralrobotics/rpg_vikit).

### Enhancements
The following key improvements have been implemented:
- Integrated OpenCV-based fisheye distortion correction into the equidistant camera model (`vikit_common` module).

### Acknowledgments
Special recognition to:
- [UZH-RPG group](https://rpg.ifi.uzh.ch/) for foundational [rpg_vikit](https://github.com/uzh-rpg/rpg_vikit) research.
- [Chunran Zheng](https://github.com/xuankuzcr/rpg_vikit) for developing the ROS1-compatible version [xuankuzcr/rpg_vikit](https://github.com/xuankuzcr/rpg_vikit) specifically adapted for FAST-LIVO2.
- [integralrobotics](https://github.com/integralrobotics) for porting Chunran Zheng's version to ROS2 in their [rpg_vikit implementation](https://github.com/integralrobotics/rpg_vikit).