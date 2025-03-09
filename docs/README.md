# Voltage doubler

I've copied the schematic from [LT1054.pdf](LT1054.pdf) for easier manufacturing. The design is on page 17, Figure 20.

Everything is the same except 2uF cap is replaced with 2u2 since on mouser it was easier to find 2u2.

The idea behind this is just to double the voltage from input, for my use case it's 9V power supply for guitar pedals,
to double the voltage and get bigger headroom.

There are commercial products available, cheapest that I saw was 35€. I think with a bit of time and 5€ of components,
you can make it yourself. And I did that on protoboard first, then soldered on breadboard. But since I want to attach
IO barrel jacks to the board and 3D print the case, I think it will be neater with manufactured PCB.

The idea is first found on this [link](https://aionfx.com/project/18v-voltage-doubler-bypass-module/), but I've just
taken the IC and found the schematic there, adopter the capacitor and that's it.

From my experiment, this gives 17.52V output.

A presumption is that you're using quality power supply, since this just doubles whatever you give it (according to
specification).

---

Center negative, J1 and J2.

| barrel connector | function                        |
|------------------|---------------------------------|
| A                | (B) - barrel tip/center pin, V+ |
| B                | (J) - jack/switch terminal      |
| C                | (S) - sleeve - ground           |

But since we're using center negative, we'll swap A and C, B is unconnected.

---

Casing should be for 1590LB 50.5x50.5x31mm

https://www.thingiverse.com/thing:6540997

---

TODO test and add LED, check the voltage drop