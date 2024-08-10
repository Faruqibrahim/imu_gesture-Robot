### IMU gesture-based controller ###

* Quick summary

The IMU-Bot is a GoPiGo2 bot controlled by a specially designed controller on the glove. The controller consists of a multisensor connected to the Raspberry Pi Pico with a Wi-Fi adapter. This Raspberry Pi receives the signal from the multisensor's gyroscope and accelerometer and compares the signal taken with signals in the database. Based on that information, Raspberry Pi decides if the signal taken is a noise or a "gesture" and then sends the corresponding answer to the GoPiGo2 robot with another Raspbery Py on it. The signals will include such functions as going forwards and backwards, turning to right or left, stopping the robot and so on. 

During the discussion, some ideas of working logic were proposed. There was a proposal of state machines for making a gesture detection, for example state one: it goes up, state two it goes forward etc. Besides, there was a proposal of machine learning for gesture detection. We have decided to use machine learning for that, but we will also try out other methods, including nested loops if they will work better.

We also discussed the possible appearance of the controller. One of the ideas was a watch that would be fixed on the hand of the user. Another idea was to place a controller on a glove, and we thought that it was a fantastic idea and would have some benefits. The main advantage of such a design is that it is simple but beneficial, as the user's hand will be free to do any other movements.

![Proposed Design](https://media.discordapp.net/attachments/1168278483001167962/1171891347658121226/image.png?ex=655e53dd&is=654bdedd&hm=91855279dc52a2531733ea7d6eb7d27acd287d0be12d879f87717669132bc7c7&=&width=1013&height=670)

The main problem of the project is that we want to make a user able to give any commands he wants to a robot just using gestures of his arm with the special glove on it.
We are sure that we will face many issues during this project, and our main issue is that we have neither experience nor knowledge in machine learning, and we will have to learn ourselves while creating the controller. Some other possible problems are issues while trying to make communication between two Raspberry Pi's.

* Version

### Students ###

* Faruq Olamilekan Ibrahim
* Nikita Kurenkov
* Martin Hansschmidt
* Jaan Hendrik Tomp

### Component list ###

| Item | Link to the item | We will provide | Need from instructors | 3D print | Total |
| ---- | ---------------- | --------------: | --------------------: | -------: | :---: | 
| GoPiGo2 |  | 0 | 1 | 0 | 1 |
| Li-ion battery pack |  | 0 | 1 | 0 | 1 |
| Li-ion battery adapter |  | 0 | 1 | 0 | 1 |
| 2 cell battery pack (AA) |  | 0 | 1 | 0 | 1 |
| Multi-sensor |  | 0 | 1 | 0 | 1 |
| RaspberryPi Pico W |  | 0 | 1 | 0 | 1 |
| RaspberryPi Pico (second option) |  | 0 | 1 | 0 | 1 |
| WEMOS D1 MINI (second option) | https://robolabor.ee/et/arendusplaadid/980-wemos-d1-mini-esp8266-v400.html | 0 | 1 | 0 | 1 |
| USB A/USB Micro B Cable 1.8 m |  | 0 | 1 | 0 | 1 |
| Power cable (Battery - Robot) |  | 0 | 1 | 0 | 1 |
| BreadBoard |  | 0 | 1 | 0 | 1 |
| Male to Male Jumper Wire set (10 pieces) |  | 0 | 1 | 0 | 1 |
| Male to Female Jumper Wire set (10 pieces) |  | 0 | 1 | 0 | 1 |
| Pair of gloves |  | 1 | 0 | 0 | 1 |
| Micro sd card 32GB |  | 0 | 1 | 0 | 1 |
| Micro sd card Adaptor |  | 0 | 1 | 0 | 1 |
| 3D printed controller holder |  | 0 | 0 | 1 | 1 |
