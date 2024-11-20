# Portfolio 

### Education
Robotics and Mechatronics Engineering, PhD (2022-present), DGIST, South Korea <br />
Engineering Technology, MS (2021), KSU, USA <br />
Robotics Engineering, MS(2019), DGIST, South Korea <br />
Mechanical Engineering, BS, MIST, Bangladesh(2016)

### Skills
SolidWorks, MATLAB, MATLAB Robotics Toolbox, Simulink, ANSYS MAXWELL, ANSYS Mechanical, Unity 3D, Blender, Arduino, Python, C, C#, C++, OpenCV, ROS2 (Robot Operating System), Gazebo, FANUC ROBOGUIDE, Altium Designer, Proteus, LaTex, StarUML

### Projects
**1. Virtual Reality-Enabled Intuitive Magnetic Manipulation of Microrobots and Nanoparticles**
   Micro and nano sized robots have huge potential in medical robotics as they can enable accurate and precise drug delivery to the target sites. However, controlling these tiny robots in complex vasculatures     is an extrememly challenging tasks. In this project I implement for the first time in the world, a VR controlled intuitive method of navigating microrobots inside complex geometries that is superior to         conventional open loop and closed loop control.
- Developed micro and nano scale robot steering scheme with Virtual Reality (VR) inside small and complex geometries
  - Designed and coded VR environments with Unity 3D and C#
  - Coded the Oculus Rift S touch controllers for robot steering
- Performed camera calibration and developed code for accurate 3D position tracking of microrobots
  - Obtained camera parameters through MATLAB camera calibraiton toolbox
  - Utilized OpenCV for image processing
  - Implemented TCP communication between Python and C# scripts
  - Implemented multithreading for improved performance
- Designed 3D phantoms mimicking human vasculatures
  - Utilized blender to make complex geometries
- Integrated VR control with Electromagnetic Actuation Systems and improved robot control performance by 16.4% due to intuitive and immersive manipulation method
   

 ![1](https://github.com/user-attachments/assets/b6bb151d-2002-4373-bc54-cbf5eb561152)

**2. Design and analysis of wire-driven robotic joints with applications for Minimally Invasive Surgeries** <br />
   This project aimed to eliminate two major problems associated with Single Incision Laparoscopic Surgeries (SILS): (1) Damage to on-site motors and sensors of surgical robots (2) Lack of multifunctionality 
   or accommodating mulitple surgial tools in a confined space. To resolve these two issues I designed and developed a wire actuation system that enables remote placement of electronics and motors as well as 
   enable multifunctionality.

   ![SILS](https://github.com/masum919/portfolio/assets/138081981/3897535a-dc1a-4fbc-abb3-950503e0d912)
 
- Developed wire-driven joints for medical robots to enable remote placement of motors and other electronics for improved device sterilization
  - Devised wire actuation of prismatic, rotation and universal joints
- Built a compact and wire-driven multi-functional robotic tool manipulator for automatic switching of multiple surgical tools
  - Implemented novel design strategy to accommodate 3 surgial tools in a single compact manipulator
- Designed a flexible snake-like robotic arm to mount surgical manipulators for accessing complex regions with redundant degrees of freedom (DOF)
  - Devised wire driven multi-joint flexible robotic arm to access hard to reah regions
- Derived joint kinematics and implemented a PID position control scheme for the wire driven joints, tool manipulator, and the flexible robotic arm
  - Utilized MATLAB Robotics Toolbox
- Improved surgical tool changing time by 30% leading to reduced fatigue and radiation exposure, and improved patient recovery time

**3. Design and development of a robotic landing system for UAVs** <br />
   This project focused on building a self adjusting landing gear for UAVs for safe landing in uneven terrains.

![Landing gear](https://github.com/masum919/portfolio/assets/138081981/e8f9176c-370f-42d1-931e-71a57b3dd1c4)
 
- Designed a mechanical self-adjusting robotic landing gear equipped with Force Resistive Sensors (FSR). The proposed mechanism improves the conventional skid or wheel landing mechanism by allowing adjustable landing on uneven grounds
- Implemented a PID controller with the mechanism leading to a successful drone landing at maximum 12 degree ground inclination

**4. An active orthosis with Tenodesis Effect for pinch force augmentation in activities of daily living** <br />
     In this work, I had developed an inexpensive and simple orthosis to augment pinch grasp force for Spinal Cord Injury (SCI) patients with Tenodesis Effect. The orthosis was made to operate in both passive 
     and active mode. It had only one motor (MAXON DC) and no sensor. Most of the parts were 3D printed.

![AOTE](https://github.com/masum919/portfolio/assets/138081981/af19c1ae-9b76-4ca3-8a77-2d4af23fbf0e)
    
- Designed a robotic 4 bar mechanism to assist impaired hand motions of Spinal Cord Injury (SCI) patients
  - Utilized SolidWorks for design and motion analysis
- Reduced cost by eliminating need for sensors and reduced the number of required motors to a single motor while other robots require up to 3 motors
  - Controlled a MAXON BLDC motor position with an EPOS controller
- Performed kinematics and stress analysis and added safety mechanism to ensure user safety
  - Utilized SolidWorks for simulations
- Designed a worm gear and mini clutch mechanism to switch between active and passive mode of operation
- Devised mechanism for pinch force control to grasp different types of objects. The mechanism can generate a pinch force up to 15 N which is sufficient to perform 75% of daily activities

**5. Development of micro-robotic systems for surgical treatment of chronic total occlusion** <br />
     I have built a FEM simulation model of an 8-core Electromagnetic Actuation System (EAS) with ANSYS MAXWELL. I have also simulated and analyzed the magnetic fields produced by the system to verify the real 
     system for microrobot manipulations.

![ANSYS](https://github.com/masum919/portfolio/assets/138081981/b477ca10-9d8a-4bba-a7e3-d7e5f9a99de9)
     
- Developed a simulation model for an 8 core Electromagnetic Actuation System 
- Validated and analyzed magnetic field distributions with ANSYS MAXWELL by comparing with experimental data

### Publications
- [Virtual Reality-Enabled Intuitive Magnetic Manipulation of Microrobots and Nanoparticles](https://doi.org/10.1002/aisy.202300793)
- [Autonomous 3D positional control of a magnetic microrobots using reinforcement learning](https://doi.org/10.1038/s42256-023-00779-2)
- [Development of a Self-Decoupled Wire-Driven Robotic Universal Joint Toward Medical Application](https://doi.org/10.1115/DMD2022-1016)
- [Driven Multifunctional Manipulator for Single Incision Laparoscopic Surgery](https://doi.org/10.1115/DMD2020-9015)
- [Design and Analysis of a Wire-Driven Multifunctional Robot for Single Incision Laparoscopic Surgery](https://doi.org/10.1115/DETC2020-22471)
- [Development of a Robotic Landing System for UAVs Applied in Various Terrains](https://doi.org/10.1115/DETC2020-22606)

### Awards
DGIST Presidential Fellowship 
- DGIST Presidential Fellowship (4 year scholarship for outstanding students)
  
### Git Repo
- [A ros2 control implementation of a custom hardware interface (arduino) to send motor commands](https://github.com/masum919/ros2_control_custom_hardware_interface)
- [A simple example of simulating a differential drive robot in Gazebo Harmonic](https://github.com/masum919/DiffDrive_Hyundai_Kona_ROS2_Gazebo_Harmonic)
- [FANUC LR MATE 200iD Robot Arm Simulation ROS2](https://github.com/masum919/FANUC-LR-MATE200i)
