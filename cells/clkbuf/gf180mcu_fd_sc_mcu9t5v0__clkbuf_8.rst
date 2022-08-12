====================================
gf180mcu_fd_sc_mcu9t5v0__clkbuf_8
====================================

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_8 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_8.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_8 symbol

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_8 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_8 schematic

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_8 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_8.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_8 layout


| CLKBUF_X8 is a clock buffer with 8X drive strength

|
| Attributes

============= ======================
**Attribute** **Value**
area          73.382400 µm\ :sup:`2`
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


.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_8.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0221
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | Z(LH)      | default            | 0.0100       | 0.0010            | 0.1392         | 0.0253        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | Z(HL)      | default            | 0.0100       | 0.0010            | 0.1291         | 0.0232        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(LH)      | 0.0010            | 0.9098              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(HL)      | 0.0010            | 1.3568              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.3666
I                  0.3610
================== ==============

