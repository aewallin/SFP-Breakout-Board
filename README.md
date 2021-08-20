# SFP-Breakout-Board
SFP fibre-optical transciever simple breakout board. Works up to at least 1 Gbit/s.

* differential TX+/TX- RX+/RX- outputs/inputs with SMA connectors
* connector and cage for SFP or SFP+ transciever
* +3V3 power for transciever
* Three status LEDs for TX_FAULT, LOS, and MOD_ABS
* jumpers for SFP rate-select settings.

![PCB](SFP_breakout_PCB.png "PCB image")

![Board](doc/20210820_SFPboard.jpg "PCB image 2")

![SA](doc/2021-08-20_SFPboard_tx_to_rx_2boards.png "Spectrum analyzer")

Spectrum analyzer measurement of tracking-generator output to Tx-board with SFP, short 2 m fiber, and RX-output of receiving board with SFP. Bandwidth up to ca 1.8 GHz.

See also these other similar projects:

* https://github.com/aewallin/SFP2SMA_2018.03  single-ended input/output, with op-amp and transformer coupling to SFP
* https://osmocom.org/projects/misc-hardware/wiki/Sfp-experimenter
* https://osmocom.org/projects/misc-hardware/wiki/Sfp-breakout
* Multi-SFP crate https://www.ohwr.org/project/sfp-plus-i2c/wikis/home
