# freeDSPx AES/SPDIF IN

This is a digital input add-on board based on a design found at [latent laboratories](http://www.latentlaboratories.com/dsp-01/). It's built around a CS8422 asynchronous sample rate converter, has S/PDIF and AES/EBU input plus two potentiometers, a toggle switch and a LED connected to the ADAU's GPIOs.

## Comments

* The pin distance of the input transformer is a little narrow. However, it fits with a little bending. 
* The design uses the bit clock signal of the serial output as master clock for the ASRC. Therefore, the output needs to be configured in SigmaStudio as ‚Master Mode‘. The BCLK frequency needs to be selected as ‚internal clock/4‘.

## License

This work and all other materials under https://github.com/freeDSP are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/legalcode">Creative Commons Attribution Share-Alike 4.0 license</a>. This allows for both personal and commercial derivative works, as long as they credit freeDSP and release their designs under the same license. 
