# Challenge

Configure the **blue** and **green** pins of the on-board RGB LED and update the main loop to toggle all three in a sequence: red, wait, green, wait, blue, wait, repeat.

> [!NOTE]
> **HINT 1**
>
> The RGB LED is fully wired to `GPIOA`: red on pin `24`, green on pin `23`, blue on pin `22`.

> [!NOTE]
> **HINT 2**
>
> Don't forget to set the pin muxes for the new pins in `BOARD_InitPins()` in `board.c`. GPIO initialization alone won't drive the pad until its port mux is set to `kPORT_MuxAsGpio`.
