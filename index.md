# Third Eye for the Blind
I am working on an Arduino Third Eye for the Blind. Users with visual disabilities are able to detect objects with the use of physical and audio cues from their very own hand.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Kyra D. | Piedmont High School | Software Engineering | Incoming Senior

<p align="center">
<img src="https://user-images.githubusercontent.com/94956287/176249518-41fbc503-300a-44c9-b105-41aef7d56669.png" width="400">
<img src="https://user-images.githubusercontent.com/94956287/176250830-977c3406-10c4-423c-be4b-18db8e569712.png" width="400">
</p>

# Final Milestone
My final milestone is the addition of a thermistor that provides temperature readings. Negative Temperature Coefficient (NTC) Thermistors change resistance with temperature. By understanding the relationship between temperature and resistance, temperature readings can be obtained. I chose to add this modification because while those who are blind are typically able to feel when objects are hot, if they are reaching out fast or far, this added safety feature will override the buzzer or vibrating mode and will constantly beep until the detected object is below a certain threshold. I first tested the use of the thermistor on my prototype breadboard before adding it to the soldered micro. The thermistor is placed on the palm of the user's hand alongside the ultrasonic sensor, so that the device both determines distance and temperature as the user gets towards objects.

[![Kyra's Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1656520787/video_to_markdown/images/youtube--AKeC7Vd3b3w-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=AKeC7Vd3b3w "Kyra's Final Milestone")

# Third Milestone
My third milestone was finishing the project and making the whole device handheld. Taking my prototype from the breadboard, I sautered the connections to my perfboard and Arduino Micro using wires and soldering tracks. With soldering, I was able to make connections underneath the board, so that the device used a micro board instead of an Arduino Uno. This took a lot of time and patience, as I had to make sure all of my connections were secure, and that they were in the right place. After ensuring all of my connections were correct and secure, I hooked up the power source which is a 9V battery. The next step was making this portable, and I used an old glove instead of a piece of cloth to glue down my board, sensor, and power source. In addition, I changed the button feature so that the user can toggle between buzzer and vibrating mode rather than having to hold down the button. This made the device more functional and easier to switch between modes.

<p align="center">
<img src="https://user-images.githubusercontent.com/94956287/176252080-bea44cc8-bcb4-4551-94b7-e2ddc74dafe7.JPG" width="500">
</p>

[![Kyra's 3rd Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1656091170/video_to_markdown/images/youtube--3WJ3lJCEA6w-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=3WJ3lJCEA6w "Kyra's 3rd Milestone")

# Second Milestone
My second milestone was getting my button and vibrating motor to work alongside the ultrasonic sensor and button. I used the same conditional statements for the code of the vibrating motor and buzzer, which will change the frequency of alerts given off from either one. When a button is not held down, the pins are only connected in pairs. When the button is pressed, the pins are internally connected. Using different conditional statements, I programmed the code to switch to buzzer mode when the button was pressed, and then default to vibrating mode when not pressed. This was in replacement of the switch used in previous projects, the only set back of this, however, was that the user would have to hold the button down for the duration of the desired mode.

[![Kyra's 2nd Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1656090848/video_to_markdown/images/youtube--jOFxKbY50XA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=jOFxKbY50XA "Kyra's 2nd Milestone")

# First Milestone
My first milestone was setting up my ultrasonic sensors and piezo buzzer. The ultrasonic sensor works by sending out an ultrasonic wave, and measuring the time it takes for that wave to bounce off an object and be received again by the sensor. I first tested the  sensor using basic example code in the Arduino library, to make sure that the distance measured between the sensor and target object was accurate. After getting my sensor to work, I added the piezo buzzer to the breadboard and used conditional statements to make the buzzer make noise when an onject was a certain distance. When the object is far away, there is no noise, but as the sensor gets closer to the object, the noise becomes mre high pitched and frequent, audibly letting the user know they are close to something.

[![Kyra's First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1656439828/video_to_markdown/images/youtube--gY0ncTcIGnQ-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=gY0ncTcIGnQ&t=17s "Kyra's First Milestone")
