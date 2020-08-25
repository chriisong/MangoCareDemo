# Mango Care
**Mango Care** is a Personal Health Record app that enables patients to keep a well-organized record of their prescriptions, blood glucose values, blood pressure values, weight measurements, and clinic appointments, and set alerts to remind them to take their prescriptions, measure their health indices, and attend their appointments. Mango Care stores all sensitive data in private CloudKit containers to not only keep the user's data data secure, but also to allow ease of use when operating from different device. 

Upcoming versions of Mango Care will focus on interactions between the users and their designated clinics or other healthcare facilities. For example, patients will be able to share their data with their medical professionals in order to receive appropriate coaching and prescription adjusting to better suit their current health trend. Moreover, medical professionals will be able to push prescription information to their designated patients, set appointments, or send lab results directly to the users. 

Mango Care allows for unimpeded access to a patient’s own medical record and will play a bigger role in the growing telemedicine industry.

#### Technology: Core Data, CloudKit, UNNotification, Diffable Data Source, REST API
#### 3rd Party Libraries: FSCalendar, YPImagePicker, Charts
## Screen Recordings

### Charts to Visualize Health Index Values
![Alt Text](Gifs/Charts.gif)

### URLSession API Call to [Canadian Drug Product Database](https://health-products.canada.ca/api/documentation/dpd-documentation-en.html)
![Alt Text](Gifs/DrugDB.gif)

### YPImagePicker to Upload Images
![Alt Text](Gifs/Radiology.gif)

### UIDocumentPicker
![Alt Text](Gifs/Document.gif)

### Custom Views, UNUserNotificationCenter, FSCalendar to Add Appointment Information
![Alt Text](Gifs/Appointment.gif)

### NSDiffableDataSourceSnapshot to Add or Remove CollectionView Items
![Alt Text](Gifs/AddReminder.gif)

### Custom Views and Animation to Present Modal ViewController 
![Alt Text](Gifs/AddDoctor.gif)

### Custom CollectionView Cell with Button that updates Core Data Object Values
![Alt Text](Gifs/Prescription.gif)
![Alt Text](Gifs/AddDoctor.gif)
