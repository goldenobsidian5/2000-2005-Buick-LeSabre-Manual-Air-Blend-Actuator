# 2000-2005 Buick LeSabre Manual Air Blend Actuator
3d-printable modification for the cabin air conditioning system for the Buick LeSabre (years 2000 - 2005). Replaces the automatic computer controlled air blend door actuator with a manual lever.

So far I've only done the driver side.

This mod may also fit other GM HVAC systems, and may not fit your buick. Everything written in this doc is intended for the specified make/model/year range. Mileage may vary.

Please reach out to me if you do genuinely use this in some capacity, simply because I think that's really cool! You drive a nice car.


# Why might I need this?
If you've found that your Buick has lost the ability to change what temperature air comes out of the vents, there is a chance that the Air Blend Door Actuator (part # 604-111) isn't responding (or behaving abnormally) to the Climate Control Module (CCM). In other words, when you change the temperature in your car's vents, the motor responsible for turning the Air Blend Door may be stuck and unresponsive. If all else fails, you can remove this motor, and replace it with this 3d print.


# What other things can I do?
Personally, when my car had this issue, I replaced the CCM, replaced the Air Blend Door Actuator, and (this is unnecessary for some, but my AC compressor clutch was failing) replaced the AC compressor / evaporator / filter kit. None of these fixes helped my issue, but it might be worth for you to try as a proper fix before resorting to this option. My issue is that to this day, when properly connecting everything, my actuators will always turn all the way to the "hot air" position, and then stop moving indefinitely. I do not know why they do that, so I made this to replace one of them.
Also, something else I did for a while before creating this print was to mantually set the actuator to the "hot air" position. Then, during the winter, I installed the motor without plugging it in to get hot air in the cabin. During the summer, I removed the actuator, and gravity naturally helped the Air Blend Door to fall/stay towards the "cold air" position. I still have to set the CCM to a low temperature in order for the compressor to run, or, I can set it to a high temperature if I do not want the compressor to run, which sometimes helps with defrosting the windshield. I still do this with the passenger side.


# How do I build this?
## IMPORTANT:
My 3d printer has a tolerance of about 0.25mm, meaning each feature is over-extruded by about that much. Your printer may be different. My final build ended with each joint being pretty sloppy, and socket that attaches to the air blend door was a TIGHT fit. If you're CAD savvy, I made this using Fusion 360 and can provide the source files if wanted, that way you can customize it for your printer's tolerances.

Anyways:
1. Optionally, look at the `FULL BUILD.stl` file to see how the construction should look at the end.
2. Print each file one of the remaining files separately or all at once depending on printer.
3. Use small (2.5mm x 1mm) zip ties to ensure each joint does not separate. Use the images below to see how to secure each zip tie.

Here's 3 images showing the finished product, in its 3 different states.
The rightmost component is what will attach to the Air Blend Door Knob inside the dashboard, replacing the actuator.
The "top" side of this mechanism is on the right of the images, as it lays on it's side.

Cold (60°F):
![Cold air](https://github.com/user-attachments/assets/509864ff-276a-4aec-baca-f5ad1b1e467b)

Medium:
![Medium air](https://github.com/user-attachments/assets/6975f752-4f5a-40f5-a843-ae95530c0a96)

Hot (90°F):
![Hot air](https://github.com/user-attachments/assets/04dce315-278d-4859-9a42-dfdb36c186ec)


# How do I install this?
Driver side:
1. Remove the kicker panel above the gas/brake pedal. There is a light as part of the wiring harness you will need to remove from this panel. _Please note that you will not be able to re-install this panel, it would block access to my manual lever._
2. Locate the Air Blend Door Actuator. Disconnect it and route the cable so it does not dangle. Uninstall the 2 bolts with a 7/32 (preferred) or 6mm socket, and a small wrench.
3. Optionally, ensure the keyed Air Blend Door Knob is tilted towards the front (in the same direction as the car's wheels), in my car this was for cold air. Consider the orientation of the flat keying of the knob.
4. Press fit the new 3d printed keyed actuator onto the knob, and let gravity dangle the rest of the mechanism downward.
5. Optionally, mount the `base.stl` to something rigid. I did not do this, and the mechanism still works as intended, but a lot more finnicky.

Usage:
Gravity will naturally push the mechanism towards the "Cold" position. This is why there are dovetails to keep the lever in place with the help of gravity. To adjust, free the handle from the dovetail, turn it to the desired temperature, then re-secure.
For hot air, move the lever down.
For cold air, move the lever up.

A demo of how the components will move:
https://youtube.com/shorts/TcRUgjRJ4LY

If the tiny dovetail joints slip and the door is free to rotate, the Cold position is the (for me) what my vehicle falls back to. To prevent the dovetail joint from slipping, an aidditional ziptie can be secured around both the lever handle and the 3 rigid levers on the `base.stl` to ensure that your heat is guaranteed to work during the winter. Alternatively, you can omit that ziptie, and if your suspension hasn't rusted out too much yet, the mechanism will reliably stay in place if not kicked. This is especially useful during Spring and Fall, when it's cold in the morning and hot in the afternoon, because the temperature adjustment lever can be reached from the driver's chair while the vehicle is not in motion.
If the dovetail joints break, superglue may work to repair it, or you can still use the ziptie method. Perhaps a rubber band for sustainability.

The Air Blend Door Actuator:
![Actuator](https://github.com/user-attachments/assets/8eb230c6-63cc-4188-bef8-a850cb24fcd3)

The finished product, installed and in the top "Cold" position:
![Zoomed in](https://github.com/user-attachments/assets/10a9d825-9148-40a0-96b2-55d14ad71843)

A zoomed out view. It's harder to see the mechanism, but this shows an overall relative view of where everything sits. The camera is on the driver floorboard, looking up and to the right:
![Zoomed out](https://github.com/user-attachments/assets/4212a940-bf58-4f05-8c4b-014694dbe75a)


# What about the passenger side?
My car has individual driver-passenger climate control via buttons on the passenger door that shift the driver's setting up or down a few notches. This means that there are 2 Air Blend Door Actuators that need to work, and 2 Air Blend Doors to actuate. If your car only has one, you can still use this print if it's on the driver's side. If not, or if you have 2 like me, then there's an actuator hidden behind the glove box. I have not made a 3d printable manual actuator to replace this one, because in my opinion, the bolts are easy enough to get to that I prefer to just manually fix it twice per year when the seasons change, especially if you commute alone for short distances. The least I can do is offer the source Fusion 360 files which can be converted into a smaller passenger side version. Please note that the knob may not be in the same orientation as the driver side in your vehicle.
