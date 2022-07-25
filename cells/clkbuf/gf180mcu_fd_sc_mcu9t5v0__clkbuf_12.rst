====================================
gf180mcu_fd_sc_mcu9t5v0__clkbuf_x12
====================================

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x12 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_12.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x12 symbol

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x12 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_12.schematic.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x12 schematic

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x12 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_12.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x12 layout


| CLKBUF_X12 is a clock buffer with 12X drive strength

|
| Attributes

============= =======================
**Attribute** **Value**
area          107.251200 µm\ :sup:`2`
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


.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_12.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0334
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | Z(LH)      | default            | 0.0100       | 0.0010            | 0.1393         | 0.0253        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | Z(HL)      | default            | 0.0100       | 0.0010            | 0.1291         | 0.0231        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(LH)      | 0.0010            | 1.3690              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(HL)      | 0.0010            | 2.0390              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.5249
I                  0.5165
================== ==============

