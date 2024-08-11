# VR Project: Beat Saber 

## Overview

This project is an Oculus VR game developed using Unity. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/Pvtv_v1YDz8" frameborder="0" allowfullscreen></iframe>

## Features

**Score System**

- Tracks and displays the player's score based on hit accuracy and timing, rewarding precision and rhythm.

**Hit Detector**

- Accurately registers player actions, ensuring only well-timed hits contribute to the score.

**Hit Visual Effect**

- Provides immediate visual feedback for successful hits, enhancing the gameplay experience and keeping players in sync with the music.

**Hit Sound Effect**

- Each successful hit triggers a sound effect synced with the background music, reinforcing rhythm and accuracy.

**3D Background**

- Immersive 3D environments that react dynamically to gameplay, enriching the VR experience.

**Speed Sync with Music**

- Gameplay speed is synchronized with the tempo of the background music, challenging players to stay in rhythm.

## Prerequisites

Unity 2019.3.15f1 or later is recommended.

## Project Structure

```txt
VRproject_BeatSaber/
│
├── Assets/                     
│   ├── Oculus/                     # Contains Oculus-specific assets and settings, including VR interactions and environment setups
│   ├── Resources/                  # Holds resources that are dynamically loaded during runtime (e.g., updated hit effects)
│   ├── Samples/                    # Sample assets and scenes for reference or testing
│   ├── Scenes/                     # Unity scenes used in the project (e.g., main game scenes, environments)
│   ├── TextMesh Pro/               # Assets related to TextMesh Pro for handling high-quality text rendering in VR
│   ├── UnityTechnologies/          # Contains assets provided by Unity Technologies (e.g., updated hit effects)
│   ├── XR/                         # Assets related to extended reality (XR) components, including cross-platform VR support
│   └── XRI/                        # Contains XR Interaction Toolkit assets, supporting interactions in VR
│
├── Packages/                   
│   └── Manifest.json               # Package management file, listing dependencies used in the project
│
├── ProjectSettings/            
│   └── ProjectSettings.asset       # Unity project settings (version control, quality settings, VR settings, etc.)
│
├── run/                        
    ├── Beat Saber_Data/            # Directory containing game data files required for Beat Saber to run
    ├── MonoBleedingEdge/           # Directory containing the Mono runtime files, necessary for running the game on platforms that require Mono
    ├── Beat Saber.exe              # The main executable file for launching the Beat Saber game
    ├── UnityCrashHandler64.exe     # Executable responsible for handling crashes and sending crash reports
    └── UnityPlayer.dll             # Unity runtime library required to run the game on Windows


```

