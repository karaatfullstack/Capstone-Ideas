## Realtime Sprite Editor

#### Overview
You will be building an application for creating animated sprites. Even more, they shall be able to do so with their friends _in real time_.

#### MVP
Your users should be able to
* Create a sequence of frames, where each frame is a grid of colored cells
* Play the sprite at a given playback speed
* Invite other users by sending them a unique URL for the sprite
* Anyone invited can edit the sprite in real-time
* Revisit the sprite and pick up where they left off

#### Stretch Goals
Users can
* Create Layers (e.g. background, foreground, character). Layers may be "applied" to several frames. Editing the layer edits all the frames where it is applied.
* Export the sprite as either a GIF or a spritesheet (a spritesheet is a single PNG with all the frames lined up next to each other)
* Set the sprite to "private" and only invited registered users can edit the sprite

#### Technical Challenges
* Canvas editing
* Socket state management
* Network efficiency

#### Examples and Inspiration
* [Pixalive](https://github.com/pixalive/pixalive)
  * [Video](https://youtu.be/PVSvkN2WdAw)
* [Piskel](https://www.piskelapp.com/)
  * Not real-time collaboration, but a pretty good Sprite generator
