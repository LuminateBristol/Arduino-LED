# Programming for Robotics - Arduino Controlled LED Lights

## WokWi Simulator

Click the following link to open the LED strip simulator:

https://wokwi.com/arduino/libraries/FastLED/ColorPalette

Replace the code with this empty Arduino sketch:
```

void setup() {

}


void loop() {

}
```

## ESP 32 with the Arduino IDE

https://dl.espressif.com/dl/package_esp32_index.json

To set up the Arduino IDE to work with the LED light tubes we need to install the ESP32 board manager. For to `File > Preferences` and add copy link given above and paste it into the box `Additional Boards Manager URLs:`. Click OK.

Next go to `Tools > Board "****" > Boards NManger...`. In the Boards Manager search for `esp32` and find the `esp32 by Espressif Systems` board manager - click `Install`. Click close.

Finally go to `Tools > Board "ESP32 Dev Module" > ESP Arduino` and select `ESP32 Dev Module`.

## Install the FastLED library

Go to `Tools > Manage Libraries...` and search for `FastLED`. Find the the `FastLED by Daniel Garcia` library and click `Install`. 

## Upload to the light tube board

To upload we first need to select the `Port:`.

Go to `Tools > Port:` and select `COM3`. If this not an option or does not work, try one of the other `COM` ports.

Once the port is selected. Click the compile button (tick symbol) and the upload button (right arrow button).
