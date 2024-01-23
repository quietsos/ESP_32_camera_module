# ESP_32_camera_module
Vision Module Using ESP32 CAM module and ESP32 development board.

Development of a vision module with some LEDs(RGB, UV lights)
1. There will be a master esp32 unit.
2. Other esp32 cam module will connect with master esp32 as slave.
3. Only slaves are transmit data through master unit via MQTT.
4. Capture image after a delay time.
5. Store image in SD card which insert in each esp32 cam.
6 Control the flash of the camera depending on the light intensity.
7. Also all the slaves unit captured image will saved in online database.
8.Also integrated UV and RGB LEDs for imaging to add a fluorescence image to repertoire of image. 
9. There will be a section in dashboard where live streaming of video will show.
10. Master unit will act just a central media of data transmission.
11. PCB design for each module with schematic, Gerber and BOM files.
