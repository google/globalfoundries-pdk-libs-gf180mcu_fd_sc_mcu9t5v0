====================================
gf180mcu_fd_sc_mcu9t5v0__dlyb_4
====================================

**gf180mcu_fd_sc_mcu9t5v0__dlyb_4 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb_4.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__dlyb_4 symbol

**gf180mcu_fd_sc_mcu9t5v0__dlyb_4 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__dlyb_4 schematic

**gf180mcu_fd_sc_mcu9t5v0__dlyb_4 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb_4.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__dlyb_4 layout


| DLYB_X4 is a 4 buffer delay cell with 4X drive strength

|
| Attributes

============= ======================
**Attribute** **Value**
area          53.625600 µm\ :sup:`2`
============= ======================

|
| OUTPUT FUNCTIONS

============== ============
**Output Pin** **Function**
Z              I
============== ============

|
| TRUTH TABLE FOR Z

===== =====
**I** **Z**
1     1
0     0
===== =====

|
| FUNCTIONAL SCHEMATIC


.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb_4.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0026
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | Z(LH)      | default            | 0.0100       | 0.0010            | 1.1647         | 0.0850        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | Z(HL)      | default            | 0.0100       | 0.0010            | 1.6794         | 0.2033        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(LH)      | 0.0010            | 1.7077              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(HL)      | 0.0010            | 3.9481              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.2366
I                  0.2298
================== ==============

