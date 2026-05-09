# DJI Mission Tools

![Python](https://img.shields.io/badge/Python-3.13-green.svg)
![PyQt5](https://img.shields.io/badge/PyQT5-green.svg)
![ADB](https://img.shields.io/badge/ADB-supported-green.svg)
![MTP](https://img.shields.io/badge/MTP-supported-green.svg)
![iOS](https://img.shields.io/badge/iOS-supported-green.svg)
![Windows](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
![macOS](https://img.shields.io/badge/platform-MacOS-lightgrey.svg)
![MIT](https://img.shields.io/badge/license-MIT-green.svg)

## Professional DJI Mission Planning & Injection Tools

This GitHub project contains two complementary applications for professional DJI waypoint mission workflows:

- **map-creator** → Advanced mission planning and KMZ generation
- **DJIKMZInjector** → Direct mission management and synchronization for DJI devices

Together they provide a fully local, professional workflow for:
- DJI Fly waypoint missions
- Photogrammetry planning
- Terrain following
- Vertical inspection missions
- Gaussian Splatting workflows
- DJI RC / RC2 mission management
- iOS mission synchronization on macOS

---

# map-creator

![map-creator](https://github.com/hdrpano/map-creator/blob/main/images/map-creator.png))

## Advanced DJI Mission Planning

map-creator is a desktop application for planning and visualizing drone waypoint missions directly on an interactive map.

### Features

- Polygon and circular mission planning
- Waypoint grid generation
- Terrain following support
- Vertical and helix missions
- Cross grid support
- Interactive mission preview
- DJI Fly compatible KMZ export
- Import of KMZ, KML and CSV missions
- Blender / Gaussian Splatting workflows
- Fully local processing
- Windows and macOS support

### Why map-creator?

Unlike cloud-based planning tools, map-creator works completely locally and focuses on:
- Fast mission iteration
- Advanced geometry generation
- Professional photogrammetry workflows
- Direct DJI Fly compatibility
- No subscription required

### Gaussian Splatting Workflow

map-creator can be used to generate optimized flight paths for:
- RealityScan
- COLMAP
- Gaussian Splatting pipelines
- 3D reconstruction workflows

### Watch the videos

#### Mission Planning

[![Watch the video](https://img.youtube.com/vi/LUwJ74JaNIQ/maxresdefault.jpg)](https://youtu.be/LUwJ74JaNIQ)

#### Gaussian Splatting

[![Watch the video](https://img.youtube.com/vi/xbpYkrBMoUU/maxresdefault.jpg)](https://youtu.be/xbpYkrBMoUU)

### Releases

https://github.com/hdrpano/map-creator/releases

Website:
https://map-creator.com

---

# DJIKMZInjector

![DJIKMZInjector](img/MacOS.png)

## Direct DJI Mission Management

DJIKMZInjector is a lightweight desktop tool to manage DJI waypoint missions directly on DJI RC controllers, Android devices and iOS devices.

### Main Features

- Replace DJI waypoint missions by UUID
- Native iOS mission creation support
- Automatic backend detection
- Automatic USB connection handling
- Mission preview synchronization
- Safe DJI-compatible workflows
- macOS and Windows support
- No cloud dependency

### iOS Integration (macOS)

The native iOS backend allows:
- Direct mission creation
- Automatic synchronization
- Full mission database access
- Mission preview handling
- Automatic device connection at startup

No jailbreak or developer mode is required.

### MTP Support

MTP support is optimized for:
- DJI RC 2
- Android devices
- DJI Fly mission synchronization

Special handling was implemented for macOS USB/MTP stability.

### Watch the video

[![Watch the video](https://img.youtube.com/vi/LUwJ74JaNIQ/maxresdefault.jpg)](https://youtu.be/LUwJ74JaNIQ)

### Releases

https://github.com/hdrpano/DJI-KMZ-Injector/releases

---

# Typical Workflow

1. Create missions in **map-creator**
2. Export DJI-compatible KMZ missions
3. Synchronize directly using **DJIKMZInjector**
4. Fly missions using DJI Fly / DJI RC devices

This workflow enables:
- Fully local mission planning
- Fast iteration cycles
- Professional photogrammetry pipelines
- Reliable DJI mission synchronization

---

# Platform Support

| Platform | map-creator | DJIKMZInjector |
|---|---|---|
| Windows | ✅ | ✅ |
| macOS | ✅ | ✅ |
| iOS support | — | ✅ |
| Android support | ✅ | ✅ |
| DJI RC2 support | ✅ | ✅ |

---

# Philosophy

These tools were developed with a strong focus on:
- Reliability
- Local workflows
- Transparency
- Professional mission planning
- Stable DJI integration
- No subscription model
- Fast iteration for real-world drone operations

---

# Contact

Website:
https://map-creator.com

GitHub:
https://github.com/hdrpano

---

# License

Free for personal and professional use.

Use at your own risk.
