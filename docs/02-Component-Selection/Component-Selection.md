---
title: Component Selection
---

### Style 2

**Thermistor / Thermometer**

1. LM35DZ/NOPB Thermometer

    ![](Thermo1.png)

    * $1.67/each
    * [LM35DZ/NOPB](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366](https://www.digikey.com/en/products/detail/texas-instruments/LM35DZ-NOPB/32489?)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

2. SNS-DHT11 Thermistor

    ![](Thermo2.png)

    * $1/each
    * [SNS-DHT11](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940](https://www.digikey.com/en/products/detail/olimex-ltd/SNS-DHT11/21662551)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
