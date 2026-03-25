# Lane Detection and Lane-Keeping Demo

## Overview
This project explores a computer-vision-based approach to lane detection and basic lane-keeping for autonomous driving in simulation using Python and OpenCV. The goal is to detect lane boundaries from road images or video frames, estimate the vehicle’s position relative to the lane centre, and generate a simple steering guidance output.

Lane detection is a core perception task in autonomous systems because it links camera input directly to navigation and control. Before a vehicle can plan safe movement, it must first understand the structure of the road. This project focuses on that perception layer by building a pipeline that extracts lane information and converts it into useful directional guidance.

The system is being developed around a standard classical computer vision pipeline, including grayscale conversion, Gaussian blurring, edge detection, region-of-interest masking, and line detection. As development progresses, the project will be extended to support lane centre estimation, steering suggestions, and testing across multiple road conditions and video inputs.

This repository forms part of a broader robotics and AI portfolio focused on perception, planning, and intelligent systems. It is intended to strengthen practical skills in Python, OpenCV, and robotics-oriented problem solving while building experience in areas such as computer vision, sensing, and autonomous navigation.

## Objectives
- Detect lane boundaries from road images and video
- Visualise detected lanes on the original frame
- Estimate lane centre position
- Generate a basic steering guidance output
- Develop stronger practical experience in perception for autonomous systems

## Skills Demonstrated
- Python programming
- OpenCV-based computer vision
- Image preprocessing and edge detection
- Perception for autonomous systems
- Technical project structuring and documentation

## Tech Stack
- Python
- OpenCV
- NumPy
- Matplotlib
- Git / GitHub

## Repository Structure
- `src/` - main project source files
- `sample_data/` - test images and videos
- `media/` - screenshots and demo outputs
- `results/` - processed results
- `docs/` - notes and supporting documentation

## Current Status
Prototype / early implementation

Completed:
- Repository setup
- Initial project structure
- Requirements and roadmap
- Starter source files

In progress:
- Image preprocessing pipeline
- Lane boundary detection
- Demo generation

Planned:
- Lane centre estimation
- Steering guidance output
- Video support
- Improved evaluation and documentation

## Planned Workflow
1. Load road image or video frame
2. Convert image to grayscale
3. Apply Gaussian blur
4. Detect edges using Canny edge detection
5. Apply region-of-interest masking
6. Detect lane lines using Hough transform
7. Overlay lane boundaries on the original frame
8. Estimate lane centre and steering guidance

## How to Run
Instructions will be added as implementation progresses.

## Results / Demo
Demo images, processed outputs, and videos will be added during development.

## Limitations
This is currently an early-stage prototype and does not yet handle all lighting conditions, weather conditions, or complex road layouts.

## Next Steps
- Build the first working lane detection pipeline
- Add support for road video input
- Estimate lane offset from centre
- Add simple lane-keeping logic
- Extend testing within a simulation environment
