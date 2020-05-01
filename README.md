# HomieLib
Adaptation of Light weight homie v3 (MQTT) Library for ESP8266 and ESP32

Nothing much, just adds a pointer to the owning object of the HomieProperty as parameter of callback, since callbacks are stateless. Enables use of class instances with the library.

No documentation yet except for the example.

It doesn't have every homie feature but is well matched with openHAB.

## dependencies

[AsyncMqttClient](https://github.com/marvinroger/async-mqtt-client)

[ESPAsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP)
