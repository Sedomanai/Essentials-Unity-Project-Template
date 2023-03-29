# Essentials Unity Project Template
    Project template for Unity: Essentials (Good for tutorials setup (not graphics related, not using URP)

## Packages
    com.unity.2d.psdimporter: 6.0.6,
    com.unity.ide.visualstudio: 2.0.16,
    com.unity.inputsystem: 1.4.4,
    com.unity.textmeshpro: 3.0.6,
    com.unity.ugui: 1.0.0,
    com.unity.modules.animation: 1.0.0,
    com.unity.modules.audio: 1.0.0,
    com.unity.modules.imgui: 1.0.0,
    com.unity.modules.jsonserialize: 1.0.0,
    com.unity.modules.particlesystem: 1.0.0,
    com.unity.modules.ui: 1.0.0,
    com.unity.modules.uielements: 1.0.0,
    com.unity.modules.umbra: 1.0.0

## Layers
    Default (Default, Transparent FX, Ignore Raycast, Water, UI)
    Player
    Player Static Collider
    Enemy
    Enemy Static Collider
    Wall
    Projectile
    Checker
    Check Listener
    Stencil
    Garbage Collector

## Project Settings

### Player
    Company Name : Elang
    Product Name : [Product Name] (Make sure to replace it with new product name)
    Version      : 0.0.01

### Physics
    Gravity           : -9.81 in z axis
    Default Material  : Default Material (Assets/Template/Default Material)
    Layer Collision Matrix :
        Enemy / Player Static Collider
        Enemy / Wall
        Player / Enemy Static Collider
        Player / Wall
        Projectile / Player
        Projectile / Enemy
        Projectile / Wall
        Checker / Check Listener

### Enter Play Mode
    Enter Play Mode Options : True
        Reload Domain & Reload Scene : False

## Assets
    Default Material.physicsMaterial2D
    Global Light Settings
    Input System Settings
    Scene Template
    
