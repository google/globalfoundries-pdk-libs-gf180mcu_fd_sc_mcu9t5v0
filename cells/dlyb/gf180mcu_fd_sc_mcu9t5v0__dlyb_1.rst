====================================
gf180mcu_fd_sc_mcu9t5v0__dlyb_1
====================================

**gf180mcu_fd_sc_mcu9t5v0__dlyb_1 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb_1.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__dlyb_1 symbol

**gf180mcu_fd_sc_mcu9t5v0__dlyb_1 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__dlyb_1 schematic

**gf180mcu_fd_sc_mcu9t5v0__dlyb_1 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb_1.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__dlyb_1 layout


| DLYB_X1 is a 4 buffer delay cell with 1X drive strength

|
| Attributes

============= ======================
**Attribute** **Value**
area          36.691200 µm\ :sup:`2`
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


.. image:: gf180mcu_fd_sc_mcu9t5v0__dlyb_1.png


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
| I(LH)         | Z(LH)      | default            | 0.0100       | 0.0010            | 0.7777         | 0.0537        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | Z(HL)      | default            | 0.0100       | 0.0010            | 0.8766         | 0.0841        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(LH)      | 0.0010            | 0.3723              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(HL)      | 0.0010            | 0.5388              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.1560
I                  0.1531
================== ==============

