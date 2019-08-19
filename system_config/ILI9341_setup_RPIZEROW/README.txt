Compilation
Source for the driver is here
https://github.com/juj/fbcp-ili9341

According to the SNAPONAIR Schematic diagram the compiling line should be 

cmake -DILI9341=ON -DGPIO_TFT_DATA_CONTROL=24 -DGPIO_TFT_RESET_PIN=25 -DSPI_BUS_CLOCK_DIVISOR=6 ..


