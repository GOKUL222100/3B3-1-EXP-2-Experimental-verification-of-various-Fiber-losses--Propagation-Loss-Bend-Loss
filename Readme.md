EXPERIMENT-2-OPTICAL-COMMUNICATION
🔍 EX.NO: 2 – Verification of Fiber Losses
Aim:
To measure propagation and bending losses for two wavelengths in plastic fiber.

Equipments Required:

Link-B Kit
Patch chords
Oscilloscope
Function Generator
Fiber cables
Theory:

Optical Fibers are available in different variety of materials. These materials are usually selected by taking into account their absorption characteristics for different wavelengths of light. In case of Optical Fiber, since the signal is transmitted in the form of light which is completely different in nature as that of electrons, one has to consider the interaction of matter the radiation to study the losses in fiber.

Losses are introduced in fiber due to various reasons. As light propagates from one end of Fiber to another end, part of it is absorbed in the material exhibiting absorption loss. Also part of the light is reflected back or in some other directions from the impurity particles present in the material contributing to the loss of the signal at the other end of the Fiber. In general terms it is know as propagation loss. Plastic Fibers have higher loss of the order of 180 dB/Km. Whenever the condition for angel of incidence of the incident lights is violated the losses are introduced due to refraction of light. This occurs when fiber is subjected to bending. Lower the radius of curvature more is the loss. Other losses are due to the coupling of Fiber at LED and photo detector ends.

Procedure:
 Connect the power supply with proper polarity to the kit link-B and switch it on.  Keep all Switch Faults in OFF position.  Keep switch SW8 towards TX position.  Keep switch SW9 towards TX1 position.  Keep Jumper JP5 towards +12V position.  Keep Jumpers JP6, JP9, JP10 shorted.  Keep Jumper JP8 towards sine position.  Keep Intensity control pot P2 towards minimum position.  Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog Buffer.

image
 Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.  Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.  Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.  Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.

image
 Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.  Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.

image
 If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]

Where a = nepers/ Meter L1 = Fiber Length for V1 L2 = Fiber Length for V2 This a is for peak wavelength of 660nm  Keep switch SW9 towards TX2 position.  Keep Jumper JP7 towards +12V position.  Remove fiber cable from SFH756V (660nm) & SFH350V and insert one meter fiber between SFH450V (950nm) & SFH350V.  Observe the detected signal at post ANALOG OUT on oscilloscope.

image
 Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.  Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.  If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ] Where a = nepers/ Meter L1 = Fiber Length for V1 ; L2 = Fiber Length for V2 This a is for peak wavelength of 950nm  Compare the two a values.

MEASUREMENT OF BENDING LOSSES:  Remove fiber cable from SFH450V (950nm) & SFH350V and insert one meter fiber between SFH756V (660nm) & SFH350V.  Bend the Fiber in a loop. Measure the amplitude of the received signal.  Keep reducing the diameter of bend to about 2 cm & take corresponding out voltage readings. (Do not reduce loop diameter less than 1 cm).  Plot a graph of the received signal amplitude versus the loop diameter.

Tabulation:

Propagation Loss
[WhatsApp Image 2026-03-23 at 2 15 00 PM](https://private-user-images.githubusercontent.com/142885740/567615811-3068408d-1a15-4aee-871f-6ce106252036.jpeg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzQ1NTE5ODAsIm5iZiI6MTc3NDU1MTY4MCwicGF0aCI6Ii8xNDI4ODU3NDAvNTY3NjE1ODExLTMwNjg0MDhkLTFhMTUtNGFlZS04NzFmLTZjZTEwNjI1MjAzNi5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI2MDMyNiUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNjAzMjZUMTkwMTIwWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NGFlM2FiN2ZiMzE5ZTZlNDhjMzc5ZmQ1ODg4MWIyZWIwZjVjNDM1YmIzZTJiMzBlYzdlMmE3MGRlMDA0ZjQ1NiZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.EU2tv3_2gY22phuupJ7thWRFeKa0-ZHImFFRDsqhCic)

Bending Loss
[WhatsApp Image 2026-03-23 at 2 14 59 PM](https://private-user-images.githubusercontent.com/142885740/567615892-06b47055-d7b2-4abd-843e-006f943eaece.jpeg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzQ1NTE5ODAsIm5iZiI6MTc3NDU1MTY4MCwicGF0aCI6Ii8xNDI4ODU3NDAvNTY3NjE1ODkyLTA2YjQ3MDU1LWQ3YjItNGFiZC04NDNlLTAwNmY5NDNlYWVjZS5qcGVnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI2MDMyNiUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNjAzMjZUMTkwMTIwWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9MDJmN2I2YTc5OWVhOTJjM2EwYTZkYTUwNWNmZGU4NmVhZDJkM2JiZjUzMWY5NTI1MWU5MzY1ODFlMWNkZjc2MCZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.WxwlZUA37x_yY9FvPeREgf3RBh2Jx4huaUbEDw8uzrE)

Result:
Attenuation and bending loss characteristics verified.

