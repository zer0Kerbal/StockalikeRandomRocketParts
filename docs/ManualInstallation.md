---
permalink: /ManualInstallation.html
title: ManualInstallation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.6.0
Stockalike Random Rocket Parts (SaRRP)
created: 01 Oct 2019
updated: 14 Apr 2022 -->

<!-- based upon work by Lisias -->

# Stockalike Random Rocket Parts (SaRRP)

[Home](./index)

Stockalike Random Rocket Parts for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the AlbertKerminIndustries folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/AlbertKerminIndustries`
* Extract the package's `AlbertKerminIndustries/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/AlbertKerminIndustries` --> `<KSP_ROOT>/GameData/AlbertKerminIndustries`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/AlbertKerminIndustries/StockalikeRandomRocketParts`

### If Downloaded from SpaceDock / GitHub / other

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/AlbertKerminIndustries`
* Extract the package's `GameData/AlbertKerminIndustries` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData/AlbertKerminIndustries` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/StockalikeRandomRocketParts`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [AlbertKerminIndustries]
      + [StockalikeRandomRocketParts]
        + [Assets]
          ...
        + [Compatibility]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * changelog.md
        * CC-BY-ND-4.0.txt
        * readme.htm
        * StockalikeRandomRocketParts.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none
