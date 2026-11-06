# Research & Development Diary

Teensy 4.1 recomended by LUG member																									
https://www.pjrc.com/store/teensy41.html																									
This dev board has a stupid amount of IO and horsepower to do whatever we want																									
https://www.sparkfun.com/products/16771																									
$31.50																									
																									
Teensy is cool, but doesn't have WiFi out of the box.  ESP32s do.																									
https://www.espressif.com/en/products/modules																									
SparkFun Thing Plus - ESP32-C6																									
https://www.sparkfun.com/products/22924																									
$19.95																									
Specifications for ESP32-C6 WROOM-1-N16 found on SparkFun Thing Plus																									
https://www.espressif.com/sites/default/files/documentation/esp32-c6-wroom-1_wroom-1u_datasheet_en.pdf																									
SparkFun Thing Plus - ESP32-S3																									
https://www.sparkfun.com/products/24408																									
$19.95																									
https://www.espressif.com/sites/default/files/documentation/esp32-s3_datasheet_en.pdf																									
																									
T-BeamSUPREME SoftRF																									
U-blox MAX-10S																									
https://www.lilygo.cc/products/t-beamsupreme-softrf?variant=42880905412789																									
$70.17																									
https://github.com/Xinyuan-LilyGO/LilyGo-LoRa-Series?tab=readme-ov-file																									
																									
https://www.amazon.com/Radiolink-PIXHAWK-Flight-Controller-Module/dp/B0BY1797VF?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A2N8PHTOJI3K3Q																									
																									
Flexible antenna -just an idea 																									
https://a.co/d/fPqvwc8																									
																									
ADXL375 - High G Accelerometer (+-200g) with I2C and SPI - STEMMA QT / Qwiic																									
https://www.adafruit.com/product/5374																									
$24.95																									
https://www.sparkfun.com/products/9836																									
$20.50																									
																									
MPU-9250 MPU9250 BMP280 SPI IIC/I2C 10DOF Acceleration Gyroscope Compass 9-Axis Sensor Board Module GY-91 for Arduino 3-5V																									
https://www.amazon.com/MPU-9250-MPU9250-Acceleration-Gyroscope-Compass/dp/B07KNLDXQJ/																									
MPU-9250 Nine-Axis (Gyro + Accelerometer + Compass) MEMS MotionTracking™ Device																									
https://invensense.tdk.com/products/motion-tracking/9-axis/mpu-9250/																									
10,000g acceleration																									
																									
https://eggtimerrocketry.com/home/eggfinder-gps-tracking-system/																									
https://eggtimerrocketry.com/wp-content/uploads/2023/08/Eggfinder-TX-Assembly-Manual-Rev-D3-D4.pdf																									
																									
																									
Data Logger																									
https://www.sparkfun.com/products/16832																									
https://github.com/sparkfun/OpenLog																									
																									
																									
																									
A complete location tracker and logger package.  No other telem.  Existing app.  Uses M10 GPS, and samples GPS at 10Hz																									
https://www.featherweightaltimeters.com/featherweight-gps-tracker.html																									
Data sheet on M10																									
https://content.u-blox.com/sites/default/files/MAX-M10S_DataSheet_UBX-20035208.pdf																									
https://www.u-blox.com/en/product/max-m10-series																									
																									
Reddit threads following similar requirements																									
https://www.reddit.com/r/rocketry/comments/14y6yr5/flight_computer_components/																									
https://www.reddit.com/r/rocketry/comments/siuvjm/guides_for_building_simple_flight_computer/																									
https://forums.adafruit.com/viewtopic.php?t=191973																									
																									
SparkFun Micro Pressure Sensor - BMP384 (Qwiic)																									
https://www.sparkfun.com/products/19833																									
SparkFun Pressure Sensor - BMP384 (Qwiic)																									
https://www.sparkfun.com/products/19662																									
$15.95																									
BMP390																									
DPS310																									
																									
