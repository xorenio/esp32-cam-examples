# esp32-cam-examples

## Install the esp32 boards 

via the `Tools` -> `Board:` -> `Boards Manager` -> type `esp` -> scroll to bottom

![image](https://github.com/user-attachments/assets/87c17cc3-5ce7-48cc-9297-aeeb13e80eab)

## Select `AI Thinker ESP32-CA` 

via the `Tools` -> `Board:` -> `ESP Arduino` -> `AI Thinker ESP32-CA` 3/4 down

## Examples 

The following examples are using the `OV2640` camera sensor

### 1. Basic
- Wi-Fi
- Camera

### 2. White balance and Exposure
- Auto white balance
- Auto Exposure

### 3. Html Page
- Very basic html page
> This version has issues as its only using 1 core for all the code execution. meaning when the streams loaded no more other requests can be made

### 4. Task to core pinning
- 1st core: Html webserver for html
- 2nd core: Webserver for image stream on port `81`
