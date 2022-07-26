====================================
gf180mcu_fd_sc_mcu9t5v0__clkinv_x16
====================================

**gf180mcu_fd_sc_mcu9t5v0__clkinv_x16 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_16.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_x16 symbol

**gf180mcu_fd_sc_mcu9t5v0__clkinv_x16 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_x16 schematic

**gf180mcu_fd_sc_mcu9t5v0__clkinv_x16 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_16.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_x16 layout


| CLKINV_X16 is a clock inverter with 16X drive strength

|
| Attributes

============= ======================
**Attribute** **Value**
area          95.961600 µm\ :sup:`2`
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


.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_16.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0881
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | ZN(HL)     | default            | 0.0100       | 0.0010            | 0.0352         | 0.0131        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | ZN(LH)     | default            | 0.0100       | 0.0010            | 0.0265         | 0.0149        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(HL)     | 0.0010            | -0.2941             |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(LH)     | 0.0010            | 1.6352              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.4570
I                  0.4797
================== ==============