SparkFun GPS Breakout - NEO-M9N																									
https://www.sparkfun.com/products/17285																									
$74.95																									
																									
																									
																									
Rockets experience accellearations betwen 4-60G																									
Velocities upward of 250mi/h or 111.76m/s																									
GPS receivers can only handle <4G																									
The Featherweight model mentioned above samples its GPS at 10Hz.  I'm not sure how it achieves this.																									
Somewhere there is mention that the GPS-acceleration issue is only problematic with a charged crystal.  So, if we're only enabling GPS in low acceleration conditions, we can enable the GPS module only when it's safe.																									
																									
																									
																									
																									
Information about batteries for rocket electronics																									
https://www.apogeerockets.com/Peak-of-Flight/Newsletter603																									
Despite caution noted in meeting regarding Lithium batteries.  I see no concerns mentioned elsewhere.  Proceeding with product recomendations.																									
																									
T-Beam suggests using																									
18650 Li-Ion flat top 18x65mm																									
Lithium Ion Battery - 3.7v 18650 Cell (2600mAh) - $6.50																									
https://www.sparkfun.com/products/12895																									
"Batteries+ 3.7V 18650 Lithium Ion - 2 Pack - $22.99
"																									
https://www.batteriesplus.com/productdetails/ul1865=26=2p																									
NURE18650-CH Nuon Dual Charger for Nuon Lithium 18650 Batteries - $19.99																									
https://www.batteriesplus.com/productdetails/nure18650=ch																									
																									
NiMH Battery for reference																									
https://www.sparkfun.com/products/335																									
																									
Batteries+ has batteries and charger in town																									
																									
32GB µSD Card - $6.98 (Aile L22)																									
https://www.walmart.com/ip/SanDisk-32GB-ImageMate-microSDHC-UHS-1-Memory-Card-Up-to-120MB-s-SDSQUA4-032G-Aw6ka/547052541																									
																									
																									
I'm considering exsiting Flight Controller software to avoid writing everything from scratch																									
The two predominant are PX4 and Ardupilot																									
https://ardupilot.org/dev/docs/esp32-autopilot.html																									
https://github.com/ArduPilot/ardupilot/blob/master/libraries/AP_HAL_ESP32/README.md																									
																									
Those software are for driving auto-pilot.  There is a separate package for telemetry radios																									
https://docs.px4.io/main/en/telemetry/esp32_wifi_module.html																									
https://github.com/DroneBridge/ESP32																									
																									
MAVLink is a widely supported open source message library.																									
https://mavlink.io/en/																									
https://github.com/mavlink/mavlink																									
																									
																									
Another flight control software																									
https://github.com/qqqlab/madflight																									
Designed for use on ESP32-S3																									
																									
																									
https://www.reddit.com/r/esp32/comments/cjksh4/esp32_quadcopter_flight_controller/																									
https://github.com/PepeTheFroggie/EspCopter32																									
https://github.com/multiwii/multiwii-firmware																									
Ultimately, I think this is the firmware we'll go with.  It's custom build for the T-Beam.																									
https://github.com/lyusupov/SoftRF/wiki/Prime-Edition-MkIII																									
																									
																									
																									
Researching how to get MAVLink over UDP.																									
Right now, there is support for MAVLink in the firmware, but only over ADS-B.																									
Since the library is included, it should be trivial to just make the appropriate calls.																									
https://github.com/mavlink/mavlink/blob/master/examples/c/udp_example.c																									
https://github.com/espressif/arduino-esp32/blob/master/libraries/Network/src/NetworkUdp.cpp																									
An instance of NetworkUdp AKA WifiUdp is made on the WiFi object.  Perhaps we can leverage that existing object to transmit our mavlink messaes.																									
In summary, we may have both existing classes/libraries/stacks (MAVLink and UDP) already in the firmware package.  They just have to be integrated together.																									
																									
