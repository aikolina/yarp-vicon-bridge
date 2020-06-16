---
layout: post
title:  "Typical Vicon Workflow"
date:   2020-06-15 14:25:00 +0200
categories: vicon
---

!!! UNDER CONSTRUCTION !!!

1. Run Vicon Nexus 2.X as administrator
2. Check system status (Left Pane)
   - All the cameras of the setup should be available (green arrow!)
3. Tools > System Preparation (Right Pane)
   - Run the calibration procedure
     - Mask Cameras
     - Calibrate Cameras (Active Wand v2)
     - Set Volume Origin (Active Wand v2)
4. Open the Data Management (Bottom Central Pane)
   - Create a database (yellow and blue circles)
   - Create a patient classification (green circle)
   - Create a Patient (yellow circle)
   - Create a Session (gray circle)
5. Create an empty subject (Left Pane)
6. Tools > Subject Preparation (Right Pane)
   - Start subject capture -- subject is STATIC
   - Apply "Reconstruct" pipeline
   - Create a segment (rigid body)
      - Select the origin marker
      - Select the primary axis marker (x-axis)
      - Select the secondary axis marker (y-axis)
      - Select additional markers
      - Click again on "Create" to close the segment creation
7. Resources > Subjects (Left Pane)
   - Change the name and/or color of the markers of the created subject
   - (If desired, create a template for the next session)
8. Go Live (Left Pane)
   - the markers will be named/colored as defined in the previous steps
