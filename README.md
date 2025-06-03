This article records the updates in PICO Unity OpenXR SDK v1.3.0.
## **Release time**
October 12, 2024
## **Required PICO device system version**
5.11.0 or later
## **What's new**
The following features are available in v1.3.0:
| **Module** | **Feature** | **Description** |
| --- | --- | --- |
| Sense Pack | Spatial Anchor | Spatial anchors can anchor the positions in the virtual environment to the positions in the real environment. After placing and saving spatial anchors, when the user returns to the locations where these anchors were placed, the system can retrieve them and return them to the app. Refer to"[Spatial Anchor](/document/unity-openxr/spatial-anchor/)" for detailed instructions. |
|  | Scene Capture | The Scene Capture feature uses the Room Capture app to enable users to capture the walls, doors, windows, tables, chairs, sofas, and other objects in their real-world environment. This allows for interaction between the captured real-world objects and virtual objects in the mixed reality scene.  Refer to "[Scene Capture](/document/unity-openxr/scene-capture/)" for detailed instructions. |
|  | Spatial Mesh | The Spatial Mesh feature can dynamically scan the real-world scene in real-time, and then convert the contents of the scene into spatial meshes. Spatial meshes are primarily the representation of the physical environment in a mixed reality scene. By reconstructing the physical environment into spatial meshes, it becomes easier to enable interactions between virtual and real-world objects. Refer to "[Spatial Mesh](/document/unity-openxr/spatial-mesh/)" for detailed instructions. |
|  | MR Safeguard | When the distance between the objects in the virtual scene and the PICO headset or controllers is within a certain range, the virtual scene will become semi-transparent, revealing the real-world scene. While ensuring user safety, the MR Safeguard capability can maximize the immersive experience for your app. For detailed instructions, refer to "[MR Safeguard](/en_mr-safeguard)". |

