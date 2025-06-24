Graham Reeves' Resume
=====================
Last Revision: 24th June 2025.

Key skills
-----------------
- Experience in a huge number of platforms over 25 years
	- Windows/Winapi's (including directx), games consoles (PS2-4, Xbox, gamecube, wii era), Linux (Rapsberry pi, Nvidia jetsons, server-docker instances), macos/ios/tvos/visionos (Objc/UIKit/SwiftUI/Metal etc), android, Web, Server-side developement (AWS, GoogleCloud, node.js etc)
	- XR headsets/platforms; Hololens (WPF/Directx), Magic Leap (Android), Varjo (Steamvr-like), Oculus/Gearvr (desktop & Android)
	- Developing custom arduino devices, bluetooth devices, standalone computing devices (jetson, PI, mac servers - running on-site for weeks at a time)
- Developing in a variety of languages and can quickly pickup new languages. Most notably;
	- C++, javascript, swift, c#, gpu shaders (GLSL,MSL,WGSL,HSL, etc) as well as light use of python, go, perl, etc
- Working in live interactive environments
	- Live volumetric streaming (Most recently https://condensereality.com/ )
	- Live visualisations on commerical film sets (See Analog work)
	- CAVE/Virtual Production environments for film & interactive projects
	- Device & User interactive projects (Using Kinects, camera tracking, custom bluetooth devices, VR/Vive controllers)
- Developing a large mix of applications/products
	- Store-deployed client apps (ie. ios/ipad/desktop apps, XR games)
	- Server-deployed services (User auth & management, leaderboards, live game-servers, logging, server-side processing, etc) 
	- Internal tools (desktop apps, remote controls & monitors for live work)
	- Standalone kiosk-style devices, attached to kinects, cameras, input devices, working independently of apps to make ultra-stable & modular enviroments, or outputting data for consumption by other tools)
	- Specific graphics effects, rendering systems
	- Libraries, plugins & tools in a variety of languages, deployed to Unity, Unreal, CG tools, custom engines/systems

Open Source and R&D Work
--------------------------
A huge amount of work is open-sourced (libraries, tools, simple UI components, backend system templates/examples, initial prototypes) in various languages & packaging systems
- https://github.com/newChromantics/
- Volumetric capture & experimental rendering (SDF/path tracing)
- Various UI libraries for vector animation missing from Unity, SwiftUI etc https://github.com/NewChromantics/PopLottie.UnityPackage
- Reverse engineered Bluetooth Cat-Thermal-Printers https://github.com/NewChromantics/PopCatPrinter
- Turn based board/card multiplayer game system (for online & offline play and rapid prototyping)
- 13kb web-xr competiton games https://grave.quest/ https://js13kgames.com/
- WebGPU & Metal integrations for SwiftUI
- Arudino/ESP device development
- CMS systems for clients which integrate with Git for revision-safe content, drafting & backup
- Various libraries for codecs, file formats and simple package integrations into Unity, SwiftUI, web, etc
- Computer Vision & MachineLearning model integrations (eg. using Whisper for an audio-transcribing API) 

Employment History
----------------
- Eurocom 2001-2008
	- Developing console games (PS2-3, Xbox+360, Gamecube-Wii, Windows)
	- Architecture, Networking, Visual Effects, Gameplay, UI
- TT Games 2008-2009
	- Developing middleware & tools for video games (PS3-4 era)
- Venatrack 2009-2012
	- Live (on-site) player & ball tracking of Premier League Football games, generating on-site stats & visualisations
	- Role switched to Right-hand-man-of-CTO position covering every aspect of the product;
	- Writing game-engine to visualise players & tracking
	- Optimising capture pipeline from Computer Vision to data output across 35 16-core xeon machines (located in vans on-site per match)
	- Rewriting UI/Tooling side for operators
	- Starting to convert CPU computer vision algorithms+pipeline to GPGPU (via OpenCL)
- New Chromantics 2012-Present
	- Own company doing hired-studio projects & freelancing (notable projects below)
- Unity 2013
	- Worked as Developer-Relations, fixing bugs in Unity, helping other developers
	- Was regularly consulted-out by Unity to other games studios to hand-optimise their games and relay notable changes back into the engine 
