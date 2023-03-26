# Unity XRI starter project with Meta Quest passthrough.

A sample starter project using [Unity XRI samples](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@2.3/manual/index.html) targeting Meta Quest Pro including passthrough and hand-tracking functionalities.

![Screenshot 2023-03-12 at 20 26 11](https://user-images.githubusercontent.com/99928/224571549-98475d5b-c48a-49a7-ac8e-cf3f09352f11.png)

As described in [this article](https://localjoost.github.io/Passthrough-transparency-with-MRTK2-and-3-on-Quest-2Pro/), the setup required the creation of a new game object for enabling the passthrough native functionalities including a OVR manager script with enabled passthrough:

<img width="476" alt="image" src="https://user-images.githubusercontent.com/99928/227773238-5bd3a795-04ef-4d06-8c59-714fb81c5183.png">

An OVR passtrough layer needs to be present with the placement set to "Underlay":

<img width="466" alt="image" src="https://user-images.githubusercontent.com/99928/227773351-9607d09f-21fa-47c0-b194-19cf34f4c3eb.png">

The camera settings, and in particular the "Output"->"HDR" option needs to be modified as below to correctly have the passthrough working as "Underlay":

<img width="477" alt="image" src="https://user-images.githubusercontent.com/99928/227773478-cefc9589-26d6-4be6-9790-9c7d3b6f1132.png">

### References:
- Unity XR Interaction Toolkit samples and starter projects - https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@2.3/manual/index.html
- Oculus Integration plugin - https://assetstore.unity.com/packages/tools/integration/oculus-integration-82022
- Quest passtrough API official documentation: - https://developer.oculus.com/documentation/unity/unity-passthrough/
- MRTK Quest see through - https://github.com/LocalJoost/MRTKQuestSeeThrough
