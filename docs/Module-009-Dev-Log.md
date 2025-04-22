## Name: Joseph Conlon
### Module: 08

### Date: [04/21/2025]

#### Goals for this Module
- [x] Finalize a playable version of the game map.
- [x] Begin character sprite design and animation.
- [x] Add basic player movement mechanics.
- [x] Define corner spawn points for 2–4 players.

#### Progress
- **What I accomplished**:
  - Polished the initial map layout to be visually consistent and symmetrical.
  - Created draft character sprites for player avatars.
  - Implemented basic movement using keyboard controls.
  - Assigned and tested unique spawn points for different player counts.

- **Challenges faced**:
  - Balancing player start distances to the center while maintaining symmetry.
  - Making character movement feel responsive on a grid-based map.
  - Pixel-perfect collision handling on tile-based obstacles.

- **Solutions**:
  - Used a coordinate system to calculate spawn and center distances.
  - Smoothed movement using step-based control instead of raw coordinates.
  - Set up invisible collision objects and adjusted hitboxes for cleaner interactions.

#### Learnings
- Visual consistency in sprite and tile sizes is crucial to avoid janky-looking movement.
- Playtesting player positions reveals small issues that don’t show up in the editor.
- Simple mechanics like movement and collision are foundational and deserve polish early on.

#### Free Thinking
- Might add slight map variants or modes depending on player count.
- Possible use of character color or shape to easily identify each player.
- Could experiment with audio for lava tiles or edge feedback to add polish.

#### Next Steps
- Add animations for movement and idle states.
- Begin drafting player abilities or special tiles (e.g. speed boosts, traps).
- Implement turn-based or real-time multiplayer logic depending on game direction.
