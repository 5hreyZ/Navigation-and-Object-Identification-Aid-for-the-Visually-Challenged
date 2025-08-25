# Navigation-and-Object-Identification-Aid-for-the-Visually-Challenged
Affordable Wearable Navigation Aid for the Visually Impaired
This project develops an affordable, lightweight electronic navigation system designed to help visually impaired people travel independently. The device is shaped like a pair of eyeglasses and incorporates ultrasonic sensors and vibration motors to provide spatial awareness of obstacles.

Key Features
1) Obstacle Detection: Two ultrasonic sensors detect objects up to 400 cm ahead. Feedback is delivered via two calibrated vibration motors, allowing users to perceive the distance and location of obstacles by changes in vibration intensity and position.
2) Object Identification: A camera module continuously captures live video. A TensorFlow-based model processes this video in real time to identify objects ahead, which are announced to the user through earphones to aid object search.
3) Processing: The system uses a Raspberry Pi 3B+ microcomputer to handle sensor data and run the image recognition model.

Technology Stack
1) Raspberry Pi 3B+ for embedded processing
2) HC-SR04 ultrasonic sensors for distance measurement
3) Precision vibration motors for tactile feedback
4) TensorFlow for machine learning-based image recognition
5) Compact camera module for video capture

Impact
The device combines sensor-based obstacle detection with AI-driven object recognition to enhance mobility and independence for the visually impaired. It offers an intuitive, wearable interface that supports safe navigation in real-world environments.

Contributions
Contributions and suggestions for additional features, sensors, or feedback forms are welcome. Refer to the documentation for setup instructions and how to participate.
