# Description
On March 24th 2026, participants of CSULB IEEE's SOPHEE Program synthesized their nine weeks of MCU discussions and hands-on circuit building to assemble an embedded circuit. The circuit simulated a traffic light that receives input and triggers an output. The circuit is idle until an object covers light from a sensor, which triggers an external interrupt. The MCU then executes an interrupt service routine by shutting off an indicator LED and communicating with an LED siplay driver through SPI to count down from 9 seconds. After reaching 0, the main program resumes and the indicator light switches back on, along with the LED dot matrix displaying "GO."

> # _[Video Link](https://drive.google.com/file/d/1a24whzxjisXWJCGOHU3sF_clboYWUFuo/view?usp=sharing)_
