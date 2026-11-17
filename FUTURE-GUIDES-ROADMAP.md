# Future Guides Roadmap

This collection already covers SDL3, C++, game mathematics, collision and physics, rendering, shaders, audio, input, networking, architecture, debugging, build systems, GitHub, Lua, and DirectX 12. The following additions would make it a more complete game-programming reference library.

## Highest-priority additions

1. **Complete OpenGL guide**  
   Context creation, buffer objects, vertex arrays, textures, framebuffers, GLSL, debugging, modern rendering patterns, and common portability mistakes.

2. **Vulkan in-depth guide**  
   Instance and device creation, swap chains, command buffers, synchronization, descriptors, render passes, pipelines, memory allocation, validation layers, and a complete triangle-to-texture progression.

3. **Metal and cross-platform graphics guide**  
   A comparison of DirectX 12, Vulkan, Metal, and OpenGL, including equivalent concepts and practical portability strategies.

4. **GPU mathematics and linear algebra workbook**  
   Matrix conventions, coordinate spaces, projections, quaternions, transforms, camera systems, interpolation, numerical stability, and worked exercises.

5. **2D collision and physics implementation guide**  
   SAT, circle and capsule tests, broad phase structures, contact manifolds, impulse resolution, friction, restitution, and a small fixed-timestep physics engine.

6. **3D physics engine guide**  
   Rigid bodies, inertia tensors, constraints, sleeping, continuous collision detection, stacks, joints, and debugging physics instability.

7. **Game audio implementation guide**  
   Mixing, buses, streaming, spatial audio, attenuation, reverb, music transitions, latency, voice management, and middleware integration.

8. **Asset pipeline guide**  
   Importing models, textures, animations, and audio; cooking runtime formats; dependency tracking; hot reload; compression; validation; and reproducible builds.

9. **Animation guide**  
   Skeletal animation, skinning, interpolation, animation state machines, blending, blend trees, inverse kinematics, root motion, and animation compression.

10. **UI and immediate-mode GUI guide**  
    Layout, input focus, text rendering, accessibility, localization, retained versus immediate mode, and integrating tools such as Dear ImGui.

## Engine systems worth documenting

- **Entity-component-system architecture:** entity IDs, component storage, systems, queries, archetypes, events, and cache-friendly updates.
- **Reflection and serialization:** runtime type information, versioned data, editor properties, prefab formats, and safe migrations.
- **Resource management:** handles, reference counting, asynchronous loading, streaming, lifetime tracking, and dependency graphs.
- **Scene and world management:** transforms, hierarchy, visibility, level streaming, portals, spatial partitioning, and saveable world state.
- **Particles and VFX:** emitters, simulation, GPU particles, trails, sorting, lighting, and authoring workflows.
- **Lighting and shadows:** forward, deferred, clustered, tiled, cascaded shadow maps, screen-space effects, probes, and image-based lighting.
- **Post-processing:** HDR, tone mapping, bloom, exposure, temporal anti-aliasing, motion blur, ambient occlusion, and color grading.
- **Virtual texturing and streaming:** mip selection, residency, feedback, texture pools, and bandwidth budgeting.
- **Navigation and pathfinding:** grids, navmeshes, A*, hierarchical search, steering, crowd movement, and dynamic obstacles.
- **Game AI:** behavior trees, utility systems, planners, perception, goals, squad coordination, and debugging tools.
- **Networking architecture:** client/server models, replication, prediction, interpolation, rollback, lag compensation, snapshots, and security.
- **Multiplayer services:** matchmaking, lobbies, authentication, persistence, leaderboards, telemetry, and failure recovery.
- **Save games and versioning:** atomic writes, cloud saves, migrations, corruption recovery, and platform-specific storage.
- **Input and accessibility:** rebinding, dead zones, controller families, keyboard layouts, remapping UI, subtitles, color accessibility, and assist modes.

## Tools and production guides

- **Visual Studio for game development:** projects, CMake integration, debugger windows, natvis, sanitizers, profiling, and graphics debugging.
- **CMake for multi-platform games:** presets, toolchains, dependency managers, packaging, install rules, CI builds, and platform-specific targets.
- **Continuous integration:** build matrices, artifact publishing, automated tests, shader compilation, asset validation, and release pipelines.
- **Testing games:** unit tests, integration tests, deterministic simulation tests, replay tests, rendering regression tests, and fuzz testing.
- **Profiling handbook:** CPU sampling, GPU captures, memory tools, frame-time budgets, instrumentation, telemetry, and interpreting counters.
- **Crash reporting and diagnostics:** symbol servers, minidumps, GPU crash dumps, breadcrumbs, log design, and reproducible bug reports.
- **Editor and tooling architecture:** command buses, undo/redo, reflection, inspectors, scene editing, gizmos, and preview worlds.
- **Modding and scripting security:** sandbox design, capabilities, quotas, versioned APIs, untrusted content, and safe hot reload.
- **Packaging and distribution:** Windows, Linux, consoles, storefronts, installers, patching, DLC, save locations, and crash recovery.

## Practical project-sized examples

The collection would benefit from complete, buildable reference projects rather than only topic guides:

- SDL3 + CMake window and game loop starter.
- DirectX 12 triangle, textured cube, and deferred renderer progression.
- Vulkan triangle with validation and a frame graph.
- 2D platformer with collision, animation, audio, save data, and Lua scripting.
- Small 3D demo with glTF loading, PBR materials, skeletal animation, and camera controls.
- Client/server multiplayer sample with prediction and interpolation.
- Asset cooker that converts source assets into runtime packages.
- Headless deterministic simulation with replay recording and automated tests.

## Reference material that would improve the whole collection

- A one-page **API naming and ownership glossary**.
- A **common C++ patterns sheet** for RAII, spans, allocators, handles, and error handling.
- A **coordinate-system comparison sheet** for SDL, DirectX, OpenGL, Vulkan, and common math libraries.
- A **GPU format and texture compression reference**.
- A **frame-time budget worksheet** for 30, 60, 120, and 144 Hz targets.
- A **debugging decision tree** for black screens, device removal, validation errors, crashes, and performance regressions.
- A **shader semantics and binding comparison** for HLSL, GLSL, SPIR-V, and Metal Shading Language.
- A **game-development terminology glossary** for beginners.

## Suggested production order

1. Vulkan and OpenGL fundamentals.
2. Asset pipeline, animation, and resource management.
3. Physics implementation and navigation.
4. Testing, profiling, and continuous integration.
5. UI, accessibility, and localization.
6. Networking and multiplayer services.
7. Lighting, shadows, post-processing, and advanced GPU techniques.
8. Complete buildable sample projects tying the individual guides together.

