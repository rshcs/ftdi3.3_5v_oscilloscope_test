## ftdi3.3_5v_oscilloscope_test
 Test FTDI converter 3.3v and 5v

---
Testing has been done for the following converter
![FTDI Converter](https://i.ibb.co/hHMjF5D/ftdi.jpg)

---
Test: Sent the String "Hello" through the converter while its Tx and Gnd pins connected to an oscilloscope.

---
Measurement with selector position at 5v:
![FTDI 5v test](https://i.ibb.co/HnSvXqr/5v-2.png)
 
---
Measurements with selector position at 3.3v 
![FTDI 3.3v test](https://i.ibb.co/GsHSM4J/3-3v-2.png)

---
Results and Conclusion:
* **Tx line logic level reduced selector at 3.3v position**

* **Gnd to 5v voltage was measured using digital multimeter result around 4.9v regardless of the selector position (3.3v or 5v).**

* **Safe to use this converter for interfacing devices which has 3.3v logic levels. However the interfaced device has to use a seperate 3.3v power supply (with Common Gnd as usual).**

* **Rx line not connected/ Tested**