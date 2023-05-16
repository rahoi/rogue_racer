# Racing Roguelike

![Racing Roguelike](https://github.com/rahoi/rogue_racer/blob/main/public/assets/MainMenu.png)

## About
Racing Roguelike is a union between two popular gaming genres, racing games and roguelike games. Racing games typically are a video game genre in which the player participates in a racing competition and roguelike games typically have procedurally generated levels, turn-based gameplay, grid-based movement, and permanent death of the player character. Combining these two genres together will create a unique gaming experience that will attract users that are fans of either genre of video game. We hope to make our game fun and engaging enough to keep our users interested in progressing in the game. We want to take the fast paced engaging gameplay of racing games and combine that with the random generation and interesting upgrades of roguelike games. We want to take the best aspects of each type of game and use those to create something new.

## Development Team
The Racing Roguelike development team has been guided by their sponsor, Jon Rahoi ([jonrahoi](https://github.com/jonrahoi)), and consists of:

- Colin Bindi ([ColinBindi](https://github.com/ColinBindi))
- Steven Lu ([StevenLU0413](https://github.com/StevenLU0413))
- Cameron Kramer ([Cmkramer1](https://github.com/Cmkramer1))

## Play the Game

To play the current version of Racing Roguelike, click [here](https://drive.google.com/drive/folders/1elPPeuwQ7TYmea-vtw8ple85nB8jkaCK?usp=sharing)!

1. Download the zip file for either Windows or Max
2. Run the executable file
    - `Windows users just need to run the executable file`
    - `Mac users need to run the following command before running the exectable file`
        - `chmod +x SeniorTeamProjectMac.app/Contents/MacOS/Racing\ roguelike`
3. Play the game

## Installation
Can be done through 4 steps. Go to FILE, BUILD SETTINGS, select the corresponding OS (Windows/MacOS), and click BUILD AND RUN.

## Usage
This will create an .exe file in corresponding folder (Assets by default).

## Task Management and Issues
- Trello
    - [https://trello.com/b/p2K56wjI/racing-roguelike](https://trello.com/b/p2K56wjI/racing-roguelike)

## Development Dependencies/Technologies
- Unity
    - [https://unity.com/releases/editor/whats-new/2020.3.44](https://unity.com/releases/editor/whats-new/2020.3.44)
    - Version 2020.3.44
- PlasticSCM
    - [https://www.plasticscm.com/download](https://www.plasticscm.com/download)
    - Version 11.0

## Development Environment
- Visual Studio
    - [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
    - Version 17.5.4

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

### Design
The following design demonstrates the aesthetics of our game from Scene to Scene.

![Design](https://github.com/rahoi/rogue_racer/blob/main/public/assets/Design.png)

### Data Flow Diagram
The following diagram demonstrates the flow of data from Scene to Scene.

![Scene Diagram](https://github.com/rahoi/rogue_racer/blob/main/public/assets/DataFlow.png)

### Test Documentation
The following test documentation explains how our code is tested

![Test Documentation](https://docs.google.com/document/d/1etIqaaAcKjNOm8D7NVJk7PTZm3ewYiJLcNySeKN1SgM/edit?usp=sharing)

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

### Midterm Presentation
[https://docs.google.com/presentation/d/1z3Su3tlW_QmH7YirFtQ3MQhMxVxaYfQ6MOpdXavsnRo/edit?usp=sharing](https://docs.google.com/presentation/d/1z3Su3tlW_QmH7YirFtQ3MQhMxVxaYfQ6MOpdXavsnRo/edit?usp=sharing)

### Final Presentation
[https://docs.google.com/presentation/d/1YnBX80psI-J3Ph09G3i4xWLb2IXDLpbzrlEN331Nnco/edit?usp=sharing](https://docs.google.com/presentation/d/1YnBX80psI-J3Ph09G3i4xWLb2IXDLpbzrlEN331Nnco/edit?usp=sharing)

### Credits
Special thanks to

- [Unity Asset Store](https://assetstore.unity.com/) for the awesome assets for the vehicles and map
