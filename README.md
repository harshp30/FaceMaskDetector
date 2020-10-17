# FaceMask_Detector

May 2020

Youtube Demonstration: https://youtu.be/B7D-o21zXec

Price: $0

This project uses tensorflow which I am quite new too. The premise of the project is to create a applicable project to modern day life. as everbody knows COVID-19 has changed everybodys day to day life and I wanted to create a 
project surrounding that exact idea. On eof the vhanges to everyone's life is on some locations (such as my city) masks are mandatory in indoor locations. This includes Walmart, Superstore, and many other indoor places.
One issue is that some people even with this strict rule in place do not want to or forget to wear a mask. One solution is using a project similiar to this and applyign it at the entry doorways at these stores. This would ensure every individual is 
wearing a mask and if they aren't the staff are iformed and can provide the idnividual with a mask. The project has some flaws, it obviously does not account for individuals who can not wear a mask due to pre existing medical codititons,
but nonetheless the premise of this project is to detcet if someone is wearing a mask or not.

Using tesnorflow I was able to follow some tutorials and get a live video feed howing the probability someone is wearing a mask or not. I wanted to take the project to the next step and wanted it appliable to real world conditions.
With that goal in mind I used Google Text to Speech software and created a smple few lines that would either welcome the ustomer inot a store (if wearing a mask) or prompt them to "please wear a mask before entering (the) store".
The best part about the project is that it reads on a loop live. So if you take of your mask suddenly it will immediately change the prompt.

This is a simple and partially effective way of creating a project that is applicable and useful in the world we live in today. I believe the spread of COVID-19 could be slowed down if this was implemeneted in more stores across the world.

*Github would not let me upload all the training files so I only uploaded the pure code

Challenges:

Getting tensorflow (which I was unfamiliar to work) was very tough, but eventually got it working.
Implimenting a new useful addition to the face mask detector made me think about what issues COVID-19 has presented in society.
I decided to simulate a store entrance and the code checked if an infividual was wearing a mask or not and prompted them.

Lessons:

Simple softwrae like this can really help improve society in certain situtaion like we are in now. 
Wearing a mask is neccessary to limit the spread of COVID-19 and code like this could help save lives by reducing the spread.

Possible Improvements:

Multi-face trackign could have helped mak ethe project more realistic, since in stores individuals are not walking in
a single file line. Being able to track multiple faces would be useful to implement this project in the real world.
