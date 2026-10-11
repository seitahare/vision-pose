# vision-pose

> Camera calibration and visual pose-estimation experiments for robotics and XR.

**Status:** Planned — roadmap only. No implementation has been claimed.

## Goal

Estimate where a visual marker is relative to a camera.

## Available / suggested hardware

Built-in laptop camera or XIAO ESP32S3 Sense camera; printed AprilTag marker.

## MVP (first demonstrable result)

1. Capture camera frames and detect a known AprilTag using an existing library.
2. Calibrate camera intrinsics and set the marker’s physical size.
3. Estimate and visualize the marker pose (position and orientation) relative to the camera.

## Next milestones

- [ ] Plot measurement noise and latency at various distances.
- [ ] Combine visual orientation with pose-lab IMU data.
- [ ] Explore visual odometry and eventually SLAM in a separate later phase.

## Skills to learn

- Pinhole camera model
- Intrinsic calibration and lens distortion
- Perspective-n-Point pose estimation
- Frames of reference and sensor fusion

## Connections to other repositories

- **pose-lab:** compare and fuse inertial vs. camera estimates.
- **spatial-ui:** add camera-relative anchors for spatial objects.
- **teleop-lab:** visually identify robot or target locations.

## Important scope note

Marker-relative 6DoF pose is not the same as markerless 6DoF SLAM; start with a known tag and camera calibration.

## Definition of done for MVP

- [ ] A reproducible demo or data output is committed.
- [ ] README explains how to run it.
- [ ] At least one validation result, plot, photo or screenshot is included.

## License

License to be selected before redistributing code.
