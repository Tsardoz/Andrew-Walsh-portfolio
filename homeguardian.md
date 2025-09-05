# HomeGuardian: Elderly Fall Detection System

## Project Overview
At HomeGuardian, I led the technical development of an AI-powered fall detection system designed to identify falls in elderly individuals using computer vision technology deployed on edge devices (eg. Raspberry Pi or other SBC with an advanced neural processing unit). This project addressed a critical healthcare challenge, as falls are the leading cause of hospital admissions for people over 65.

## Technical Challenges

### Initial State
When I joined as the sole software engineer:
- The existing Python codebase was non-functional
- The system used basic YOLO object detection with a rudimentary aspect ratio method for fall detection
- Accuracy was approximately 80%, far below the 99.9% reliability required for a life-safety application
- False positives and false negatives were common occurrences
- The system struggled with partial visibility and normal activities like bending

### Technical Approach

#### Computer Vision Pipeline
- Redesigned the computer vision processing pipeline on Raspberry Pi
- Implemented more sophisticated fall detection algorithms beyond simple aspect ratio detection
- Optimized Python code for performance on resource-constrained edge devices
- Developed strategies for handling edge cases like partial visibility and non-fall activities

#### Model Training and Optimization
- Improved the training methodology for more accurate fall detection
- Developed techniques to distinguish between falls and similar movements (bending, lying down)
- Optimized models to run efficiently on Raspberry Pi hardware (and more advanced SBCs using a neural processing unit NPU)
- Implemented systematic testing processes to validate detection accuracy

## Results
- Significantly improved detection accuracy over the original implementation
- Created a more robust system capable of handling a wider range of scenarios
- Established technical foundation for a viable commercial product
- Identified remaining technical limitations that would need to be addressed for commercial viability

## Key Learnings
- Edge-based computer vision systems face significant constraints in processing power vs. accuracy
- Achieving medical-grade reliability (99.9%) requires more sophisticated approaches than edge-only processing
- Fall detection is an extremely challenging computer vision problem due to the variety of scenarios and environments
- This experience directly informed my later work at Safest Tech, where I developed a hybrid edge-cloud approach

## Technical Skills Applied
- Computer vision (OpenCV, YOLO and other object detection systems)
- Python optimization for edge devices
- Machine learning model training and deployment
- Edge computing
- Embedded systems development
