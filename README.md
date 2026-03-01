# REE JCNS Template #
A 010 Editor binary template for parsing Joint Constraints (*.jcns) files from most RE Engine games. <br>

Currently work in progress. Not sure everything is correct! <br>
You can help this project by providing further information about any unknown data. <br>

This was separated from my [MHWs Research repository](https://github.com/XenonBaruku/MHWs-Research-Templates). Older file changes, issues and histories could be found there.

## Supported JCNS Versions / Games
| JCNs Version | Game                                                                                 |
| ------       | ------                                                                               |
| 11           | Resident Evil 2 Remake / Devil May Cry 5                                             |
| 12           | Resident Evil 3 Remake                                                               |
| 16           | Resident Evil 8                                                                      |
| 21           | Monster Hunter Rise Sunbreak                                                         |
| 22           | Resident Evil 4 Remake / Street Fighter 6                                            |
| 24           | Dragon's Dogma 2                                                                     |
| 29           | Monster Hunter Wilds (pre-TU4)                                                       |
| 35           | Resident Evil 9 / PRAGMATA SKETCHBOOK DEMO / Monster Hunter Stories 3 Trial Version  |
| 102          | Monster Hunter Wilds (post-TU4)                                                      |

## Sections
| ID     | Description (unofficial)| Common Suffixes                                | Supported?               |
| ------ | ------                  | ------                                         | ------                   |
| 0      | Ranges                  | RS, drv, BS (BlendShape), MB (MaterialBlend)   | Yes (with unknown data)  |
| 1      | Rotation Expressions    | RotExpression, Subjoint, Second                | Yes (with unknown data)  |
| 2      | Skin Constraints        | SC, CS, Skin, Point                            | Yes (with unknown data)  |
| 3      | Aim Constraints         | Aim                                            | Yes (with unknown data)  |
| 4      | Material Constraints    | MC                                             | Yes (with unknown data)  |
| 5      | Joint Export Graph      | /                                              | Yes                      |

## TODO
 * Editing (Maybe do this in Blender or something else)
 * Full unicode support for hash generation

# Credits
 * Thank everyone who provided infomation about the file structures.
