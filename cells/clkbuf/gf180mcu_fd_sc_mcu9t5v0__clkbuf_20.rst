====================================
gf180mcu_fd_sc_mcu9t5v0__clkbuf_x20
====================================

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x20 symbol**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_20.symbol.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x20 symbol

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x20 schematic**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf.schematic.svg
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x20 schematic

**gf180mcu_fd_sc_mcu9t5v0__clkbuf_x20 layout**

.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_20.layout.png
    :alt: gf180mcu_fd_sc_mcu9t5v0__clkbuf_x20 layout


| CLKBUF_X20 is a clock buffer with 20X drive strength

|
| Attributes

============= =======================
**Attribute** **Value**
area          174.988800 µm\ :sup:`2`
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


.. image:: gf180mcu_fd_sc_mcu9t5v0__clkbuf_20.png


| PIN CAPACITANCE (pf)

======= ======== ====================
**Pin** **Type** **Capacitance (pf)**
I       input    0.0549
======= ======== ====================

|
| DELAY AND OUTPUT TRANSITION TIME corresponding to min slew and load

+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| **Input Pin** | **Output** | **When Condition** | **Tin (ns)** | **Out Load (pf)** | **Delay (ns)** | **Tout (ns)** |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(LH)         | Z(LH)      | default            | 0.0100       | 0.0010            | 0.1394         | 0.0251        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+
| I(HL)         | Z(HL)      | default            | 0.0100       | 0.0010            | 0.1296         | 0.0232        |
+---------------+------------+--------------------+--------------+-------------------+----------------+---------------+

|
| DYNAMIC ENERGY

+---------------+--------------------+--------------+------------+-------------------+---------------------+
| **Input Pin** | **When Condition** | **Tin (ns)** | **Output** | **Out Load (pf)** | **Energy (uW/MHz)** |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(LH)      | 0.0010            | 2.2908              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+
| I             | default            | 0.0100       | Z(HL)      | 0.0010            | 3.3937              |
+---------------+--------------------+--------------+------------+-------------------+---------------------+

|
| LEAKAGE POWER

================== ==============
**When Condition** **Power (nW)**
!I                 0.8415
I                  0.8275
================== ==============

