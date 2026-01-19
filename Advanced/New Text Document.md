Advanced Game Dev Task: "2D Procedural RPG Combat System"
Welcome to the advanced 2D challenge! This task will test your architecture design, performance optimization, and tool creation skills by building a data-driven 2D RPG combat system with procedural content generation.

🎯 The Goal
Create a modular, data-driven 2D RPG combat framework with procedural generation, a robust attribute system, and full modding support.

🛠 What You'll Create
Data-driven combat system with ScriptableObjects for 2D

Procedural loot generation system

Advanced character attribute system

Custom editor tools for 2D game design

Modding API with JSON support

Performance profiling and optimization for 2D

Event-driven architecture

2D-specific systems (sprite animation, tilemaps, 2D physics)

📋 Step-by-Step Instructions
Phase 1: Advanced 2D Project Architecture
Step 1: Project Foundation & 2D Package Setup
Create a new Unity 2D project

Install required packages:

Input System

TextMeshPro

2D Animation

2D PSD Importer (optional)

Unity Recorder (for profiling)

Set up enterprise-level 2D folder structure with clear organization for sprites, tilemaps, and 2D-specific systems

Step 2: Implement Event-Driven Architecture for 2D
Create an event system with 2D-specific events

Focus on combat events with 2D positions

Include sprite animation events

Create tilemap interaction events

Step 3: Create 2D Character Attribute System
Build a robust character attribute system optimized for 2D

Include 2D-specific stats (moveSpeed, jumpForce, attackRange)

Design modifiers for 2D physics interactions

Create animation speed modifiers

Phase 2: Data-Driven 2D Combat System
Step 4: Implement ScriptableObject-Based Design for 2D
Create core 2D combat data structures

Ability system with 2D range and area-of-effect

Projectile patterns for 2D space

Sprite-based visual effects

Step 5: Create 2D Animation System
Build a sprite animation controller

State machine for 2D animations

Blend trees for smooth transitions

Frame-by-frame animation support

Step 6: Implement 2D Tilemap Procedural Generation
Create dungeon generator using Unity's Tilemap system

Room generation algorithms

Corridor placement

Tile variation and decoration

Phase 3: Advanced 2D Systems
Step 7: Create 2D Physics-Based Combat
Implement 2D physics interactions

Raycasting for line-of-sight

Collider-based hit detection

Physics-based projectiles

Step 8: Build Procedural Loot System for 2D
Create item generation with 2D sprite variations

Weighted random generation

Level-based scaling

Visual feedback for rare items

Step 9: Implement 2D Camera System
Create advanced camera controller

Smooth follow with prediction

Room-based camera constraints

Screen shake for combat feedback

Phase 4: Modding & Tool Creation
Step 10: Create Modding System for 2D Assets
Build JSON-based mod loader

Support for custom sprites and animations

Ability definitions via external files

Tilemap data loading

Step 11: Develop 2D Editor Tools
Create custom Unity editor tools

Sprite animation timeline editor

Tilemap brush customization tool

Level design palette tool

Step 12: Build Ability Editor for 2D
Visual tool for designing 2D abilities

Projectile trajectory editor

Area-of-effect visualization

Animation event sequencing

Phase 5: Performance & Optimization
Step 13: Implement 2D-Specific Performance Optimizations
Focus on 2D rendering performance

Sprite atlasing system

Tilemap chunk optimization

Particle pooling for 2D effects

Step 14: Create 2D Profiling Tools
Build performance monitoring for 2D

Sprite draw call tracking

Physics2D performance metrics

Memory usage for texture assets

Step 15: Implement Object Pooling for 2D
Create pooling system optimized for 2D

Projectile pooling

Enemy spawning pools

Particle effect recycling

The Grading System (100 Points Total)
Each task is graded out of 100 points, broken down into two main categories:

A. Technical Implementation & Functionality (60 Points)
Core Requirements Met (25 pts): Does the submitted project do what was asked?

Code Quality & Architecture (20 pts): Is the code clean, well-structured, and scalable?

Error Handling & Robustness (10 pts): Does it handle edge cases gracefully?

Performance & Optimization (5 pts): Is it efficient? (FPS, memory, etc.)

B. GitHub & Development Process (40 Points)
Commit History (15 pts): Small, logical, and descriptive commits.

Branching & Pull Requests (10 pts): Use of feature branches and clear PR descriptions.

Use of Issues/Project Board (10 pts): Breaking down the task into manageable parts.

README & Documentation (5 pts): Clear setup and project explanation.

