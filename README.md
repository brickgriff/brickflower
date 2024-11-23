# brick and flower
## html canvas game engine

### feature plan

- [ ] fix file structure
  - [x] index.html - project files, libraries
  - [x] index.css - global stylesheet, animations
  - [x] main.js - main game loop, config
  - [ ] world.js - world state (model)
  - [ ] display.js - canvas methods (view)
  - [x] buffer.js - user input (controller)
- [ ] minimalist tools
  - [ ] light-camera-action
    - [ ] canvas helpers (lights)
      - [ ] shapes([[x,y]])
      - [ ] polygon(x,y,radius,vertexCount)
      - [ ] arc(x,y,radius,angle,offset), circle, ellipse
      - [ ] color palettes, themes
    - [ ] viewport controls (camera)
      - [ ] look
      - [x] zoom
      - [ ] pitch
    - [ ] player control (action)
      - [x] move
      - [ ] touch
  - [ ] main menu
  - [ ] debug frame
- [ ] fix basic data
  - [ ] game CRUD
  - [ ] world config
  - [ ] entities, systems, patterns, assets, etc
  - [ ] sessions
- [ ] fix basic elements
  - [ ] time - frames, millis (main.js)
  - [ ] space - pixels, spans, turns (display.js)
  - [ ] matter - primitives (world.js)
  - [ ] energy - deltaMouse (buffer.js)
- [ ] libraries
  - [ ] modeler
  - [ ] physics
  - [ ] seedrandom
  - [ ] shader