# 2026/11/07 (First) Flight Event Debrief
We met on Saturday November 7th, 4pm, at the  <a href="https://maps.app.goo.gl/XdYiqzcfiGTVXW6o7">Silver Lake Recreation Area</a>.
There was approximately about 20 people in attendance from GTLUG and GTAS.

Weather was clear and sunny, around 40-50℉   Wind was <10mph.

We brought two, nearly identical, rockets: labeled "A" and "E".  Made from the same Quest Courier "egg lofter" kit.

Our primary objective for this event was answering the basic question: "Can we even get off the launch pad?"

We performed three launches.  In summary, we tested the following:
1. Rocket "E", fully integrated assembly with T-Beam supreme.  Using A8 engine.
2. Rocket "A", full integration except no telemetry module.  Using A8 engine.
3. Rocket "A", full integration except no telemetry module.  Using C6-7 engine.

We brought 6x of each of these engines (ordered by capacity)
1. A8-5
2. B6-4 (never fired)
3. C6-7

## Pre-Flight (on location)
This was the first time that we were able to fully integrate all of the components.

We did collect weight in grams (coming soon) of the fully integrated assemblies.  This will be useful for the next event (foreshadowing).

On location, we visually inspected the spectrum centered around 915MHz before powering on telemetry modules,
ti establish some baseline expectations.  The visible bandwidth appeared relatively clear of artificial noise.

With the telemetry enabled, we were able to identify the telemetry signal.  Using our 900MHz Yagi-Uda directional,
we were able to orient the antenna in an orthogonal direction approximately 25 feet away from transmitter, and still
recognize the signal, albeit lower in strenth.

## 1st Attempt
On the very first flight attempt, we used Rocket "E" in a fully integrated assembly, including telemetry unit "A".

We oriented the launch pole approximately 5° off vertical in the opposite direction of wind.

We used an A8-5 engine.  Granted it is the lowest capcity engine, 8 Newtons is the highest thrust engine we brought.

The rocket did get off the launch pad, but only barely and landed only a few feet away from the launch pad.
The engine finished its first phase on the ground.  The rocket was left to trigger its 
report phase while resting on the ground.  This appears to have caused one of the fins to break.
The single fin is beyond repair.  The rest of the rocket is in great condition and is likely reusable.

Telemetry IGC file coming soon.

We also used our radio capture stack (Yagi-Uda, HackRF, SDR++, etc.), we captured a base-band IQ WAV recording of the 
telemetry radio signal centered on 915MHz (±10MHz bandwidth).  This was captured starting during countdown (on "3"),
and was stopped immediately after the rocket landed on the ground, before the report phase fired.
This RF WAV capture will be made available, coming soon.

## 2nd Attempt
On the second flight, we had to switch to Rocket "A".  Testing using the same configuration of variables
as the 1st attempt would NOT be valuable.  Because 8 Newtons was the highest thrust value we had,
the next logical step (given F=ma) we had to change the mass of the rocket.

Because we still wanted to test the aerodynamics of the nose-cone and kit integration, we removed
the telemetry module.  We weren't actually capturing real-time telemetry anyway.

For this test, we tested again with an A8-5 engine.  This time the rocket made it several feet above the 
launch pade before the first rocket phase ended.  It seemed that there was just moderate (not large)
thrust, but perhaps just not enough of it.

To avoid rapid unplanned disassembly like the 1st attempt, the rocket was hazardously lifted 
**before** the report phase could fire and possibly wreck another fin.

Because the telemetry module didn't fly, no data will be available for this flight or the 3rd.

## 3rd Attempt
On the 3rd attempt, we used Rocket "A" again.  Because the 2nd attempt seemed to have enough thrust
but perhaps just not long enoguh; we decided to go straight to C6 engines.  Specifically, we used
a C6-7.  It has only 6 Newtons, rather than the 8N used in the 1st and 2nd attempts, so having no
mass calculations, it was a risk not having enough thrust to launch again.  Still, the hypothesis
was that perhaps it would still be just enough, and burn for long enough.

We reoriented the launch pole vertical.

This was a successful launch initially.  It traveled approximately 100 feet into the air 
before reaching apogee.  Unfortunately, due to the long 7 second delay before report phase 
(which was probably designed for a much lighter mass rocket traveling to higher altitudes),
our rocket didn't have enough time to fire its report phase, before nosediving (AKA lawn-darting).

This report phase failure and crash resulted in another broken fin, and damaged nose-cone.

Because our test articles were beyond immediate repair, we had to terminate our testing.

## Preliminary Conclusion
We've clearly established that 8 Newtons of thrust isn't enough to lift a fully assembled rocket.

We need to take our captured mass information (coming soon), and determine the correct amount of thrust, 
and try to source engines that meet that minimum.  This may require special online ordering, rather than
simply going to a retail store (i.e. Meijer, Walmart, Hobby Lobby, etc.) to purchase them.

We did capture radio signal and onboard telemetry from the first flight, which does contain meaningful data.
All of this will be published and can be analyzed further.  Note for later: https://github.com/abbbi/igcviewer

We need to replace a fin each for both rockets.  Given we have 2D scans of the fins in their cutout, 
immediate options for replacement considered are:
1. 3D print, which is readily available, and more rigid
2. Laser cut, which is how the previous fins were constructed

Going forward we will target these goals:
* More data will be collected and published.
* We will try to learn from the data collectedd.
* We will continue working on telemetry decoding.
* We will plan on having another launch event in early 2027.  Stay tuned to [this GitHub repository](../../) and our
[main website](https://gtlug.github.io/) for the latest schedule.
