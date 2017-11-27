As a part of course curriculum, we have implemented CORDIC algorithm on FPGA to generate desired phase shift in input wave.<br/>
Sine wave input to FPGA on Spartan-3E board has been taken with help of onboard ADC. Since, this ADC communicates with FPGA through SPI protocol, we have developed the code taking care of all timing requirements. This code has also incorporated the settings of pre-amplifier since it has to be used in conjunction with ADC.<br/>
Then we have implemented our algorithm to produce desired phase shift.<br/>
Finally we have used onboard DAC and write code according to its timing requirements and its SPI protocol.<br/>
More details about implementation and algorithm can be found in this report.
