# Racing Roguelike

![Racing Roguelike](https://github.com/rahoi/rogue_racer/blob/main/public/assets/MainMenu.png)

## About
Racing Roguelike is a union between two popular gaming genres, racing games and roguelike games. Racing games typically are a video game genre in which the player participates in a racing competition and roguelike games typically have procedurally generated levels, turn-based gameplay, grid-based movement, and permanent death of the player character. Combining these two genres together will create a unique gaming experience that will attract users that are fans of either genre of video game. We hope to make our game fun and engaging enough to keep our users interested in progressing in the game. We want to take the fast paced engaging gameplay of racing games and combine that with the random generation and interesting upgrades of roguelike games. We want to take the best aspects of each type of game and use those to create something new.

## Development Team
The Racing Roguelike development team has been guided by their sponsor, Jon Rahoi ([jonrahoi](https://github.com/jonrahoi)), and consists of:

- Colin Bindi ([ColinBindi](https://github.com/ColinBindi))
- Steven Lu ([?](https://github.com/?))
- Cameron Kramer ([?](https://github.com/?))

## Play the Game

To play the current version of Racing Roguelike, click [here](https://rahoi.github.io/racing-roguelike/)!

## Installation
Can be done through x steps. Go to FILE, BUILD SETTINGS, select the corresponding OS (Windows/MacOS), and click BUILD AND RUN.

## Usage
This will create an .exe file in corresponding folder (Assets by default).

## Task Management and Issues
- Trello
    - [https://trello.com/b/p2K56wjI/racing-roguelike](https://trello.com/b/p2K56wjI/racing-roguelike)

## Development Dependencies/Technologies
- Node.js
    - [https://nodejs.org/en/download/](https://nodejs.org/en/download/)
    - Version 16.15.1
- Jest
    - [https://jestjs.io/](https://jestjs.io/)
    - Version 28.0.7
- Svelte
    - [https://svelte.dev/](https://svelte.dev/)
    - Version 3.49.0
- Vite
    - [https://vitejs.dev/](https://vitejs.dev/)
    - Version 2.9.9
- Phaser 
    - [https://phaser.io/download/stable](https://phaser.io/download/stable)
    - Version 3.55.2 “Ichika” 
- catmull-rom-interpolator
    - [https://github.com/rciszek/catmull-rom-interpolator](https://github.com/rciszek/catmull-rom-interpolator)
    - Version 1.0.1
- hull.js
    - [https://github.com/AndriiHeonia/hull](https://github.com/AndriiHeonia/hull)
    - Version 1.0.2
- MRPAS
    - [https://bitbucket.org/umbraprojekt/mrpas/src/master/](https://bitbucket.org/umbraprojekt/mrpas/src/master/)
    - 2.0.0

## Development Environment
- Visual Studio Code
    - [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
    - Version 1.63.2
- TypeScript 
    - [https://www.typescriptlang.org/download](https://www.typescriptlang.org/download)
    - Version 4.7.4

## Getting Started
To contribute to Racing Roguelike or branch off and continue the project,

1. Clone the repo
2. Install dependencies
    - `npm i`
3. Start the local development server
    - `npm run dev`
4. Make changes to the repo
5. View changes on the local server
    - [http://localhost:3000/](http://localhost:3000/) (if port 3000 is not already in use)
6. Add tests to the [tests](https://github.com/rahoi/racing-roguelike/tree/main/tests) folder
7. Run tests and verify test results
    - `npm test`
8. For building and deployment:
    - If pushing to the main branch on this repo, [deploy.yml](https://github.com/rahoi/racing-roguelike/blob/main/.github/workflows/deploy.yml) will automatically start a GitHub Action to build and deploy the updated project to [this](https://rahoi.github.io/racing-roguelike/) GitHub Pages site
    - If branching off and continuing the project on your own, you'll have to either set up GitHub Pages for your own repo, or delete [deploy.yml](https://github.com/rahoi/racing-roguelike/blob/main/.github/workflows/deploy.yml) and run `npm run build` to build for deployment and deploy onto a site of your choosing

### Scripts and Usage
- [deploy.yml](https://github.com/rahoi/racing-roguelike/blob/main/.github/workflows/deploy.yml)
    - starts a GitHub Action to build the project, then deploy to GitHub pages

### Architectural Diagram
The following diagram demonstrates the architectural design of this project.

![Architectural Diagram](https://github.com/rahoi/racing-roguelike/blob/main/public/assets/architectural-diagram.png)

### Data Flow Diagram
The following diagram demonstrates the flow of data from Scene to Scene.
![Scene Diagram](https://github.com/rahoi/rogue_racer/blob/main/public/assets/DataFlow.png)

### Completed Features
Below are major features of the game that have been implemented and are working in the current version of Racing Roguelike:

- Procedurally Generated Race Track
- Random Terrain
- Vehicle Physics
- Weather Conditions
- Checkpoints
- Vehicle Selection
- Timer

### TODO/Future Planned Features
Below are some features that have not been implemented, but are the next steps to pursue:

- Multiplayer
- Improved Enemy AI
- Random Objectives

### Credits
Special thanks to

- [Unity Asset Store](https://assetstore.unity.com/) for the awesome assets for the vehicles and map
