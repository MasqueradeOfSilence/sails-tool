# sails-tool
Sail animation tool for Stowaway (BYU Animation)

Naming Convention for Branches: STOW-SAIL-###-issue
- "Issue" will describe what I'm working on, such as "wind-simulation". 

Thought Processes for Sail-003:
- I made both the sails into DOP objects. This added a DOP node in their geometry network (for all the other nodes, the geometry node stayed blank). 
- File node is pretty straightforward. I think the warning about accessing locked stuff only matters if I'm trying to access the file itself (I hope), but let's just get it working for now and worry about that later. I think it just means that you can't lock anything. Which I don't need to do anyway. 
- Rest node is for ensuring that textures stick on. 
- setup-packed-prims is mainly to generate geometry at run-time (so not important to what we're currently doing, I don't think). 
- DOP import node makes it mobile
- To automatically organize nodes, hit L for layout
- Ok, the wind isn't doing anything. But it should work even for a static object. 
- "Simple FX" tab has a simple cloth. 
- So as of today, 9/08, we got the simple cloth material working. However, it falls to the ground for some reason, and I can't seem to figure out how to properly add wind. 
