# Team_Unblockers_Design_Thinking_CB.EN.U4ARE24060-
The proposed project addresses the problem of people forgetting or misplacing essential belongings while moving from one place to another. Because of frequent transitions, small essential items such as ID cards, keys, earphones, chargers and other personal belongings are easily forgotten or misplaced.

  AI model: Sonnet 5.5

  Prompt: Design a realistic, compact and lightweight smart everyday-carry tracking device for students and active users who frequently move between classrooms, sports facilities, hostel rooms and other locations.

The device should address the problem of users forgetting or misplacing essential belongings such as ID cards, keys, earphones, chargers and other small personal items.

Design the prototype around the following Combination 6 system architecture:

• User location: Inbuilt GPS module in the electronics.
• List of essentials: Acquired listing based on the user's schedule.
• Object identification/location support: RFID-based identification with location information associated with the user's device.
• Inventory logging: Active RFID logging.
• Inventory data storage: Cloud storage.
• Missing-object identification: Relative positioning between the object and the user.
• Alerts and reminders: Location-based reminders.
• Communication: MQTT-based IoT communication.
• Power source: Rechargeable battery.

For the physical prototype, use the following proposed electronic architecture:

1. ESP32-WROOM-32 as the main controller.
2. u-blox NEO-M8N GPS module for location acquisition.
3. MFRC522 RC522 RFID reader using SPI communication.
4. 13.56 MHz MIFARE-compatible RFID tags attached to essential belongings.
5. Rechargeable 3.7 V Li-Po battery.
6. TP4056 charging/protection circuit.
7. Appropriate voltage regulation for the electronics.
8. Small buzzer and LED for local alerts and system status.

Create a compact enclosure that integrates the electronics without appearing bulky. Include attachment or tagging provisions for RFID-tagged personal belongings.

The product should look like a realistic consumer IoT product rather than a laboratory circuit. Use a clean, ergonomic form suitable for everyday student use.

Visually communicate the relationship between the main device and the RFID-tagged belongings. The design should suggest that the user carries the smart device throughout the day while important belongings are identified and monitored.

Show a practical arrangement of the GPS, RFID reader, controller, battery and alert components within the enclosure while maintaining a compact external appearance.

The final virtual prototype should represent a smart essentials-management and tracking system designed to reduce the likelihood of users forgetting or misplacing their important belongings, generate a simulation 3d model for the given product
