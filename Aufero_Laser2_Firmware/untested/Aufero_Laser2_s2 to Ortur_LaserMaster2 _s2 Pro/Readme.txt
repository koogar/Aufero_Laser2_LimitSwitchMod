WARNING UNTESTED!!!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!



https://forum.lightburnsoftware.com/t/limit-switches-at-aufero-laser-2/58224/39?page=2

wrighizilla
Chris

1
17 Apr
the solution to solve the problem of negative numbers and limit switches on the Aufero 2 is very simple: you have to transform the Aufero 2 into an Ortur laser master 2 pro.
to do this download the LM2 firmware and rename it exactly with the name of the Aufero2.bin firmware
load it and from the console you will stop having an Aufero 2, the machine will be recognized as an ortur laser master 2 pro which already has the limit switches and all the pre-set settings for them.

until then I was using the fake solution of the G92 X0 Y0 macro which works but not perfectly, besides having to be loaded every time before working.

it is not a solution invented by my cousin, it was the ortur technicians who gave it to me when, after much insistence, I explained that I did not intend to drag the carts by hand even on an entry level machine and it is my full right to be able to configure the machine to my liking with homing on top left as to have the full working area accessible to put wood without having the X-bar placed out front to get in the way