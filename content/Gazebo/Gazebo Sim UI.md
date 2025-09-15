opening gazebo with terminal commmand, 
simple, using -v 4, using paths, all of these opening steps.. 
take ss, make boxes, explain each of the colored box to explain all the ui components, each filled with their own exercies to follow (ask them to wait for video which will be dropped soon enough)

then try different local sdf files, but it wont open, take them to their respective folders and then open, it will. then explain model_export_path and similar topics to them 
ask them to play with the code and see the changes on ui

make a world and leave it be, move to the next chapter



![[gazebo_ui.jpg]]


### Pink Box (Top Right): Window Controls

This is the standard set of controls for managing the application window itself.

- **Minimize:** Hides the window.
    
- **Maximize:** Makes the window fill the entire screen.
    
- **Close:** Exits the Gazebo application.
    

---

### Red Box (Top Left): Main Toolbar

This toolbar contains the essential tools for **interacting with and manipulating objects** within the 3D simulation scene. From left to right, the primary tools are for:

- **Selecting:** Click to select objects.
    
- **Translating:** Move selected objects along the X, Y, or Z axes.
    
- **Rotating:** Rotate selected objects.
    
- **Scaling:** Resize selected objects.
    
- **Inserting Shapes:** Quickly add simple shapes like spheres, boxes, and cylinders to the world.
    

---

### Green Box (Middle Right): World Panel

This panel, often called the **Inspector** or **World Inspector**, displays all the global properties and loaded **plugins** for the entire simulation. It's where you can view and configure the "rules" of your virtual world. This includes:

- **Physics:** Shows which physics engine is being used (e.g., `dartsim`).
    
- **Plugins:** Lists all the system and render engine plugins that are active and managing the simulation's behavior and appearance.
    
- **Scene:** Contains properties related to the overall 3D scene, like ambient light and shadows.
    

---

### Blue Box (Middle Right): Entity Tree

This panel lists every single object, or **"entity,"** currently present in your simulation world. It's organized in a tree-like hierarchy. You can see default entities like the `ground_plane` and the `sun` (which provides light). This is your main tool for **finding and selecting specific models** in your world, especially in complex environments with many objects.

---

### Yellow Box (Bottom Left): Simulation Time Controls

These are the fundamental controls for running your simulation.

- **Play/Pause Button:** Starts and stops the flow of simulation time. When paused, the simulation is frozen.
    
- **Step Button:** Advances the simulation by one single, small time step. This is extremely useful for debugging, as it lets you see how your robot behaves frame-by-frame.

