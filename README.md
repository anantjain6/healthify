
# HEALTHIFY AMBULANCE
Healthify Ambulance is an Ambulance Management System that will ease the management of ambulances for better effectiveness. It provides solution to the following problems:

  - Tracking of Ambulances.
  - Finding way to the patient’s location as these locations are not on Google Maps.
  - The person who receives the call when someone dials 102/108/District Hospital is a non-medical person and seldom knows the severity of the case.

## DESCRIPTION

  - Tracking of Ambulances : In our Project we have made great use of Google Transport Tracker API to track the live location of the Ambulances. This is the fastest way of getting the live location of Ambulances so that one can immediately send the ambulance to places where there are no ambulance at that time. 
  - Locating the Patient :It becomes very handy for the ambulance driver to get the exact location of the patient, especially if it is a rural area and it may also cause the patient death. To unravel this problem, we’ll  send a link to the patient’s phone which on clicking will fetch the exact location of the patient. It would be a simple web link which works on IP tracking technique. Also, if the patient does not have an active internet connection we’ll fetch the location by an Android Application which will access the GPS of the phone and send us the coordinates. 
-  Severity and Disease Identification of the Patient: It happens nowadays that the person who is receiving the call of the Patient does not know what ambulance to send or the type of first aid required by the patient by hearing his symptoms. To track this problem, we will use a controller system that would record the call and extract the symptoms and severity of the medical issue. This will be done through Machine Learning. This would effectively save the cost and time which is very critical for both the patient and ambulance.