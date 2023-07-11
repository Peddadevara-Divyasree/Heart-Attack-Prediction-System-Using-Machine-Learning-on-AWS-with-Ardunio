# Heart-attack-prediction-system

# Abstract
In India, close to regarding 2 hundredths of the whole population loses their lives 
because of an interrupted health observance system I.e., in most of the hospitals, doctor 
visits rarely. What happens if patient health becomes critical between that interval or if the 
doctor was unavailable to treat the patient? A patient might lose his/her life. So the main 
theme of our heart attack detection system using DE10 Nano FPGA, machine learning, 
and API Twilio is an innovative approach to monitor heart health and provide timely alerts 
to individuals who may be experiencing a heart attack.
The system uses advanced machine learning algorithms to analyze real-time data from the 
DE10 Nano FPGA, which is capable of monitoring various vital signs such as heart rate, 
glucose levels, cholesterol levels, and ST-T wave abnormality. The system can then detect 
any abnormal patterns and send an alert through Twilio (API) to the user’s phone, allowing 
them to seek immediate medical attention.
This technology has the potential to save lives by providing early detection and 
intervention in cases of heart attack, making it an important advancement in the field of 
healthcare by intimating the level of the disease (i.e., initial stage, intermediate...) In this 
way, we can reduce the mortality rate of a heart attack patients.
# Introduction of project
The real-time monitoring of heart failure patients, especially people with cardio-
vascular diseases, is a very important task. Continuous monitoring can help minimize the 
need for human supervision in hospitals, and ensure the medical monitoring of individuals 
at risk for cardiac seizures without requiring heavy and costly hospital 
management.Therefore, the development of an embedded monitoring system is needed. It 
is possible toperform real-time monitoring of this kind of patient.
To create a machine learning-based heart attack detection system using the DE10 Nano 
FPGA, you would need to first collect a large amount of patient data. This data would need 
to include a variety of patient characteristics, such as age, gender, glucose levels, 
cholesterol level, ECG rest. You would also need to collect data on the patient's heart rate, 
blood pressure, cholesterol levels, and other relevant factors.
Once you have collected the data, you can use machine learning algorithms to analyze it 
and identify patterns that are indicative of an increased risk of a heart attack. You would 
need to train the machine learning algorithm using a variety of techniques, such as 
supervised learning, unsupervised learning, or reinforcement learning, depending on the 
specific algorithm you are using.
Once the machine learning algorithm has been trained, you can deploy it on the DE10 
Nano FPGA to create a real-time heart attack detection system. DE10 nano FPGA board 
as the board offers HPS(hard processor system) which lets us to make serial 
communication with Ardunio.DE10 nano serial communication, is a protocol used for serial 
communication between devices. It allows for data to be sent in a bit-by-bit fashion over a 
single communication line.Arduino is a popular open-source hardware and software 
platform used for building digital devices and interactive objects. It is commonly used in the
development of embedded systems and IoT applications.To implement this system, you 
can use an Arduino board with sensors to collect data from the patient, and a DE10 nano 
board to perform serial communication with the Arduino board. The DE 10 nano board can 
then be used to transmit the collected data to a computer or other device running the 
machine learning algorithm.
We used LXDE(pre installer) OS as environment .We get readings from sensors includes( 
Heart rate , IR , Gas and ECG sensors ) and compare the readings with the dataset Using 
Machine learning technology. The machine learning algorithms would then analyze this 
data in real-time to identify any patterns or anomalies that could indicate an impending 
heart attack. The system would be designed to provide early warning to the patient and 
their healthcare provider, allowing them to take preventative measures and potentially 
save the patient's life.
To ensure that the patient receives timely alerts, the system would be integrated with the 
Twilio platform, which provides a programmable API for sending SMS messages and voice 
calls. The system would be configured to automatically send alerts to the patient's 
healthcare provider and emergency contacts in the event of an impending heart attack.
# Problem statement
Heart attack is a critical medical emergency that requires prompt diagnosis and 
treatment. Early detection of heart attack symptoms can help improve patient outcomes 
and reduce mortality rates. However, identifying symptoms of a heart attack can be 
challenging for individuals, and delayed diagnosis can result in severe consequences. 
Thus, there is a need for an accurate and reliable heart attack detection system that can 
quickly and efficiently identify symptoms and alert medical professionals
