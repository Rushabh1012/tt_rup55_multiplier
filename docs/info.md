<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project implements a 4-bit multiplier. Two 4-bit inputs are taken from ui_in[7:4] and ui_in[3:0] and the 8-bit product is generate and sent out to uo_out[7:0].

## How to test

Apply two 4-bit input values to ui_in, A and B, to ui_in[7:4] and ui_in[3:0] respectively. Enable the design using ena, release reset using rst_n and verify that uo_out shows the correct 8-bit multiplication result.

## External hardware
No external hardware is required for this project.


