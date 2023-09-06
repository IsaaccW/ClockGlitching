# ClockGlitching
Repository for Clock Glitching

Clock glitching is the act of switching a devices clock in hopes of causing it to perform in a way that was unintended. The most common use of the clock glitching is switching a devices clock to a much faster clock, from KHz to MHz and as a result the devices memory bus is then flooded and it may release very important information. For devices with very little security you can also skip instructions by inserting a fault at just the right time. 

There are two different types of clock fault injection synchronous and asynchronous. This means you are either interrupting the devices clock and inserting your own, which is easily identifiable by the deivces security prototcols. The other involves synchronizing both clocks, the device's and the one to be inserted, so that you insert the clock you want and deactivate the devices clock on the same high/low pulse.

I have attached an image of how to obtain the exact clock you want to insert below.

<img width="324" alt="Screenshot 2023-09-06 at 4 30 15 PM" src="https://github.com/IsaaccW/ClockGlitching/assets/65687558/050ecde0-137d-422e-a303-f80e7b4096d2">