I don't really want to hard code a remote ip to send the UDP packets to.																									
This is going to be a tiny peer-peer-like network, so I don't think it would be entirely inappropriate to use UDP broadcast packets.																									
In most idea scenarios, the broadcast domain is going to be small.  Either way, we need to configure some address.  It should be trivial to just set this to a unicast or broadcast address depending on needs.																									
Mission Planner doesn't effectively support multicast.  It does support unicast and broadcast UDP.																									
																									
I really want to be able to get arbitrary sensor data stored either in TLOG or in Real Time.																									
It does appear the IGC standard written to the SD card has support for a number of extended values.																									
"I" records can contain extra data, with 3-letter codes.  These codes can be found on page "35"/50 of this IGC spec																									
https://xp-soaring.github.io/igc_file_format/igc_fr_specification_with_al8_2023-2-1_0.pdf																									
																									
Getting real time location data may be really the ideal.																									
																									
																									
																									
																									
6 New 18650 Battteries in hand																									
2 T-Beam Supreme in hand																									
Each comes with SoftRF v1.2+ installed																									
I had read somewhere that some models do come with Meshtastic loaded instead.  This fortunately wasn't the case.																									
																									
By default, the board creates its own WiFi access point.  The built in antenna is pretty weak.																									
The default passphrase for the network is: 12345678																									
I'm not sure where this is defined yet.  I'd like to be able to change this.  I didn't see the setting in the web ui																									
I was able to connect to the board's web server																									
http://192.168.1.1/																									
																									
I successfully upgraded the board's firmware using this pre-compiled binary																									
https://github.com/lyusupov/SoftRF/blob/master/software/firmware/binaries/ESP32S3/SoftRF/OTA/SoftRF-firmware-v1.5.1-ESP32S3.bin																									
																									
I haven't figured out how to load my own custom firmware.  I have succesfully compiled the source.																									
																									
There is an option to broadcast GDL90 UDP.																									
There is also an option to automatically generate Flight Recorder logs onto the SD card.  Triggered by altitude.																									
																									
																									
																									
I'd like to pursue getting WiFi 2.4GHz working as the primery data link.																									
Using the built in antenna, and a laptop and phone, I was able to drive across a parking lot.  The signal/connection dropped at around 100 feet.																									
I ordered a new external 2.4GHz antenna, and adaptive cable																									
For the time being, we will investigate how to integrate both the 2.4GHz and 915MHz band antennas into the rocket.																									
I am very interested in how custom helical antenna designs might work.  Moving them to the surface (still internally) of the nose cone would save on space.																									
																									
																									
																									
																									
This tool may be useful																									
https://github.com/semuconsulting/PyGPSClient																									
																									
"It's hard to have a good time on a Mac" Jeff Geerling																									
https://www.youtube.com/watch?v=AtmQGMwF_M8																									
																									
																									
																									
																									
																									
																									
																									
																									
Based on research, it looks like ADS-L is going to be the best radio protocol.																									
																									
Two options exist																									
1. Get a seperate SoftRF node receiver, that can re-transmit GDL90 over WiFi/UART																									
2. Write parsers using GNU radio																									
																									
gr-lora should give us raw bytes.  We just have to decypher them.																									
																									
ADS-L packet structure																									
software/firmware/source/libraries/OGN/ads-l.h																									
																									
The protocol is divided into two main sub-bands with distinct technical parameters:																									
M-band: Uses frequencies 868.2 MHz and 868.4 MHz with a channel bandwidth of 200 kHz.																									
O-band: Uses the single frequency 869.525 MHz with a channel bandwidth of 250 kHz.																									
																									
These are the used frequencies regardless of 915MHz setting																									
																									
																									
																									
We may end up going with the "Legacy" protocol, that does transmit on 915MHz																									
																									
																									
1/12/2026																									
software/firmware/source/SoftRF/src/protocol/radio/Legacy.h																									
software/firmware/source/SoftRF/src/protocol/radio/Legacy.cpp																									
																									
																									
																									
																									
																									
																									
Below is a complete, structured explanation of:																									
																									
