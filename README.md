# Blender-Common-Tools
A repository of Onri's most used tools or sub-tools for rendering in Blender.
__________________________________________________________________
## [Download Blender Here](https://www.blender.org/download)
### [Onri's Free Blend Files Here (Examples)](https://github.com/OJB-Quantum/Free-Blender-Models)
__________________________________________________________________
| General | Description |
| - | - |
| • Fast GI Approximation | For faster rendering of lighting scenes besides the use of GPU-accelerated Optix denoising. |
| • Deleting interior faces | For faster rendering by allowing the system to spend less time on rendering faces that cannot be seen in the render view mode. |
| • The use of Wireframe mode in Viewport Shading to select all vertices, edges, or vertices | So you won't accidentally miss the selection of any vertices, edges, or faces. |
| • Solidify | For adding thickness to an object mesh to use it as a solid 3D model. |
| • Bake | For calculating associated physics in the Blender model. |
| • Screw Modifier | For turning a selected object into a coil shape or similar. |
| • Smooth by Angle Modifier + Shade Smooth | Smoothes curved object surface based on the desired angle while retaining sharper, 90 degree edges. |
| • Render Properties >> Advanced >> Seed >> Click timer box icon | Animates the noise texture in the lighting conditions. |
| • Material Properties >> Add a new material >> Surface (set to Principled BSDF, pick color) >> Specular (set to Multiscatter GGX, pick color) | To allow an object to change color based on the viewing angle. |
| • Physics >> Collision >> Field Absorption, Damping, and Friction | Set to max to allow particles to stick to selected object. |
_________________________________________________________________________
| In Object Mode: | Description |
| - | - |
| • Add Mesh | For adding 2D and 3D shapes. |
| • Shade Smooth + Smooth by Angle Modifier | For smoothing rough edges of added shapes. |
| • Selection of Objects + Hide [H key] | For hiding of desired objects in Object Mode. This is great for isolating the selection of smaller objects in a scene. |
| • Nurbs [Bezier curve] >> Data >> Geometry >> Bevel >> Depth | For easy creation of wire from surface to surface. |
| • Ctrl + Shift + [-] | To cut 2 or more overlapping objects after selecting all desired objects, be sure to hide the cutting object's render on the right panel. |
___________________________________________________________________________
| In Edit Mode (Given that you select desired shape): | Description |
| - | - |
| • Face Mode selection >> press A >> Mesh tab >> Normal >> Recalculate outside | For remeshing. |
| • Face Mode selection >> press Alt + E >> Press S or Spin | For creating a circle array of selected object. |
| • Fill [F key] | For filling selected edges that are closed or not open-ended. |
| • Loop Cut | For sectioning added shapes into smaller sections for modification. |
| • Shrink/Fatten | For extruding individual or selected vertices, edges, or faces. |
| • Grid Fill | For closing selected edges. |
| • Bridge Edge Loops | For closing selected edges between 2 planes. |
| • Bevel | For selecting edges, extruding it with the E key, selecting a direction to extrude the edge(s) with X, Y, or Z, then using the scale tool or S key to stretch the selected edges inward or outward. |
| • Add Single Vertex | For extruding an added vertex in vertex selection to draw a modifiable line. |
| • Right Click >> Limited Dissolve | For simplifying meshes with too many vertices. |
| • Select tab >> Select All by Trait >> Interior Faces >> Right-Click >> Delete faces | For deleting faces not expected to display in the render view mode, saves rendering time as well. |
_____________________________________________________
| I have a personal preference for 3:2 aspect ratio, so here are some resolutions I like: |
| - |
| 1620 x 1080 pixels = 3:2 aspect ratio version of 1080p. |
| 2160 x 1440 pixels = 3:2 aspect ratio version of 2K. |
| 2880 x 1920 pixels = 3:2 aspect ratio version of 3K. |
| 3840 x 2560 pixels = 3:2 aspect ratio version of 4K. |
| 4096 x 2730 pixels = 3:2 aspect ratio version of 4K Cinema. |
| 5120 x 3413 pixels = 3:2 aspect ratio version of 5K. |
| 5760 x 3840 pixels = 3:2 aspect ratio version of 5.7K. |
| 7680 x 5120 pixels = 3:2 aspect ratio version of 8K. |
| 15360 x 10240 pixels = 3:2 aspect ratio version of 16K. |
| 30720 x 20480 pixels = 3:2 aspect ratio version of 32K. |
### Note: at 3K resolution format, a combination of noise threshold at 0.09, max samples of 295, with fast GI approximation enabled, and no denoising can render 385 frames in ≈ 15 minutes. Using 75 or 95 samples works fine as well for animations. 15 or 20 samples works well for 8K resolution format.
______________________________________________________
| Supplementary YouTube Links: |
| - |
| [How to Render Faster In Blender Cycles](https://youtu.be/boMoTlnj9Mw?si=l5aWUtfLfO_vjeKZ) |
| [6 Minutes of Boolean Basics, Blender Secrets](https://youtu.be/_S3D8djM5bE?si=R8XP6i_JRW26wFZI) |
| [Loop Tools Tips, Blender Secrets](https://youtube.com/playlist?list=PLrB1kuJIjcg4UByYChm0sojwfy87RincB&si=cT6be2h_AgWlrQ_o) |
| [Shade Auto Smooth, Ryan King Art](https://youtu.be/WT29Hyv2XX8?si=DG-mETUzCpBWWrW1)
| [Blender Glare Node for Cycles Glow / Bloom, Brandon 3D](https://youtu.be/N9p00A7P5h8?si=eUaph8IPTgahYMbL) |
| [Fill Holes in a Mesh, Buvesa Game Development](https://youtu.be/mkfv5ecpvvs?si=wZVfQo-JLvOyUxJJ) |
| [Create Projectors Fast, CGMatter](https://youtu.be/adahnQCqmw0?si=hdK1bFHX82S0qBEB) |
| [How to make Blender Eevee Look Realistic - Indirect Lighting, Void Visuals](https://youtu.be/6R4pnPwCA3U?si=tkyVCdaELI5eU3AD) |
