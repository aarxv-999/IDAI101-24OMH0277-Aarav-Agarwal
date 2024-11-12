# Made by: Aarav Agarwal, IBCP-XI
## Summative Assessment 1 

The project that I have decided to pick is the gesture recognition system, where if the user makes a certain gesture, the AI model will perform an action in the smart home. The list of the gestures and the potential actions are as follows: <br/>

Open palm: Turn on lights <br/>
Closed fist: Turn off lights <br/>
Peace sign: Play/pause music <br/>
Ok sign: Activate security system <br/>
C sign: Increase Air Conditioning temperature <br/>

For the training data, I decided to include images of people with dark skin and light skin doing the gestures for the sake of diversity. Since this is a prototype, only 2 primary skin tones were considered, but if this model were to officially be released, it would make use of many more races for diversity. 
To find the data, I got majority of the images via google and a lot of the training data was generated using AI. I also took some images myself for the data.

Google's Teachable Machines was the base platform for this model and I used it's Computer Vision and Machine Learning structure. I bumped up the epoch to 200 and the learning rate to 0.00105 for more accurate results. 

To evaluate the model, I used my webcam for input to see how accurate the results were.

This model can easily be integrated in a real world application. For example:
In the future with smart homes, we could implement cameras around the house which recognize any gestures from the residents of the house and each gesture would perform the respective action. This way, homes could be automated further, even assisting disabled people. 

Furthermore, a potential higher level feature for this model could be fingerprint recognition; just from putting your hands up, it would look at your fingerprints for authorization to avoid actions being performed by strangers or unauthorized members. Although this feature would require extremely high quality cameras. 


![image](https://github.com/user-attachments/assets/501d6644-c7e2-45a3-9cad-377cf730bc45)
![image](https://github.com/user-attachments/assets/274b580f-dafc-4834-b962-0d7834733632)