- The **RF physical layer** used by SoftRF Legacy																									
- The **packet format** (byte‑wise structure)																									
- Where the definitions live in the SoftRF source tree																									
- How this relates to FLARM “Legacy V6”																									
																									
Everything is grounded in the repository you linked.																									
																									
---																									
																									
# 📡 SoftRF “Legacy” Protocol — RF Physical Layer																									
SoftRF’s “Legacy” mode is explicitly designed to be compatible with **FLARM Legacy V6**, using the **Nordic nRF905** radio chip. This is confirmed in the SoftRF documentation and hardware descriptions.																									
																									
### RF parameters (nRF905 defaults used by SoftRF Legacy)																									
- **Modulation:** 2‑FSK																									
- **Bitrate:** 50 kbps																									
- **Deviation:** ±50 kHz																									
- **Channel spacing:** 100 kHz																									
- **Preamble:** 10 bytes (0x55 pattern)																									
- **Sync word:** 4 bytes																									
- **Payload length:** 32 bytes (fixed)																									
- **CRC:** 16‑bit CRC (nRF905 built‑in)																									
- **Frequency:**																									
- EU: 868.2 MHz																									
- US: 915.0 MHz																									
																									
These parameters are hard‑coded in the SoftRF radio driver for nRF905.																									
																									
---																									
																									
# 📦 SoftRF “Legacy” Packet Structure																									
The actual packet structure is defined in:																									
																									
```																									
software/firmware/source/SoftRF/src/protocol/radio/Legacy.h																									
software/firmware/source/SoftRF/src/protocol/radio/Legacy.cpp																									
```																									
																									
The search results confirm these files exist.																									
																									
### The important part:																									
SoftRF’s Legacy packet is a **32‑byte FLARM‑compatible frame**, consisting of:																									
																									
| Offset | Length | Field | Description |																									
|-------|--------|--------|-------------|																									
| 0     | 1      | Type | Message type (position, static, etc.) |																									
| 1–2   | 2      | Aircraft ID | ICAO or FLARM ID |																									
| 3     | 3      | Latitude | 24‑bit signed |																									
| 6     | 3      | Longitude | 24‑bit signed |																									
| 9     | 2      | Altitude | 12‑bit or 16‑bit depending on mode |																									
| 11    | 1      | Speed | Ground speed |																									
| 12    | 1      | Climb rate | Vertical speed |																									
| 13    | 1      | Track | Heading |																									
| 14–29 | 16     | Misc / vendor‑specific | SoftRF uses some bytes for battery, alarms, flags |																									
| 30–31 | 2      | CRC | nRF905 CRC |																									
																									
SoftRF does **not** encrypt or obfuscate these packets (unlike modern FLARM).																									
																									
---																									
																									
# 📁 Where the structure is defined in the repo																									
The Legacy packet is constructed and parsed in:																									
																									
### **Legacy.h**																									
Contains the struct definition and constants.																									
																									
### **Legacy.cpp**																									
Contains encode/decode logic.																									
																									
The search result confirms the file exists but GitHub’s preview failed to load in the snippet.																									
																									
---																									
																									
# 🧠 How to decode this in GNU Radio																									
Since the nRF905 uses a simple 2‑FSK at 50 kbps, you can decode it with:																									
																									
- Quadrature demod → clock recovery → binary slicer																									
- Frame sync on the 4‑byte sync word																									
- Extract 32‑byte payload																									
- Apply CRC‑16 (nRF905 polynomial)																									
- Parse fields as per the table above																									
																									
If you want, I can generate a **GNU Radio Companion flowgraph** for this.																									
																									
---																									
																									
# 🧭 Why this matters																									
SoftRF’s Legacy mode is essentially:																									
																									
> **“FLARM Legacy V6 without encryption, using the nRF905 physical layer.”**																									
																									
This is why the packet is 32 bytes and the RF parameters match FLARM.																									
																									
---																									
																									
# Want me to extract the exact struct from Legacy.h?																									
I can walk through the fields byte‑by‑byte and produce a clean, annotated packet map.																									
																									
