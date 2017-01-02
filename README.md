# Representational-State-Transfer-REST
This example shows how to use the Bridge to access the digital and analog pins on the board through REST calls. Hardware Required

• The Bridge library enables communication between Arduino and Linux

• REST is an architectural style consisting of a coordinated set of architectural constraints applied to components, connectors, and data elements.
• Base on URL, such as http://example.com/resources/
• An internet media type for the data(JSON, XML, etc.)
• Standard HTTP methods(GET, PUT, POST, DELETE)

Try to use a browser to send RESTful command to specify three modes of a LED as follows:
– Blink mode: blink the LED
– Fading mode: fade the LED
– SOS mode: generate SOS signal
Hint: You may change your Arduino between these modes by using following URL via web browser:
– http://arduino.local/arduino/blink -> blink mode – http://arduino.local/arduino/fade -> fading mode – http://arduino.local/arduino/sos -> SOS mode