- Rewind 2013-2015 (Part Time)
	- Working on many studio projects (Often VR & Interactive orientated)
	- Developing some hard-device-prototypes (auto-syncing bluetooth speakers)
	- Developed several CAVE rendering + interactive systems (including ball-tracking with kinects)
	- Made VR music-360-video-playback apps for Gearvr & Oculus DK1/2 for BBC, Bjork, others
	- Worked on deployment of apps to various app-stores
- Condense Reality 2022-2024
	- Live volumetric-capture (from Kinects) of band performances, streamed to web, XR, and mobile apps.
	- Responsible for client-side streaming library to ingest video & data streams from CDN for ios/macos/windows/android/linux/web to output to Unity, Web, Threejs, Unreal, SwiftUI
		- Rewriting existing client-side pipeline from Unity/C# into a faster C++ library which enabled WASM output for web, with no server side changes
		- Optimised each decoding system to stream data (Meshes, Video, Audio, Meta) until latency, memory usage was minimal (To work on very constrained devices)
		- Also integrated direct integration to allow on-site streaming (skipping Cloud) for ultra low latency
	- Senior developer on Unity application, for playback of streams, but also game, UI & UX work, ios integration
	- Wrote various libraries for server/services integrations as well as an animation system for Unity UI toolkit
	- Wrote a javascript version of the unity-only Fishnet networking system to allow web-app play of our game
	- Automated CI/CD pipeline to deploy builds to/from UnityCloudBuild and deploy to Apple+Testflight, Oculus, Stream, Web, with build feedback, strict versioning, testing paths
	- Advised capture side on rewriting formats, encoding, compression to improve throughput at capture, backend and client side, change encoding systems to help future integration
	- Worked on a secret stage at Glastonbury 2023 doing on-site capture
	- Worked on various client-jobs deploying our volumetric capture to client apps/websites
	- R&D into custom lighting engine for live VJ-style effects in venues

New Chromantics
-------------------
In addition to employment history, the company New Chromantics has been hired for many projects, often interactive & XR related.

Below are notable projects
- LiveLike https://livelike.com/
	- Initial prototype of 180-football streams into VR headsets
- In the Eyes Of The Animal https://marshmallowlaserfeast.com/project/in-the-eyes-of-the-animal/
	- Heavily optimised GearVR version to play through 5-million-point scenes
- Gorillaz with G-Shock https://analogstudio.co.uk/work/gorillaz-x-g-shock
	- Live on-site body tracking with cameras, streamed into unity to do 2D puppeteering, on-site during filming to monitors. Little of the capture was edited into the final production
- Three Commerical https://analogstudio.co.uk/work/three
	- Live CAVE system (camera tracked with Vive Tracker) for infinite-views during filming, rendering our audio-reactive backgrounds (tweaked live with OSC controllers)
- Bjork Vulnicura VR album https://store.steampowered.com/app/1095710/Bjrk_Vulnicura_Virtual_Reality_Album/
	- Integrated previous music videos into one "Album" with a new lobby-enviroment for Oculus Rift & Vive
- BladeRunner 2024 VR game prototype (Not released)
- Extend Robotics https://www.extendrobotics.com/
	- Initial research & development of encoding/streaming & decoding of kinect/depth camera feeds into client applications 
- Guildhall + Museum of London https://www.instagram.com/p/Bv7m8gAFK3M/
	- Created a camera-tracked bluetooth fake-spray can which could "spray" a video onto a wall as part of an exhibition
- Google Arts
	- Development of an interactive web experience with webgl https://experiments.withgoogle.com/diving-into-an-acidifying-ocean
- Google Arts & Centre Pompidou
	- Did the development of an interactive web-experience for a planned Kandinsky exhibition at the Pompidou (physical installation cancelled due to Covid) https://experiments.withgoogle.com/play-a-kandinsky
- Varjo - hired for work on their eye-tracking computer-vision work integrated into headsets
- Hired by Condense (later employed) for integration of Open-Source library PopH264 https://github.com/newChromantics/poph264 
