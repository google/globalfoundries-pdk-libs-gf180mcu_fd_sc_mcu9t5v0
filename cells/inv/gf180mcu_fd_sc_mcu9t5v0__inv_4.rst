====================================
gf180mcu_fd_sc_mcu9t5v0__inv_4
====================================

**gf180mcu_fd_sc_mcu9t5v0__inv_4 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__inv_4.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__inv_4 symbol

**gf180mcu_fd_sc_mcu9t5v0__inv_4 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__inv.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__inv_4 schematic

**gf180mcu_fd_sc_mcu9t5v0__inv_4 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__inv_4.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__inv_4 layout


| INV_X4 is an inverter with 4X drive strength

|
| Attributes

============= ======================
**Attribute** **Value**
area          28.224000 µm\ :sup:`2`
============= ======================

|
| OUTPUT FUNCTIONS

============== ============
**Output Pin** **Function**
ZN             (!I)
============== ============

|
| TRUTH TABLE FOR ZN

===== ======
**I** **ZN**
0     1
1     0
===== ======

|
| FUNCTIONAL SCHEMATIC


.. image:: gf180mcu_fd_sc_mcu9t5v0__inv_4.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0272
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | ZN(HL)     | default            | 0.0100       | 0.0010            | 0.0258         | 0.0096        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | ZN(LH)     | default            | 0.0100       | 0.0010            | 0.0319         | 0.0177        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(HL)     | 0.0010            | -0.0706             |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(LH)     | 0.0010            | 0.4634              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.1523
I                  0.1574
================== ==============

