# About Unity Physics
The Unity Physics package provides a stateless, high-performance constrained rigid body simulation.

# About this package
This package provides a custom authoring experience for creating rigid bodies and colliders for Unity Physics.

The original source of this package comes from installing the "Custom Physics Authoring" sample from the Unity Physics package in the package manager.

It is provided here as a package to make it easier to manage and upgrade.

# Installing

## From GitHub

From the package manager window, click the + and select the option to use a git url, and paste in https://github.com/redwyre/com.redwyre.physics-custom-authoring.git

## From OpenUPM

If you are already using OpenUPM you can merge this snippet with your project manifest:

{
    "scopedRegistries": [
        {
            "name": "package.openupm.com",
            "url": "https://package.openupm.com",
            "scopes": [
                "com.redwyre.physics-custom-authoring"
            ]
        }
    ],
    "dependencies": {
        "com.redwyre.physics-custom-authoring": "1.0.11"
    }
}

For more ways to install with OpenUPM see https://openupm.com/packages/com.redwyre.physics-custom-authoring/
