## Electronic Development

For this assignment I learnt how to create a custom PCB and make an ISP board.

### PCBs

The blank PCBs are made from a piece of temperature-resistant material like [FR-4](https://www.mclpcb.com/blog/fr4-guide/) and [FR-1](http://www.bestpcbs.com/blog/2016/08/whats-the-difference-for-fr1-fr2-fr3-and-fr4-materials/) and a thin layer of copper on top.

By milling away some parts of the copper layer we are able to create pathways for thr current to flow without creating shorts.

Other methods include etching using a ferric chloride solution and an image exposure method.

### Creating the ISP board

The traces used for the circuits and board size were taken from [Mr Chew's website for EP1001](https://skeatz.github.io/Further-DF-and-Prototyping/files/03-electronics-prod.html). Using the mods from his site, I was able to generate the gcode needed for the Stepcraft miling machine.

![Milling the ISP board]()

After milling the board I had to "stuff" the board, meaning I had to place the components and solder them in place. The parts for PCBs are very small, with LEDs and resistors measuring just a few millimeters in size, if not less. It took a lot of patience and fumbling with the tiny parts and tweezers before finally soldering them in place.
