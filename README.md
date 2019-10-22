# yoxbox

# 1. Introduction

This project is meant to be an opensource design for a modular storage and work space organization system. It provides a set of conventions and guidelines for building interchangeable and modular components and cases to house them. There are many good storage solutions, but most are proprietary, expensive and cannot be interchanges with other existing systems.

## 1.1 Terminology

***Conventions***: which must be followed if you intend to ensure that parts are interchangeable and compatible within the system. These are numbered as C100 (for cases) and M100 (for modules). 
 
***Guidelines***: are helpful suggestions to follow, but do not necessarily break the interchangeability of the system. These are numbered as C200 (for cases) and M200 (for modules).

# 2. System description

The system is based on a *case* that can contain one or more *modules*. The concept that ties the case and insert together is the *cell*.

## 2.1 Cell

<img src="images/cell_ext.png" width="300">

#### Cell100
*Convention:* The cell is defined as 3inch sized cube. This is a core concept of the system and provides the basis to build interchangeable modules.

## 2.2 Case

#### C100
*Convention:* The case is an enclosure whose *internal* dimensions equals to one, or more, *cell* widths (3inches).

#### C101
*Convention*: most modules (e.g. drawers) expect that they will be secured from the front to prevent opening during transport and storage within the case. Therefore it is the responsibility of the user to ensure that the configuration they adopt prevents free forward movement of a module, if necessary (note that some cases that are not portable may not have a front cover, or require any securing of the modules). See design guides sections for examples of securing the modules.

####  C200
*Guideline:* Cases are usually expected to be 1 cell deep. Shallow drawers do not hide access to items, so deeper cases are considered generally sub-optimal for many storage scenarios. It is assumed that systems of 1 or 2 cell depths will satisfy most use cases and that most people will provide compatibility for that design.

#### C201
 *Guideline*: Cases can be of any shape, however, it is expected that most will be rectangular in nature.

#### C202
 *Guideline*: In some cases cases may have internal sizes that are not multiples of a cell (3inches). If the extra space is filled by a custom insert or module, it will ensure that the rest of the case maintains conventions and can remain compatible with other modules. 

#### C203
*Guideline*: Cases are ideally designed to be stacked or stored in existing cupboard/shelving units, therefore the external dimensions should be designed to fit within common sizes (e.g. 12", 16" 18", 24").

#### C204
*Guideline*: It is recommended that cases provide a circular indentation of 6mm in diameter and >= 1mm depth centered at 1inch increments on the internal faces (except the open face), for possible addition of magnets to help secure the cells to the cases.

### 1.2.1 Case design

Case designs are based on an *A* and *B* half.

The *A* half is expected to be a rectangular case of length L, height H, and depth D.

<img src="images/case_int.png" width="300">

The *B* half is expected to be either:
- none (e.g. wall mounted storage may not require a front cover).
- a flat sheet of similar length and height as half *A*.
<img src="images/case_b1.png" width="300">
- mirror of the *A* half.
<img src="images/case_b2.png" width="300">
- a window shutter design variation of the above.
<img src="images/case_b3.png" width="300">

The *A* and *B* are connected via a hinge on the bottom or side, based on required orientations.

## 2.3 Modules

Modules are meant to be interchangeable units that provide different functionality, like drawers, paint holder, tool holders, etc.

#### M100
*Convention*: Modules need to have *external* dimensions in multiples of a cell size (3inches). A 2 (6inch) length by 2 (6inch)  height by 1 (3inch) depth module is valid.

#### M101
*Convention*: Modules are not meant to be secured to the case, except by that provided by closely packing modules into the case, to avoid cells without any modules. Note that *spacer* modules can secure the cell, but still provide an empty cell space.

#### M102
*Convention*: Modules are expected to assume that other modules would border them on any face and therefore provide structural support. For instance a module without a top plate would not accommodate other modules to sit on top of it. Modules do not, however, need to provide a solid face for other modules, as long as the face remains structurally sound.

#### M200
*Guideline*: Module shapes should be rectangular in nature to fit with common configurations. However, this is optional, as long as a spacer insert can be added to make the module conform to the cell size requirement.

#### M201
*Guideline*: Modules are recommended to be 1 cell deep, however, there are cases where a deeper would be ideal. This is an expected configuration where the case halves are each 1 cell deep, and the module itself is provided as two halves, each inserted into each half of the case.

#### M202
*Guideline*: Securing the front of the module for a portable setup is the responsibility of the case. However, it is recommended that modules try to be secure by providing magnetic or simple latching for openings where feasible.

#### M203
*Guideline*: It is recommended that modules provide a circular indentation of 6mm in diameter and >= 1mm depth centered at 1inch increments on the external faces (except the front), for possible addition of magnets to help secure the cells to the cases.
