## Vikit for FAST-LIVO2

Vikit (Vision-Kit) is a lightweight and efficient library designed to provide essential camera models, mathematical utilities, and interpolation functions required for the FAST-LIVO2 framework. 

📬 For further assistance or inquiries, please feel free to contact Chunran Zheng at zhengcr@connect.hku.hk.

### Supported Camera Models
Vikit offers support for a diverse range of camera models, including:

- Pinhole + Radtan
- Pinhole + Equidistant **(with OpenCV-based fisheye distortion correction)**
- Pinhole + ATAN
- Pinhole + Polynomial
- Omni + Polynomial

These models adapt to various camera configurations and distortion characteristics.

### Project Lineage & Modifications
This repository is a fork of the ROS2-compatible [`rpg_vikit`](https://github.com/integralrobotics/rpg_vikit) (itself derived from the [original work](https://github.com/uzh-rpg/rpg_vikit) by Chunran Zheng). Key enhancements include:
- **Added OpenCV-based fisheye distortion correction** to the equidistant camera model in `vikit_common`.

### Acknowledgments
Special thanks to:
- The [rpg_vikit](https://github.com/uzh-rpg/rpg_vikit) from [UZH-RPG group](https://rpg.ifi.uzh.ch/) for foundational work
- [integralrobotics](https://github.com/integralrobotics) for the ROS2-compatible port
