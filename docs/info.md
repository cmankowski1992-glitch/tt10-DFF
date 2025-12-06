<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A D flip-flop is a digital storage architecture that captures the value on its data input at the moment of a clock edge and holds that value at its output until the next clock edge. The data input comes from the input pin and is stored in the output until the input changes again.

## How to test

D_n | Q_n | Q_(n+1)
D_n = 0 | Q_n = x | Q_(n+1) = 0
D_n = 1 | Q_n = 0 | Q_(n+1) = 0
D_n = 1 | Q_n = 0 | Q_(n+1) = 1
D_n = 1 | Q_n = 1 | Q_(n+1) = 1
D_n = 0 | Q_n = 1 | Q_(n+1) = 0


