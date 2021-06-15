# osl-nodes
The OSL code I make is only tested with Isotropix Clarisse. It is thus designed for Y up axis coordinates in mind.

## Interior Mapping Shader

<img src="interior_mapping/interior_mapping_preview.png" width="800">

| interior_mapping.osl |
|-|
| Room mapping with custom depth and horizontal/vertical scale |
| 4 modular layers, with custom depth and hozizontal/vertical offset |
| Global texture flop for the room, individual texture flop for each layers |
| Testing texture template included |

Interior mapping was invented by Joost van Dongen.\
Thanks to Julius Ihle since I saved quite some time by studying his work.

## Grade

Inspired by Image Engine tools that were my all time favorites.
I will make soon combine_color and combine_float nodes that go with them.

| grade_color.osl |
|-|
| Designed to match Nuke's Grade node |
| + some extras that are needed for advanced lookdev |
| Pre & Post remap options to avoid extra recurrent nodes use |

| grade_float.osl |
|-|
| Base on grade_color.osl for float only |
| Pre & Post remap options to avoid extra recurrent nodes use |

## Mask

| mask_ramp.osl |
|-|
| Create ramp mask based on World/Object position |
| Output can be unclamped/clamped to default values/clamped to custom values |

| mask_sphere.osl |
|-|
| Create spherical mask based on Center/Radius/Feather values |
| Output can be unclamped/clamped to default values/clamped to custom values |
| Will feature oval options soon |


## Feedback
Code is never clean enough, settings are never self-exaplanatory enough.\
If you have any idea, any issue, feel free to contact me or to submit a commit ;)
