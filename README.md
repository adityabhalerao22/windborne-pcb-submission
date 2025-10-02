# windborne-pcb-submission
PCB submission for Windborne challenge

The objective of this project was to create two Photodiode Transimpedance amplifier circuits to read incoming signals coming from two different diode lasers (one being a 632.8 HE-NE laser)
The initial gain settings for the TIA circuit were 10, 100 and 1000 V/V but were later modified to 10k, 110k and 1M V/V. The output from the TIA circuit should meet the following specifications:
Gain: 10k, 110k and 1M V/V.
Voltage output:  > 2V

TIA_documentation_Windborne.pdf is a snippet (part of a project) that contains the documentation, including schematic, simulation, layout, and testing for the Photodiode Transimpedance amplifier circuit. There are also three JPEG/PNG files that contain the final PCB layout, schematic, and test setup (though the document is a must-read!).

The coolest part of the design is that the photodiode and the amplifier circuitry are squeezed onto a small board, with the photodiode centered with ultra-short traces into the TIA input. This minimizes parasitic capacitance and inductive pickup in a very simple way, whereas most modules have a completely separate amplifier board with SMA connectors. 
Another really cool design part is the variable gain feature is done using solder pads, which makes the soldering board even less complex without unnecessary analog switches or programmable gain op-amps.

Name - Aditya Bhalerao
Contact - aditya.b.mobile@gmail.com
