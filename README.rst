
Error Calculations
------------------

Voltage Divider:
100KOhm +/- 0.1%, 75PPM/C (-40C -> 80C)
100KOhm +/-
Max: 100100.08008
min 99899.92008


Voltage Reference:

Min @ 20C: 2.495
Max @ 20C: 2.505

Temp Coef: 75PPM/C

Max Temp Err @ -40C: -11.228mV
Max Temp Err @ 80C: +11.272mV

Min @ -40C: 2.4837725 => -16.227mV error
Max @ +80C: 2.5162725 => +16.272mV error



Temperature Calculations
------------------------
The only part that dissipates enough energy to matter is the current sense
resistor.


Max Power Consumption
---------------------

*Current Sense:*

Resistor:
R_sense = 7mOhm
A_max = 6A
P_max = 252mW

Amp:
V_max = 72V
A_max = 190uA
P_max = 14mW


*Voltage Reference:*

Ref In:
REF_Z_in = 250kOhm
REF_V_in = 2.5V
REF_A_in = 10uA
REF_P    = 25uW

Resistor:
R_bias = 82kOhm
V_max = (30V - 2.5V)
P_max = V_max^2/R_bias => 9.2mW

Reference:


Total:



*Voltage Divider:*
1/6 Voltage Divider Network

Calculations:
R_eq = 120K
V_max = 30V
P_max = V_max^2/R_eq => 7.5mW



Parts List
----------

+----------+------------+---------------------------+---------------------+
| Quantity | Designator | Description               | Mouser SKU          |
+----------+------------+---------------------------+---------------------+
| 1        | U1         | Current sense amplifier   | 700-MAX4081SASA     |
| 1        | R1         | Current sense resistor    | 71-WSL20107L000FEA  |
| 1        | R2         | 1/6 voltage Divider       | 71-TNPW0805100KBEEA |
| 1        | R3         | 1/6 voltage Divider       | 71-TNPW080520K0BEEA |
| 1        | U2         | Voltage reference         | 584-ADR5041WBRTZ-R7 |
| 1        | R4         | Voltage reference bias    | 71-TNPW080582K0BEEA |
| 2        | J1/J2      | 2 pin terminal receptacle | 710-691311500102    |
| 2        | -          | 2 pin terminal plug       | 710-691351500002    |
| 1        | J3         | 3 pin terminal receptacle | 651-1926028         |
| 1        | -          | 3 pin terminal plug       | 651-1911978         |
+----------+------------+---------------------------+---------------------+




RAW
---
30V Max
12V/24V

+/- 6A
5/12/24 V Input


<= 1mA Power



V

5V -> 5A
0V -> -5A

Mount
-----
http://www.mouser.com/Search/ProductDetail.aspx?R=1201578virtualkey65100000virtualkey651-1201578


Current Sense
-------------

Calculations:

Resistor:
R_sense = 7mOhm
A_max = 6A
P_max = 252mW

Amp:
V_max = 72V
A_max = 190uA
P_max = 14mW

Ref:
REF_Z_in = 250kOhm
REF_V_in = 2.5V
REF_A_in = 10uA
REF_P    = 25uW


Parts:
7mOhm: http://www.mouser.com/ProductDetail/Vishay-Dale/WSL20107L000FEA/?qs=sGAEpiMZZMtlleCFQhR%2fzb7jD%252buUxQm7%252biyfvAJP1Wo%3d
Amp: http://www.mouser.com/ProductDetail/Maxim-Integrated/MAX4081SASA+/?qs=sGAEpiMZZMutXGli8Ay4kB5dsh5iKl6TTQwfiqPU9w4%3d

Resistor: 500mW

-6A -> 0V
 0A -> 2.5V
+6A -> 5V

1mV out -> 2.4mA



Voltage Reference
-----------------
Bias: 82kOhm

Needs 60uA + 10uA: 70uA

(30-2.5)/80e3 -> 335uA
(12-2.5)/80e3 -> 115uA

REF_P_max = 9.2mW


Parts:
Ref: http://www.mouser.com/ProductDetail/Analog-Devices/ADR5041WBRTZ-R7/?qs=sGAEpiMZZMuBck1X%252b7j9fJ909qbP0fXHMqaADQNAzbA%3d
Bias: http://www.mouser.com/ProductDetail/Vishay/TNPW080582K0BEEA/?qs=222842oYAD9vR9R%252b93yFkQ%3d%3d



Divider
-------
1/6 Voltage Divider Network

Calculations:
R_eq = 120K
I_max = 250uA
P_max = 30mW

Parts:
100K: http://www.mouser.com/ProductDetail/Vishay/TNPW0805100KBEEA/?qs=sGAEpiMZZMtlubZbdhIBIFsxO9oIeGFUmiF5Rz3MCQ8%3d
20K: http://www.mouser.com/ProductDetail/Vishay/TNPW080520K0BEEA/?qs=sGAEpiMZZMtlubZbdhIBINl7pLegQti%252bok6yVk5rPfc%3d

25 PPM / C
0.1 %
125 mW (1/8 W)
150 V




Connectors
----------
3 Pin
Receptacle: http://www.mouser.com/ProductDetail/Phoenix-Contact/1926028/?qs=sGAEpiMZZMvPvGwLNS671zZvyVWS49C%252bmTXXxhDGUDA%3d
Plug: http://www.mouser.com/ProductDetail/Phoenix-Contact/1911978/?qs=sGAEpiMZZMvPvGwLNS6718PaoTt7FM7cq6nTDRCep18%3d

2 Pin
Receptacle: http://www.mouser.com/ProductDetail/Wurth-Electronics/691311500102/?qs=sGAEpiMZZMvPvGwLNS6715pX%252bQgp6lhzG3N%2f9nisyspwto99zh4GxQ%3d%3d
Plug: http://www.mouser.com/Search/ProductDetail.aspx?qs=7gQLVZk5cPkg%2frpRGyiXgA%3d%3d
