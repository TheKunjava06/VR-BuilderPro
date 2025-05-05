VR BuilderPro

Project Overview
Duration: 5 Months
Project Mentors: N Nagabhushanam, Dhanush V, Tanay Shekokar
Team Members: Unnati Kumari, Ganesh Madhav Rajesh, Sameer Jamkhandi

1. Introduction
1.1 Project Statement
VR BuilderPro is an advanced virtual reality (VR) application designed for interior designers, architects, and home planners to create, modify, and visualize 3D environments in an immersive setting. The platform allows users to construct virtual rooms by specifying dimensions and interactively placing objects, offering a seamless experience in space planning and design.
1.2 Background Survey
The use of VR in interior design has been gaining traction due to its ability to enhance visualization and streamline decision-making. Traditional design tools such as AutoCAD and SketchUp offer precise modeling capabilities but lack the immersive experience VR provides. Many designers struggle with conveying spatial relationships to clients using 2D blueprints or static 3D renders. VR BuilderPro bridges this gap by offering:
Real-time immersive visualization.
Interactive object manipulation.
Enhanced user experience through intuitive VR controls.

2. Methodology
 2.1 Techniques & Approach
The VR BuilderPro system follows a structured approach to allow seamless 3D room design and customization in a VR environment. The methodology integrates user input, scene generation, and interactive modification, ensuring a smooth and intuitive experience.
User Interaction & Input Handling


The user provides room dimensions via a VR interface.


A TextMeshPro-based input field captures the length, width, and height.


Once confirmed, the system processes the input and initializes the 3D scene accordingly.


Scene Generation & Object Placement


A transform algorithm creates walls, floors, and ceilings dynamically based on input dimensions with existing prefabs.


The system ensures that the player is positioned at the center of the room upon scene initialization.


Interactive 3D Object Overlay & Modification
Objects such as furniture and decorations can be modified in real time through VR gestures or via a UI panel.

 2.2 System Architecture & Workflow
The VR BuilderPro architecture follows a modular approach, ensuring flexibility and scalability in handling user interactions, scene generation, and dynamic object modifications. The system consists of multiple interconnected components that work together to create an immersive VR experience.
System Components: 
User Interface Module


Captures user input for room dimensions through TextMeshPro fields.


Provides interactive UI elements like buttons, dialogs, and selection menus.


Displays confirmation dialogs for wall creation, modifications, and save/load options.



Scene Generation Module


Uses unity’s transform techniques to construct walls, floors, and ceilings dynamically based on input dimensions.


Ensures correct scaling and positioning of all room elements.


Implements collision detection to prevent overlapping walls and objects.


Player Positioning & Movement Module


Makes sure the player is placed at the center of the generated room after creation.


Uses raycasting to detect user interactions with walls, furniture, and other objects.


Object Customization Module


Provides an interface for users to add objects to walls, floors, and furniture in real-time.
Allows users to modify room elements using VR hand gestures or UI buttons.
The code architecture


Used an architecture dividing Data, Domain and Presentation layer by isolating each other and creating interfaces between them.
Presentation layer directly the Unity’s interface and the Data and Domain layers are coded along with components present in the presentation layer. 

Workflow Breakdown
The VR BuilderPro workflow consists of the following sequential steps:
1. User Input Handling
The user enters length, width, and height via the UI.


The system validates the input and processes it.


2. Automatic 3D Room Generation
Based on the user’s input, a complete room (floor, walls, ceiling) is generated at once.


The player is positioned at the center of the room.


3. Interaction & Modification
Users can add objects to walls, floors, and furniture using an in-game UI.


The Workflow Diagram is given below: 



 2.3 Tools & Technologies Used

Software: Unity 2022.3.60f1, C#, TextMeshPro, ProBuilder, VR SDKs (Oculus Integration, OpenXR)
Hardware: Meta Quest 2, motion controllers

 3. Results & Analysis
User Experience
High interactivity and seamless VR navigation.
Reduced learning curve compared to CAD-based tools.
Enhanced realism due to real-time object interaction and physics.

4. Challenges & Learnings
Obstacles Faced
Rendering Limitations: Optimizing complex 3D assets without affecting frame rates.
User Interaction Issues: Ensuring natural and precise VR gestures.
Collision Detection Optimization: Preventing objects from overlapping in real-time.
4.2 Solutions & Insights
Performance Enhancements: Implemented Level of Detail (LOD) techniques and real-time texture streaming.
Improved Gesture Controls: Integrated haptic feedback for precise object manipulation.
Efficient Collision Handling: Used spatial partitioning and bounding box optimization to improve object physics.
5. Conclusion & Applications
Key Takeaways
      VR BuilderPro enhances interior design by providing:
A real-time immersive design process.
User-friendly object placement and customization.
Enhanced spatial visualization.
Real-World Use Cases
Architectural Pre-Visualization: Allows architects to review designs before physical construction.
Home Planning & Renovation: Enables homeowners to test layouts before purchasing furniture.
Educational Training: Used in design and architecture courses to train students in spatial planning.
Beneficiaries
Interior designers, architects, real estate developers, and VR enthusiasts looking for an innovative design tool.

 6. Future Work & Enhancements
Multi-User Collaboration: Real-time multi-user sessions for team-based design projects.
Save and load progress: Users can save current progress and load the previous session at ease.
Expanded Asset Library: Addition of more furniture, decor, and customizable materials.
Advanced Physics & Lighting: Enhanced material interactions such as cloth physics and dynamic lighting effects.


7. References


Docs:

Scripting

Welcome to the Unity Scripting Reference

Unity Essentials Pathway

VR Development Pathway - Unity Learn


Videos:

C# Tutorials : https://www.youtube.com/watch?v=gfkTfcpWqAY&list=PLTjRvDozrdlz3_FPXwb6lX_HoGXa09Yef

https://www.youtube.com/watch?v=HB1aPYPPJ24&list=PL0eyrZgxdwhxD9HhtpuZV22KxEJAZ55X-


Assets:

Modular First Person Controller | 3D Characters | Unity Asset Store

Chair pack - 3D Low Poly Office Furniture - Created with FastMesh Asset

Desks starter collection | 3D Furniture | Unity Asset Store


