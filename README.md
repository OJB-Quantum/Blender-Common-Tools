# Blender-Common-Tools
A repository of Onri's most used tools or sub-tools for rendering in Blender.

The primary URL for the repository: [OJB-Quantum/Blender-Common-Tools](https://github.com/OJB-Quantum/Blender-Common-Tools)

__________________________________________________________________

## [Download Blender Here](https://www.blender.org/download)

__________________________________________________________________

|  |
| - |
| [Onri's Free Blend Files Here (Examples for Reference)](https://github.com/OJB-Quantum/Free-Blender-Models) |
| [Generate a Coffee Mug in Blender](https://youtu.be/FpLpFMq-Jdk?si=auHfYnZulDSlEP9O) |
| [Onri's Chip Rendering Tutorials](https://youtube.com/playlist?list=PLbW5jviv4ckwvvhSjwONc6pa-glNdI6vg&si=tV7Yeq_iGdnVXbLw) |

__________________________________________________________________

| Supplementary YouTube Tutorials |
| - |
| [How to Render Faster In Blender Cycles](https://youtu.be/boMoTlnj9Mw?si=l5aWUtfLfO_vjeKZ) |
| [6 Minutes of Boolean Basics, Blender Secrets](https://youtu.be/_S3D8djM5bE?si=R8XP6i_JRW26wFZI) |
| [Loop Tools Tips, Blender Secrets](https://youtube.com/playlist?list=PLrB1kuJIjcg4UByYChm0sojwfy87RincB&si=cT6be2h_AgWlrQ_o) |
| [Shade Auto Smooth, Ryan King Art](https://youtu.be/WT29Hyv2XX8?si=DG-mETUzCpBWWrW1)
| [Blender Glare Node for Cycles Glow / Bloom, Brandon 3D](https://youtu.be/N9p00A7P5h8?si=eUaph8IPTgahYMbL) |
| [Fill Holes in a Mesh, Buvesa Game Development](https://youtu.be/mkfv5ecpvvs?si=wZVfQo-JLvOyUxJJ) |
| [Create Projectors Fast, CGMatter](https://youtu.be/adahnQCqmw0?si=hdK1bFHX82S0qBEB) |
| [How to make Blender Eevee Look Realistic - Indirect Lighting, Void Visuals](https://youtu.be/6R4pnPwCA3U?si=tkyVCdaELI5eU3AD) |
| [Improve your animations with the Graph Editor, 3Dschool](https://youtu.be/QeI2ivhchDg?si=V70MDlX2FJwgkaED) |

| YouTube Channels | Description |
| - | - |
| [Ryo Mizuta Graphics](https://youtube.com/playlist?list=PLDEMMuOUBj1ZPNZV_SIfvPWcCubXM1Biq&si=vvsFk0cM80d3cajC)| 3D Rendering Tutorials for Scientific Illustration Using Blender |
| [CGFigures](https://www.youtube.com/@CGFigures/playlists) | 3D Rendering Tutorials for Scientific Figures Using Blender |
| [Brandon 3D](https://youtube.com/playlist?list=PLYjDeW9Aw0jajsHUG4uXFMy-CplZzPIpv&si=RzoU6zsQ1B8qSfow) | Comprehensive 3D Rendering Tutorials Using Blender |
| [QuickTipsCentral](https://youtube.com/playlist?list=PLw4YtOBgDIiMEx6_14Kj4a7xioJTcnXxV&si=cTXZf7hyj-rZ2guO) | 3D Modeling & Rendering Tutorials at <1 Minute Each Using Blender |
| [BlenderVitals](https://youtube.com/playlist?list=PLMDIokDTwYr2P7NJkiEPbezEZsgW9Yr_N&si=AGickgU4PaTdoMrd) | 3D Rendering Tutorials at 1 Minute Each Using Blender |
| [1 minute Blender](https://youtube.com/playlist?list=PLFmCO7KRkJbCtKIHG33didkEZdYIjVRy9&si=SdrL3UahNIgLyQ_D) | 3D Rendering Tutorials at 1 Minute Each Using Blender |
| [CG Cookie](https://youtube.com/playlist?list=PL3GeP3YLZn5hNd8eLSC64RX3Cr2I9xu8o&si=EhdbeEkkkgBUhqeC) | 3D Rendering Tutorials Using Blender |
| [Blender Secrets](https://www.youtube.com/@BlenderSecrets/playlists) | 3D Animation Tutorials Using Blender |
| [KennyPhases](https://youtube.com/playlist?list=PLeT-XEXZURqMDgk-Zv8xBASoTgI6aMZ3k&si=Rmoa70kj7huolcVg) | 3D Animation Tutorials Using Blender |
| [PIXXO 3D](https://www.youtube.com/@PIXXO3D/playlists) | 3D Animation Tutorials Using Blender |

__________________________________________________________________

## Tables of Useful Tools & Shortcuts with Descriptions:

| General | Description |
| - | - |
| • Fast GI Approximation | For faster rendering of lighting scenes, besides the use of GPU-accelerated Optix denoising. |
| • Deleting interior faces | For faster rendering by allowing the system to spend less time on rendering faces that cannot be seen in the render view mode. |
| • The use of Wireframe mode in Viewport Shading to select all vertices, edges, or vertices | So you won't accidentally miss the selection of any vertices, edges, or faces. |
| • The use of Alpha setting under Materials Properties to quickly set 2D or 3D objects to a desired transparency | To show rendered objects behind a surface. |
| • Solidify | For adding thickness to an object mesh to use it as a solid 3D model. |
| • Bake | For calculating associated physics in the Blender model. |
| • Screw Modifier | For turning a selected object into a coil shape or similar. |
| • Bevel Modifier | For adding a touch of realism to objects with "sharp" edges. Set the amount to 0.002 m and # of segments to 10. |
| • Build Modifier | For animating objects to gradually appear into view frame by frame. |
| • Smooth by Angle Modifier + Shade Smooth | Smoothes curved object surface based on the desired angle while retaining sharper, 90 degree edges. |
| • Render Properties >> Advanced >> Seed >> Click timer box icon | Animates the noise texture in the lighting conditions. |
| • Material Properties >> Add a new material >> Surface (set to Principled BSDF, pick color) >> Specular (set to Multiscatter GGX, pick color) | To allow an object to change color based on the viewing angle. |
| • Physics >> Collision >> Field Absorption, Damping, and Friction | Set to max to allow particles to stick to selected object. |
| • Render Settings >> Film >> Pixel Filter | Set to a wdith of 1 pixel or less to increase sharpness and clarity of overall render outcome. | 
| • Object Properties >> Shading >> Caustics >> Receive Shadow Caustics| When box is checked, it allows for caustic effect to project on a selected object's surface. Make sure caustic effects are turned on (usually on by default under Render Properties tab >> Light Paths >> Caustics). |


| In Object Mode | Description |
| - | - |
| • Add Mesh | For adding 2D and 3D shapes. |
| • Shade Smooth + Smooth by Angle Modifier | For smoothing rough edges of added shapes. |
| • Selection of Objects + Hide [H key] | For hiding of desired objects in Object Mode. This is great for isolating the selection of smaller objects in a scene. |
| • Nurbs [Bezier curve] >> Data >> Geometry >> Bevel >> Depth | For easy creation of wire from surface to surface. |
| • Ctrl + Shift + [-] | To cut 2 or more overlapping objects after selecting all desired objects, be sure to hide the cutting object's render on the right panel. |
| • Ctrl + Join [J key] | For joining selected objects after first selecting one of the objects. |



| In Edit Mode (Given that you select desired shape) | Description |
| - | - |
| • Face Mode selection >> press A >> Mesh tab >> Normal >> Recalculate outside | For remeshing. |
| • Face Mode selection >> press Alt + E >> Press S or Spin | For creating a circle array of selected object. |
| • Any Selection Mode >> Mesh >> Clean Up >> Limited Dissolve | For merging vertices, edges, or faces into one section. Merge by Distance is a similar tool available under the same tab. |
| • Select >> Checker Deselect | For selection of every other face around an object such as a cylinder mesh. Perfect for creating gears. |
| • Fill [F key] | For filling selected edges that are closed or not open-ended. |
| • Loop Cut | For sectioning added shapes into smaller sections for modification. |
| • Inset [I key] | For creating a form of offset of a face. |
| • Separate by parts [P key] | For separating previously joined objects. |
| • Vertex Mode selection >> press J >> Loop Cut as needed >> Face Mode selection >> Bridge Edge Loops | For connecting vertices, sectioning faces into smaller pieces as needed, then selecting desired faces to cut a hole into a 3D object. |
| • Shrink/Fatten | For extruding individual or selected vertices, edges, or faces. |
| • Grid Fill | For closing selected edges. |
| • Bridge Edge Loops | For closing selected edges between 2 planes. |
| • Bevel | For selecting edges, extruding it with the E key, selecting a direction to extrude the edge(s) with X, Y, or Z, then using the scale tool or S key to stretch the selected edges inward or outward. |
| • Add Single Vertex | For extruding an added vertex in vertex selection to draw a modifiable line. |
| • Select tab >> Select All by Trait >> Interior Faces >> Right-Click >> Delete faces | For deleting faces not expected to display in the render view mode, saves rendering time as well. |

_____________________________________________________

## Rendering Resolutions That Can Be Set Under the 'Output Properties' Tab:

| I have a personal preference for 3:2 aspect ratio, so here are some resolutions I like |
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

### When importing DXF layouts, 0.0005 should be scale value to fit in the viewport.

______________________________________________________
