# Project of the Automatic Pet Feeder

## Overview
This repository contains the design files, documentation, and code for an automatic pet feeder developed by a team from the Faculty of Mechanical Engineering and Robotics at AGH. The project features a smart, app-controlled feeder with video monitoring, sensor-based food and water level detection, and customizable feeding schedules, prioritizing sustainability with recyclable materials.

## Files
### 3D Models and Drawings
- `BACK_plate.f3d`: Back plate component.
- `Bone_back_plate(autocad).pdf`: AutoCAD drawing of the back plate.
- `Bone_container_2(autocad).pdf`: AutoCAD drawing of the bone container.
- `Bone_shaped_container(autocad).pdf`: AutoCAD drawing of the bone-shaped container.
- `Bonefront_plateContainer(autocad).pdf`: AutoCAD drawing of the front plate and container.
- `Container(autocad).pdf`: AutoCAD drawing of the container.
- `Container_Drawing_v1.pdf`: Container drawing version 1.
- `Container.f3d`: Container component.
- `FOOD_SLEEVE.f3d`: Food sleeve component.
- `Front_plate.f3d`: Front plate component.
- `PetFeederAssembly.pdf`: Assembly drawing of the pet feeder.
- `PetFeederExplosion.pdf`: Exploded view of the pet feeder.
- `WATER_SLEEVE.f3d`: Water sleeve component.
- `assemblyPetfeeder_v6.png`: Assembly image version 6.
- `assemblyPetfeeder_v7.png`: Assembly image version 7.
- `assemblyPetfeeder_v8.f3z`: Assembly file version 8.
- `bone_shapeside_part-1.f3d`: Bone shape side part 1.
- `bone_shapeside_part-2.f3d`: Bone shape side part 2.
- `circuit(1).png`: Circuit diagram image 1.
- `circuit_image(1).png`: Circuit diagram image 2.
- `feedscrew_v1.f3d`: Feed screw component version 1.
- `screw(autocad).pdf`: AutoCAD drawing of the screw.

### Documentation
- `Project of the Automatic Pet Feeder.pdf`: Detailed report including project goals, morphological analysis, core design, system overview, components, software, demonstration, and future improvements.

### Code
- `README.md`: Initial commit of this README file.

## Project Details
- **Objective**: Simplify pet care routines with remote monitoring and control, using sustainable materials for small to medium-sized pets.
- **Features**: App-controlled food and water dispensing, live video monitoring, ultrasonic and water level sensors, customizable schedules.
- **Components**: ESP32-S3, Seeed Xiao ESP32-S3 Sense with OV2640 camera, 28BYJ-48 stepper motor, 5-12V DC water pump, HC-SR04 ultrasonic sensor, Grove water sensor, 5V 4A power supply.
- **Materials**: Plywood, biodegradable 3D filament, plexiglass.
- **Power**: 5V 4A power supply with an average current draw of ~2.565A.

## Assembly Instructions
Refer to `PetFeederAssembly.pdf` and `Project of the Automatic Pet Feeder.pdf` for step-by-step assembly instructions, including:
- Laser-cut plywood front and back plates.
- 3D-printed side cylindrical holders and container with plexiglass windows.
- Assembly using screwed and glued joints.

## Software
- **Platform**: Arduino Cloud for remote control, real-time data visualization, and scheduling.
- **Features**: Live sensor data (food/water levels), customizable schedules, manual and scheduled dispensing, camera feed via HTML site.

## Demonstration
- **Videos**: Check the prototype presentation and assembly 3D model videos at [https://drive.google.com/drive/folders/1KkYPMTIqAwl6N05ESCOF5NJ43y_c4hTv?usp=drive_link](https://drive.google.com/drive/folders/1KkYPMTIqAwl6N05ESCOF5NJ43y_c4hTv?usp=drive_link).

## Contributors
- Ivan Rybalko
- Michal Nowicki
- KyiMin Thant
