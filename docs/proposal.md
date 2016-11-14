# Cube

## Background

Cube is a simple demonstration of WebGL.

There will be an explorable area, with a couple of interactions. The primary showpiece will be a cube floating on a pedastal that the user can drag to rotate. The user will also be able to roam around the room.

## Functionality & MVP

Users will be able to:

- [ ] Walk around the environment and properly collide with walls
- [ ] Click on the cube and drag the mouse to rotate the cube horizontally
- [ ] Hear environmental sound effects
- [ ] Have basic lighting

## Wireframes

![front-view wireframe](https://github.com/VictorAw/Cube/blob/master/docs/wireframes/Front%20entrance%20view.jpg)
![3d-view wireframe](https://github.com/VictorAw/Cube/blob/master/docs/wireframes/3D%20Room%20Layout.png)

## Architecture and Technologies

- [ ] WebGL
- [ ] Sylvester
- [ ] glUtils.js
- [ ] Webpack to bundle up scripts

In addition to the tools listed above, there will be a script file for:

- [ ] Collision detection
- [ ] Loading the correct shaders and vertices
- [ ] Physics
- [ ] Handling interaction

## Implementation Timeline

**Day 1**: Set up Sylvester and an entry javascript file along with an html file. Get the canvas rendering a basic cube.

**Day 2**: Get shaders working and add in vertices for the walls and entryway of the room. Start collision detection.

**Day 3**: Finish collision detection, physics, and controls. Add environmental sound effects using the Web Audio API

**Day 4**: Finishing touches and polish

## Bonus Features

There are many things that I would like to add to the project if time permits:

- [ ] A contact me section in the user interface where a letter pops up that the user can type into and send an email to me with
- [ ] Additional rooms with additional interactions
- [ ] Hidden rooms to discover and explore
