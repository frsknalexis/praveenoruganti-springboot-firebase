# Patient App using SpringBoot and Firebase

## Create app in Firebase

- Go to Firebase Console

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/1.PNG)

- Create Project

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/2.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/3.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/4.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/5.PNG)

- Now go to project settings

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/6.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/7.PNG)

- Now go to service accounts tab

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/8.PNG)


Now select Java and copy the code and paste it in [FBInitialize.java](https://github.com/praveenoruganti/praveenoruganti-springboot/blob/master/0_Projects/praveenoruganti-springboot-firebase/src/main/java/com/praveen/patient/repository/FBInitialize.java)

- Get serviceAccount.json by clicking on Generate new private key button and place it in [resources](https://github.com/praveenoruganti/praveenoruganti-springboot-firebase/tree/master/src/main/resources) folder.

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/9.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/10.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/11.PNG)

- Now create Firestore in praveenoruganti-patient-app

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/12.PNG)

Now click on Create database

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/13.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/14.PNG)

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/15.PNG)


- Now lets see SpringBoot App coding

[Patient Controller](https://github.com/praveenoruganti/praveenoruganti-springboot/blob/master/0_Projects/praveenoruganti-springboot-firebase/src/main/java/com/praveen/patient/controller/PatientController.java) in SpringBoot App.
 
[Patient Service](https://github.com/praveenoruganti/praveenoruganti-springboot/blob/master/0_Projects/praveenoruganti-springboot-firebase/src/main/java/com/praveen/patient/service/PatientServiceImpl.java) in SpringBoot App.

Create [new user](https://github.com/praveenoruganti/praveenoruganti-springboot/blob/master/0_Projects/praveenoruganti-springboot-firebase/src/main/java/com/praveen/patient/service/AuthServiceImpl.java) in Firebase.

- Lets see swagger 

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/16.PNG)

- Lets create a patient using endpoint POST /api/v1_0/createPatient

```JSON

{
  "age": 35,
  "city": "Hyderabad",
  "name": "Praveen"
}

```

- Lets see the Firebase

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/17.PNG)

- Lets get the patient details

![screenshot of the app](https://raw.githubusercontent.com/praveenorugantitech/praveenoruganti-springboot-firebase/master/src/main/resources/images/18.PNG)






