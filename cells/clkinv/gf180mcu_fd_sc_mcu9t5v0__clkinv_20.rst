====================================
gf180mcu_fd_sc_mcu9t5v0__clkinv_x20
====================================

**gf180mcu_fd_sc_mcu9t5v0__clkinv_x20 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_20.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_x20 symbol

**gf180mcu_fd_sc_mcu9t5v0__clkinv_x20 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_20.schematic.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_x20 schematic

**gf180mcu_fd_sc_mcu9t5v0__clkinv_x20 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_20.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_x20 layout


| CLKINV_X20 is a clock inverter with 20X drive strength

|
| Attributes

============= =======================
**Attribute** **Value**
area          118.540800 µm\ :sup:`2`
============= =======================

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


.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_20.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.1101
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | ZN(HL)     | default            | 0.0100       | 0.0010            | 0.0353         | 0.0131        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | ZN(LH)     | default            | 0.0100       | 0.0010            | 0.0267         | 0.0148        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(HL)     | 0.0010            | -0.3685             |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(LH)     | 0.0010            | 2.0444              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.5588
I                  0.5871
================== ==============

