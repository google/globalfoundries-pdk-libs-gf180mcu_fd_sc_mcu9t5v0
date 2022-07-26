====================================
gf180mcu_fd_sc_mcu9t5v0__inv_1
====================================

**gf180mcu_fd_sc_mcu9t5v0__inv_1 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__inv_1.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__inv_1 symbol

**gf180mcu_fd_sc_mcu9t5v0__inv_1 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__inv.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__inv_1 schematic

**gf180mcu_fd_sc_mcu9t5v0__inv_1 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__inv_1.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__inv_1 layout


| INV_X1 is an inverter with 1X drive strength

|
| Attributes

============= ======================
**Attribute** **Value**
area          11.289600 µm\ :sup:`2`
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


.. image:: gf180mcu_fd_sc_mcu9t5v0__inv_1.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0070
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | ZN(HL)     | default            | 0.0100       | 0.0010            | 0.0332         | 0.0155        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | ZN(LH)     | default            | 0.0100       | 0.0010            | 0.0446         | 0.0280        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(HL)     | 0.0010            | -0.0054             |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(LH)     | 0.0010            | 0.1368              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.0756
I                  0.0769
================== ==============

