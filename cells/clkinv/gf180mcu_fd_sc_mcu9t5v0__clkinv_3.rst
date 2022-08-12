====================================
gf180mcu_fd_sc_mcu9t5v0__clkinv_3
====================================

**gf180mcu_fd_sc_mcu9t5v0__clkinv_3 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_3.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_3 symbol

**gf180mcu_fd_sc_mcu9t5v0__clkinv_3 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_3 schematic

**gf180mcu_fd_sc_mcu9t5v0__clkinv_3 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_3.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkinv_3 layout


| CLKINV_X3 is a clock inverter with 3X drive strength

|
| Attributes

============= ======================
**Attribute** **Value**
area          22.579200 µm\ :sup:`2`
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


.. image:: gf180mcu_fd_sc_mcu9t5v0__clkinv_3.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0167
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | ZN(HL)     | default            | 0.0100       | 0.0010            | 0.0388         | 0.0162        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | ZN(LH)     | default            | 0.0100       | 0.0010            | 0.0298         | 0.0179        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(HL)     | 0.0010            | -0.0423             |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | ZN(LH)     | 0.0010            | 0.3212              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.1263
I                  0.1306
================== ==============

