# RM_BMS_V1.0
Custom BMS using ADI chips for Rensselaer Motorsport

This respository currently contains one major project:

    WIP RM28 Project - This project is the most up-to-date version of the 2024-2025 competition car's custom Battery Management System.

To open and work with these files, specific software packages must be used.

    LTSpice - Circuit simulation software used for preliminary mockups of circuit designs. The .asc files can be opened in other spice programs like ngspice or pspice, but these circuits were originally drafted in LTSpice
    KiCad - PCB design software used for creating schematics for manufacturing.

Acronyms Used:

    VCU - Vehicle Control Unit
    GLV - Grounded Low Voltage
    HV - High Voltage
    BMS - Battery Management System

Typical Circuits:

    Motherboard - Main board that communicates to segment boards as well as VCU. This board is in charge of the overall BMS, as well as safety features and any firmware controls. 
    Segment Board - Distrubuted board that collects cell temps and voltage measurements from individual cell segments. These communicate to the motherboard.
