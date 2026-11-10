# Assignment7_NaySanHtut

# Electric and Magnetic Field Classes

Two C++ classes, `Electric_Field` and `Magnetic_Field`, each storing a 3D vector in a dynamically allocated array of 3 doubles. Both provide constructors, getters/setters, and `calculateMagnitude()`. The electric class adds `innerProduct()`, and the magnetic class adds `calculateUnitVector()`.

## Files

- `main.cpp`: class definitions and test driver

## Build and Run

```
g++ -std=c++11 -o main main.cpp
./main
```

## Output

```
===== Electric Fields =====
E_default    = (0, 0, 0)
  Magnitude   : 0
  Inner product (E.E): 0

E_components = (100000, 10.9, 170)
  Magnitude   : 100000
  Inner product (E.E): 1e+10

E_setter     = (3, 4, 12)
  Magnitude   : 13
  Inner product (E.E): 169

===== Magnetic Fields =====
B_default    = (0, 0, 0)
  Magnitude   : 0
  Unit vector : (0, 0, 0)

B_components = (0.002, 0.0005, 0.001)
  Magnitude   : 0.00229129
  Unit vector : (0.872872, 0.218218, 0.436436)

B_setter     = (0, 3, 4)
  Magnitude   : 5
  Unit vector : (0, 0.6, 0.8)
```