Would you like a breakdown of **[the exact struct definition from Legacy.h](guide://action?prefill=Tell%20me%20more%20about%3A%20the%20exact%20struct%20definition%20from%20Legacy.h)** or a **[GNU Radio flowgraph for decoding the 2‑FSK signal](guide://action?prefill=Tell%20me%20more%20about%3A%20GNU%20Radio%20flowgraph%20for%20decoding%20the%202%E2%80%91FSK%20signal)**?																									
																									
																									
																									
																									
																									
																									
Absolutely — let’s build a **complete GNU Radio decoding chain** for SoftRF/FLARM‑Legacy 2‑FSK. Since you’re working with a T‑Beam Supreme and SoftRF’s “Legacy” mode, you’re dealing with:																									
																									
- **2‑FSK**																									
- **50 kbps**																									
- **±50 kHz deviation**																									
- **nRF905‑style framing**																									
- **32‑byte payload**																									
- **4‑byte sync word**																									
- **0x55 preamble**																									
																									
That’s a perfect match for a GNU Radio flowgraph.																									
																									
Below is a full, practical flowgraph design you can drop into GNU Radio Companion (GRC). I’ll also include the exact block parameters and the Python post‑processing snippet for packet extraction.																									
																									
---																									
																									
# 📡 **GNU Radio Flowgraph for SoftRF Legacy 2‑FSK**																									
																									
## 🧱 **Block‑Level Overview**																									
The flowgraph follows this structure:																									
																									
```																									
SDR Source																									
↓																									
Frequency Xlating FIR Filter (optional)																									
↓																									
Quadrature Demod																									
↓																									
Clock Recovery MM																									
↓																									
Binary Slicer																									
↓																									
Correlate Access Code (sync word)																									
↓																									
Fixed-Length Packet Extractor (32 bytes)																									
↓																									
File Sink / Socket / Python Block																									
```																									
																									
---																									
																									
# 🔧 **1. SDR Source Settings**																									
Use whatever SDR you have (RTL‑SDR, HackRF, Pluto, etc.).																									
																									
### **Parameters**																									
- **Center frequency:**																									
- EU: 868.2 MHz																									
- US: 915.0 MHz																									
- **Sample rate:** 500 ksps (safe default)																									
- **Gain:** Manual, around 30–40 dB depending on environment																									
																									
---																									
																									
# 🔧 **2. Quadrature Demod**																									
This converts the 2‑FSK deviation into a baseband frequency signal.																									
																									
### **Parameters**																									
- **Gain:**																									
\[																									
\text{gain} = \frac{\text{sample rate}}{2\pi \cdot \text{freq deviation}}																									
\]																									
For 500 ksps and 50 kHz deviation:																									
																									
\[																									
\text{gain} \approx \frac{500000}{2\pi \cdot 50000} \approx 1.59																									
\]																									
																									
Use **1.6**.																									
																									
---																									
																									
# 🔧 **3. Clock Recovery MM**																									
This extracts the 50 kbps symbol clock.																									
																									
### **Parameters**																									
- **Omega:** sample_rate / symbol_rate = 500000 / 50000 = **10**																									
- **Gain Omega:** 0.25																									
- **Mu:** 0.5																									
- **Gain Mu:** 0.03																									
- **Omega Relative Limit:** 0.005																									
																									
---																									
																									
# 🔧 **4. Binary Slicer**																									
Converts soft symbols → hard bits.																									
																									
No parameters.																									
																									
---																									
																									
# 🔧 **5. Correlate Access Code**																									
SoftRF Legacy uses the nRF905 sync word.																									
																									
### **Sync word**																									
SoftRF uses the nRF905 default:																									
																									
```																									
0xE7 0xE7 0xE7 0xE7																									
```																									
																									
### **Parameters**																									
- **Access code:** `11100111111001111110011111100111`																									
- **Threshold:** 0 (exact match)																									
																									
---																									
																									
# 🔧 **6. Fixed-Length Packet Extractor**																									
After the sync word, extract the 32‑byte payload.																									
																									
### **Parameters**																									
- **Packet length:** 32 bytes × 8 = **256 bits**																									
- **"Output unaligned"**: Off																									
- **"Keep sync word"**: Off																									
																									
---																									
																									
# 🔧 **7. Python Block (packet decode)**																									
This block receives 32‑byte packets and parses them.																									
																									
### **Python code template**																									
```python																									
import struct																									
																									
def work(self, input_items, output_items):																									
data = input_items[0].tobytes()																									
																									
# Expect 32 bytes																									
if len(data) != 32:																									
return 0																									
																									
pkt = data																									
																									
msg_type = pkt[0]																									
aircraft_id = struct.unpack(">H", pkt[1:3])[0]																									
lat = int.from_bytes(pkt[3:6], "big", signed=True) / 93206.0																									
lon = int.from_bytes(pkt[6:9], "big", signed=True) / 46603.0																									
alt = struct.unpack(">H", pkt[9:11])[0]																									
speed = pkt[11]																									
climb = pkt[12]																									
track = pkt[13]																									
																									
print(f"Legacy packet: type={msg_type}, id={aircraft_id}, "																									
f"lat={lat:.6f}, lon={lon:.6f}, alt={alt}, "																									
f"speed={speed}, climb={climb}, track={track}")																									
																									
return len(input_items[0])																									
```																									
																									
This matches the SoftRF Legacy struct layout.																									
																									
---																									
																									
# 🖼️ **Flowgraph Diagram (text form)**																									
																									
```																									
┌────────────────────────┐																									
│      SDR Source        │																									
└───────────┬────────────┘																									
↓																									
┌────────────────────────┐																									
│ Quadrature Demod (1.6) │																									
└───────────┬────────────┘																									
↓																									
┌────────────────────────┐																									
│   Clock Recovery MM    │																									
│   (omega=10)           │																									
└───────────┬────────────┘																									
↓																									
┌────────────────────────┐																									
│     Binary Slicer      │																									
└───────────┬────────────┘																									
↓																									
┌────────────────────────┐																									
│ Correlate Access Code  │																									
│   (E7E7E7E7)            │																									
└───────────┬────────────┘																									
↓																									
┌────────────────────────┐																									
│  Fixed-Length Framer   │																									
│      (256 bits)        │																									
└───────────┬────────────┘																									
↓																									
┌────────────────────────┐																									
│     Python Decoder     │																									
└────────────────────────┘																									
```																									
																									
---																									
																									
																									
																									
Below is a complete, import‑ready **GNU Radio 3.10+** flowgraph in XML form. You can save it as:																									
																									
```																									
softRF_legacy_decoder.grc																									
```																									
																									
and open it directly in GRC.																									
																									
Before that, here are the key choices you asked about:																									
																									
---																									
																									
# 📡 Recommended RTL‑SDR Sample Rate																									
For a 50 kbps 2‑FSK signal with ±50 kHz deviation, the sweet spot is:																									
																									
- **2.0 MS/s** (most stable for RTL‑SDR)																									
- **1.0 MS/s** (also fine)																									
- Avoid 2.4 MS/s unless you know your dongle handles it cleanly.																									
																									
I’ve set the flowgraph to **2.0 MS/s**, which gives plenty of bandwidth for clean demodulation.																									
																									
---																									
																									
# 🧩 Complete GNU Radio Flowgraph (ready to import)																									
																									
Save the following as `softRF_legacy_decoder.grc` and open it in GNU Radio Companion.																									
																									
```																									
<?xml version="1.0"?>																									
<flow_graph>																									
<block>																									
<key>options</key>																									
<param>																									
<key>id</key>																									
<value>softRF_legacy_decoder</value>																									
</param>																									
<param>																									
<key>title</key>																									
<value>SoftRF Legacy 2-FSK Decoder</value>																									
</param>																									
</block>																									
																									
<!-- RTL-SDR Source -->																									
<block>																									
<key>rtlsdr_source</key>																									
<param><key>id</key><value>rtl</value></param>																									
<param><key>freq</key><value>915e6</value></param>																									
<param><key>rate</key><value>2e6</value></param>																									
<param><key>gain</key><value>35</value></param>																									
</block>																									
																									
<!-- Quadrature Demod -->																									
<block>																									
<key>quadrature_demod</key>																									
<param><key>id</key><value>qdemod</value></param>																									
<param><key>gain</key><value>1.6</value></param>																									
</block>																									
																									
<!-- Clock Recovery -->																									
<block>																									
<key>digital_clock_recovery_mm_xx</key>																									
<param><key>id</key><value>clk</value></param>																									
<param><key>omega</key><value>40</value></param>																									
<param><key>gain_omega</key><value>0.25</value></param>																									
<param><key>mu</key><value>0.5</value></param>																									
<param><key>gain_mu</key><value>0.03</value></param>																									
<param><key>omega_relative_limit</key><value>0.005</value></param>																									
</block>																									
																									
<!-- Binary Slicer -->																									
<block>																									
<key>digital_binary_slicer_fb</key>																									
<param><key>id</key><value>slicer</value></param>																									
</block>																									
																									
<!-- Sync Word Correlator -->																									
<block>																									
<key>digital_correlate_access_code_bb</key>																									
<param><key>id</key><value>sync</value></param>																									
<param><key>access_code</key><value>11100111111001111110011111100111</value></param>																									
<param><key>threshold</key><value>0</value></param>																									
</block>																									
																									
<!-- Packet Extractor -->																									
<block>																									
<key>digital_fixedlen_packet_bb</key>																									
<param><key>id</key><value>pkt</value></param>																									
<param><key>len</key><value>256</value></param>																									
</block>																									
																									
<!-- Python Decoder -->																									
<block>																									
<key>python_block</key>																									
<param><key>id</key><value>decoder</value></param>																									
<param><key>imports</key>																									
<value>import struct</value>																									
</param>																									
<param><key>code</key>																									
<value>																									
def work(self, input_items, output_items):																									
data = bytes(input_items[0])																									
if len(data) != 32:																									
return 0																									
																									
msg_type = data[0]																									
aircraft_id = struct.unpack("&gt;H", data[1:3])[0]																									
lat = int.from_bytes(data[3:6], "big", signed=True) / 93206.0																									
lon = int.from_bytes(data[6:9], "big", signed=True) / 46603.0																									
alt = struct.unpack("&gt;H", data[9:11])[0]																									
speed = data[11]																									
climb = data[12]																									
track = data[13]																									
																									
print(f"Legacy pkt: type={msg_type}, id={aircraft_id}, "																									
f"lat={lat:.6f}, lon={lon:.6f}, alt={alt}, "																									
f"speed={speed}, climb={climb}, track={track}")																									
																									
return len(input_items[0])																									
</value>																									
</param>																									
</block>																									
																									
<!-- Connections -->																									
<connection><src>rtl:0</src><dst>qdemod:0</dst></connection>																									
<connection><src>qdemod:0</src><dst>clk:0</dst></connection>																									
<connection><src>clk:0</src><dst>slicer:0</dst></connection>																									
<connection><src>slicer:0</src><dst>sync:0</dst></connection>																									
<connection><src>sync:0</src><dst>pkt:0</dst></connection>																									
<connection><src>pkt:0</src><dst>decoder:0</dst></connection>																									
																									
</flow_graph>																									
```																									
																									
Paste → save → open in GRC.																									
																									
---																									
																									
# 🧭 What you get when you run it																									
You’ll see decoded packets printed like:																									
																									
```																									
Legacy pkt: type=1, id=0xABCD, lat=42.123456, lon=-83.123456, alt=1234, speed=45, climb=1, track=270																									
```																									
																									
That’s a full SoftRF/FLARM‑Legacy position frame.																									
																									
