# PE_VR_Cobots
 This project focuses on developing an immersive and interactive virtual reality (VR) simulation aimed at training users on the operation and configuration of collaborative robots (cobots) in an industrial environment. The simulation leverages Unity and VR technologies to offer an engaging, hands-on learning experience.

## Features
- Interactive Industrial Environment: Includes 3D models such as warehouses, conveyor belts, and shelves for realistic scenarios.
- Scenario-based Learning: Covers key training modules, including:
  - Configuring cobot commands.
  - Managing AGV (Automated Guided Vehicle) operations and avoiding errors.
  - Troubleshooting common configuration issues.
- 360° Video Integration: Combines 360° immersive videos with interactive 3D environments for enhanced realism.
- Dynamic Error Feedback: Interactive pop-ups to simulate real-world error handling and provide pedagogical guidance.
- Unity Integration: Built with Unity, using tools like the XR Interaction Toolkit and Oculus XR Plugin for VR compatibility.

## Development Process
- Environment Modeling: Created and imported 3D assets using Unity and Blender for a cohesive industrial setting.
- Interactive Simulation: Developed scripts to handle user interactions with the cobots and control interface.
- VR Implementation: Integrated VR functionality using Oculus Rift S and Quest 2 for testing.
- Error Handling & Pedagogy: Designed contextual error messages to enhance user understanding during the simulation.
- Testing & Validation: Conducted iterative testing with XR Device Simulator and Oculus headsets.

## Challenges
- Compatibility Issues: Encountered technical difficulties launching executables directly on Oculus devices.
- Interactive Integration: Adapting 360° videos into a 3D environment with Unity required extensive shader adjustments.
- Limited Hardware Resources: Addressed hardware constraints, such as slow compile times, through optimization.

## Future Improvements
- Establishing a streamlined testing environment to ensure executables run seamlessly on VR headsets.
- Expanding training scenarios to include advanced troubleshooting and unexpected events.
- Enhancing graphical quality with advanced shaders and optimized asset design.

## Technical Stack
- Technologies: Unity, Blender, Oculus SDK
- Languages: C#, Unity Visual Scripting
- VR Tools: XR Interaction Toolkit, Oculus XR Plugin, Visual Scripting

## Getting Started
- Clone the repository.
- Open the project in Unity (2022.x or later recommended).
- Ensure Oculus XR Plugin is installed and configured.
- Test the simulation using the Oculus Rift S or Quest 2 in Link mode.

## License
This project is licensed under MIT License.
