# **Purpose** #
Patsy (PAper Table Simulator made easY) is an application I wrote because I noticed that my friends who played DnD (Dungeons and Dragons) sometimes had a hard time managing everything that was going on in combat, as there could be ambiguities as to where AOE effects were and what various unit ranges were.

---

# **Features** #
## **Current** ##
  * Multi person interaction.
  * Display of a scalable grid.
  * Allowing each the placement of PCs, NPCs.
## **In Progress** ##
  * Correct display of each object once its present.
  * Placement of AOE effects.
  * Each PC, NPC, and AOE's stats can be modified on the fly with control tiles.
  * Transparent data display overlays.

---

# **Intended Use Scenario** #
## **Ideal** ##
The intended was to use Patsy is to have a webcam looking down onto the field of play to track the objects, and a projector projecting onto the same surface.
## **Secondary** ##
It would work just as well to have the camera and projector _under_ the table of play, but this has not been tested, as I do not have a sufficiently large clear table.
## **Alternate** ##
An alternate usage scenario is to either replace the projector with a normal screen or to have it project at a wall. The interface would still operate the same way, but it would be somewhat less intuitive to use (as each player would need to relate their physical position with whats on the screen).
# **Download/Usage Notes** #
  * The program uses the reacTIVison vision engine (or a simulator) to detect fiducials. As of now, it does nothing with finger input. It may work with other sources of TUIO data, but this has not been tested.
  * To compile the program, you need the TUIO Java libraries, found at the reacTIVision website.