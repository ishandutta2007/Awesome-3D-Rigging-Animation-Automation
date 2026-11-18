# Awesome-3D-Rigging-Animation-Automation

# Top 3D Rigging & Animation Automation Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Text-to-Rigged-Animation Pipelines, Automated 3D Skeleton Binding, AI Motion Capture & Headless Rigging Workflows*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Rigging & Animation Automation**. These tools automate skeleton generation and skin weighting for 3D meshes, convert text prompts or 2D videos into full-body and finger-tracked skeletal animations, retarget motions across disparate rigs, and export production-ready assets for Blender, Unity, Unreal Engine, and Godot.

**Examples** include Mixamo, ActorCore, Plask, DeepMotion, Rokoko Studio, Kinetix, Move.ai, Cascadeur, Wonder Dynamics (Autodesk Flow Studio), AnyWorld, and blendi-remade/prompt2rig (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for text-prompt-to-animation retargeting, autoregressive auto-rigging, browser-based skeletal binding, MCP rigging servers, and markerless video-to-mocap — ideal for indie game developers, technical artists, 3D animators, and AI researchers building automated character pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Adobe Mixamo](https://mixamo.com)**  
  Cloud-based automatic 3D character rigging service and extensive library of downloadable motion-captured animations ready for games and film.

- **[Reallusion ActorCore](https://reallusion.com)**  
  Cloud motion library and AccuRIG browser/desktop platform providing automated humanoid bone placement, skin weighting, and AAA mocap animations.

- **[Plask](https://plask.ai)**  
  Browser-based AI motion capture and 3D keyframe animation editor for extracting, cleaning, and retargeting video motion directly onto rigged characters.

- **[DeepMotion](https://deepmotion.com)**  
  AI-powered cloud markerless motion capture suite converting 2D videos into physics-simulated full-body, hand, and facial 3D character animations.

- **[Rokoko Studio](https://rokoko.com)**  
  All-in-one motion capture software and Rokoko Vision cloud platform supporting inertial mocap suits, smartgloves, and AI webcam/video tracking.

- **[Kinetix](https://kinetix.tech)**  
  No-code cloud AI platform and SDK for generating, auto-rigging, and integrating user-generated 3D character emotes into games and virtual worlds.

- **[Move.ai](https://move.ai)**  
  Multi-camera and single-camera markerless AI motion capture platform delivering studio-grade skeletal character animations without physical suits.

- **[Cascadeur](https://cascadeur.com)**  
  Physics-assisted 3D keyframe animation software with cloud/AI-powered AutoPosing, center-of-mass trajectory editing, and secondary motion tools.

- **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)**  
  Cloud AI VFX studio that automatically detects actor performance from live-action video, tracks cameras, and replaces actors with rigged CG characters.

- **[AnyWorld](https://anyworld.ai)**  
  Cloud AI 3D world and interactive character animation platform enabling rapid character rigging, motion generation, and game asset deployment.


## Open-Source GitHub Projects

- **[blendi-remade/prompt2rig](https://github.com/blendi-remade/prompt2rig)**  
  Open-source (`Apache-2.0`) prompt-to-3D-animation pipeline that generates a motion video clip, extracts 3D body (`GVHMR`) and 15-joint finger (`WiLoR`) kinematics on your local GPU, and plays it live on any Mixamo rig with `.glb` and headless Blender export.

- **[UniRig (VAST-AI-Research)](https://github.com/VAST-AI-Research/UniRig)**  
  SIGGRAPH 2025 open-source unified auto-rigging framework using large autoregressive models to predict valid skeleton trees and per-vertex skinning weights for diverse 3D meshes.

- **[Mesh2Motion](https://github.com)**  
  Free, open-source (`MIT`) browser and desktop Mixamo alternative enabling automated skeletal rigging, weight painting, and 40+ pre-built animations for humans, quadrupeds, birds, dragons, and creatures with GLB/FBX export.

- **[Roboticela/Animator](https://github.com/Roboticela/Animator)**  
  Cross-platform open-source (`AGPL-3.0`) 3D model animation studio built with Tauri, Rust, and Three.js for inspecting bones, authoring keyframe clips, applying procedural humanoid motions, and exporting GLB.

- **[Puppeteer (Seed3D)](https://github.com/Seed3D/Puppeteer)**  
  NeurIPS 2025 open-source framework for automatic 3D skeletal rigging, skinning weight generation, and video-guided differentiable animation exportable to FBX.

- **[AssetFurnace (`Bingeljell/image-to-3dlab`)](https://github.com)**  
  Local-first open-source (`Apache-2.0`) end-to-end pipeline for Apple Silicon and NVIDIA GPUs converting prompts or images into textured, auto-rigged, and animated game characters.

- **[autorig-workbench (`sambena/autorig-workbench`)](https://github.com)**  
  Standalone open-source (`GPL-3.0`) auto-rigger for generated 3D models combining headless Blender execution, per-model `rig.json` definitions, automated audits, and a 3D web results viewer.

- **[AutoTPose (`4onstudios/AutoTPose`)](https://github.com)**  
  Open-source Python and Blender add-on for automatically rigging humanoid GLB/FBX characters and converting them into clean, animation-ready T-poses.

- **[digitalblack210/UniRigMCP](https://github.com)**  
  Open-source Model Context Protocol (MCP) server that automatically rigs 3D models on a local NVIDIA GPU using `UniRig` as an automated step inside AI agent pipelines.

- **[mGear](https://github.com)**  
  Industry-proven open-source (`MIT`) modular rigging and animation automation framework for Autodesk Maya featuring Shifter guide-based biped/quadruped rigs and Synoptic pickers.

- **[Blender (Rigify & CloudRig)](https://github.com)**  
  Flagship open-source (`GPL-2.0+`) 3D creation suite featuring Rigify modular character rigging, Bendy Bones, automatic heat-map skinning, IK/FK snapping, and NLA animation blending.

- **[BlenRig 6](https://gitlab.com)**  
  Free and open-source (`GPL`) full-body and facial auto-rigging and mesh-deform cage system for Blender built for feature-quality character articulation.

- **[vid2anim (`mehulcode12/vid2anim`)](https://github.com)**  
  Open-source (`MIT`) AI motion capture and universal character retargeting studio with a Blender add-on supporting Mixamo, VRM, Rigify, Unreal Engine Mannequins, and raw unrigged meshes.

- **[MaxLiu22/Motion2MixamoRig](https://github.com)**  
  Open-source (`Apache-2.0`) Python and Blender extension that extracts human motion from video or photos and automatically retargets it onto Adobe Mixamo-rigged characters.

- **[HyMotion (Tencent Hunyuan)](https://github.com)**  
  Open-source Diffusion Transformer and flow-matching model generating natural 3D character skeletal animations from text prompts across sports, combat, and daily actions.

### Additional Strong Open-Source Options

- **[Jpalmer95/game-3d-asset-skills](https://github.com)** and **[labrat-0/ratlabs-mesh](https://github.com)** for open-source agentic pipelines turning prompts or character art into auto-rigged `.glb` game assets via `TRELLIS.2`, `Hunyuan3D`, and `SkinTokens`.
- **[FreeMoCap](https://github.com)** and **[BlendCap (`Arcomade/BlendCap`)](https://github.com)** for local markerless multi-camera and single-video performance capture directly into Blender rigs.
- **[auto-rig-web (`nff747/auto-rig-web`)](https://github.com)** and **[Poseforge (`wolfgangjblack/poseforge`)](https://github.com)** for zero-click browser ONNX auto-rigging and interactive 3D gizmo / 2D stick-figure posing.
- **[RigNet (`zhan-xu/RigNet`)](https://github.com)** and **[Neural Blend Shapes](https://github.com)** for deep-learning skeleton prediction, skin weight estimation, and pose-space deformation.
- **[ishandutta2007/Awesome-3D-Character-Animation-Rigging](https://github.com)** for a curated companion index of open-source 3D character rigging and motion-capture repositories.

**Frameworks for building custom systems**: Combine **blendi-remade/prompt2rig** (for prompt-driven motion retargeting) with **UniRig** or **Mesh2Motion**, **autorig-workbench**, and **Blender (Rigify + NLA)** for end-to-end automated 3D rigging and animation pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Prompt-to-rig and video-to-mocap pipelines (such as `prompt2rig`, `GVHMR`, and `WiLoR`) often depend on external video API keys and parametric body/hand models (`SMPL-X`, `MANO`) that carry non-commercial research restrictions — verify model licenses before commercial game deployment.
