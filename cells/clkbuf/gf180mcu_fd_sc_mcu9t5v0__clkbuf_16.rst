====================================
gf180mcu_fd_sc_mcu9t5v0__clkbuf_x16
====================================

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x16 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_16.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x16 symbol

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x16 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x16 schematic

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x16 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_16.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x16 layout


| CLKBUF_X16 is a clock buffer with 16X drive strength

|
| Attributes

============= =======================
**Attribute** **Value**
area          141.120000 µm\ :sup:`2`
============= =======================

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


.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_16.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0444
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | Z(LH)      | default            | 0.0100       | 0.0010            | 0.1395         | 0.0252        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | Z(HL)      | default            | 0.0100       | 0.0010            | 0.1293         | 0.0231        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(LH)      | 0.0010            | 1.8317              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(HL)      | 0.0010            | 2.7241              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.6832
I                  0.6720
================== ==============

