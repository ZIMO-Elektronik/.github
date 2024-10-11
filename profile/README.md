# Welcome to ZIMO's Site on GitHub

[ZIMO Elektronik](https://zimo.at) is a manufacturer of digital components for model railways based in Vienna, Austria. Since it was founded 40 years ago, ZIMO's software stack has always been written by passionate developers who love to tinker with their products. Now we want to give others the opportunity to do the same and have therefore decided to release parts of our software under permissive licenses.

Below you can find a selection of ZIMO's open-source projects. Our full repository list can be found [here](https://github.com/orgs/ZIMO-Elektronik/repositories).

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#communication">Communication</a></li>
      <ul>
        <li><a href="#mx10">MX10</a></li>
        <li><a href="#track">Track</a></li>
        <li><a href="#ulf">ULF</a></li>
      </ul>
    <li><a href="#utilities">Utilities</a></li>
    <li><a href="#miscellaneous">Miscellaneous</a></li>
  </ol>
</details>

## Communication
### MX10
Libraries for communication with MX10 devices
| Name                                            | Description                                    |
| ----------------------------------------------- | ---------------------------------------------- |
| [zcan](https://github.com/ZIMO-Elektronik/zcan) | ZCAN10/20 protocol over Ethernet or serial/CDC |

### Track
Libraries for communication via tracks
| Name                                              | Description                                                                                                                |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| [DCC](https://github.com/ZIMO-Elektronik/DCC)     | DCC protocol for controlling digital model railways                                                                        |
| [DECUP](https://github.com/ZIMO-Elektronik/DECUP) | DECUP protocol for [ZPP](https://github.com/ZIMO-Elektronik/ZPP) and [ZSU](https://github.com/ZIMO-Elektronik/ZSU) updates |
| [MDU](https://github.com/ZIMO-Elektronik/MDU)     | MDU protocol for [ZPP](https://github.com/ZIMO-Elektronik/ZPP) and [ZSU](https://github.com/ZIMO-Elektronik/ZSU) updates   |
| [MM2](https://github.com/ZIMO-Elektronik/MM2)     | MM1/2 protocol for controlling digital model railways                                                                      |

### ULF
Libraries for serial/CDC communication with ULF devices
| Name                                                              | Description                                                          |
| ----------------------------------------------------------------- | -------------------------------------------------------------------- |
| [ULF_COM](https://github.com/ZIMO-Elektronik/ULF_COM)             | ULF communication                                                    |
| [ULF_DCC_EIN](https://github.com/ZIMO-Elektronik/ULF_DCC_EIN)     | [DCC](https://github.com/ZIMO-Elektronik/DCC) as ASCII protocol      |
| [ULF_DECUP_EIN](https://github.com/ZIMO-Elektronik/ULF_DECUP_EIN) | [DECUP](https://github.com/ZIMO-Elektronik/DECUP) as binary protocol |

## Utilities
Libraries for general use
| Name                                                    | Description                                                                                                                                                           |
| ------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [QtBreeze](https://github.com/ZIMO-Elektronik/QtBreeze) | [CMake](https://cmake.org/) wrapper for [breeze-icons](https://github.com/KDE/breeze-icons) and [BreezeStyleSheets](https://github.com/Alexhuszagh/BreezeStyleSheets) |
| [QtQwt](https://github.com/ZIMO-Elektronik/QtQwt)       | [CMake](https://cmake.org/) wrapper for [Qwt](https://qwt.sourceforge.io/)                                                                                            |
| [Salsa20](https://github.com/ZIMO-Elektronik/Salsa20)   | Stream cipher                                                                                                                                                         |
| [ZTL](https://github.com/ZIMO-Elektronik/ZTL)           | ZIMO template library                                                                                                                                                 |

## Miscellaneous
Non(ish)-code related things
| Name                                                                      | Description                                                     |
| ------------------------------------------------------------------------- | --------------------------------------------------------------- |
| [.github-workflows](https://github.com/ZIMO-Elektronik/.github-workflows) | Bundles reusable GitHub workflows                               |
| [CMakeModules](https://github.com/ZIMO-Elektronik/CMakeModules)           | Bundles [CMake](https://cmake.org/) modules and toolchain files |
| [ZPP](https://github.com/ZIMO-Elektronik/ZPP)                             | ZPP file specification                                          |
| [ZSU](https://github.com/ZIMO-Elektronik/ZSU)                             | ZSU file specification                                          |