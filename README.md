# VR lessons

## Cross platform

Iterate often: get things out early and often

### UI
- UI elements and instruction text have to reference what a user is using

### Hardware
- Complexity of project code
- **OLED** VS **LED** displays: impact environment and UI design (colors, dithering)
- **3DoF** VS **6DoF** controllers: 

### Environments
- One of the biggest challenges for lower-end hardware; designed for 6DoF
- Arc-based teleporting and grid snapping helped make selected seats easier
- Performance remains a challenge
  - PC > 300 draw calls
  - Mobile < 30 draw calls
- Limit mobile users to specific teleport areas to reduce detail
- use [unlit shaders](https://unity3d.com/learn/tutorials/topics/graphics/anatomy-unlit-shader) to account for battery life considerations

### Product 
- "What value do we provide for users per platform?"
- Users on high-end devices want to invite friends with mobile
- Distill down to core values to provide the value users want on the application

### Avatars
- Avoid full body, since the experience is largely seated
- Eye gazing and blinking eyes are used with a "POI" system to predict and simulate what a users looks at
- "It doesn't have to be realistic, it has to be believable"
- Only render what you know or can easily estimate

### Leaning problem
- Linear environments made it impossible for 3DoF users to talk to each other, so curved seats were needed.




Credits to:
- [DShankar, Bigscreen](https://twitter.com/dshankar)


## Unity Assets
- [Video Capture](https://assetstore.unity.com/packages/tools/video/video-capture-75653)
