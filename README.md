# Fire-Alert

 INTRODUCTION

Fire detection and prevention system uses advanced machine learning and computer vision for real-time fire detection.Unlike traditional sensor-based systems it works effectively in challenging environments like open spaces and windy areas.Machine learning model adapts and learns ensuring quick and accurate fire detection.
When a fire is detected the system not only triggers alarms but also sends email notifications to users for swift action reducing the risk of damage.The system is controlled by an admin who manages users, employee details and camera features.Staff handle vehicle and service details along with fire incidents in urban and rural areas.Users can create accounts and send requests for assistance when direct contact with fire services is not possible.

OBJECTIVES

The project aims to improve fire detection through advanced machine learning and computer vision techniques.By enhancing accuracy and sensitivity it reduces false alarms and ensures reliability in diverse environments.Real-time monitoring enables the prompt detection of fire threats, while a comprehensive notification system sends email alerts to users   facilitating swift evacuation.The solution is designed to be cost-effective leveraging machine learning technologies while maintaining affordability.It also integrates seamlessly with existing fire safety systems, complementing traditional sensor-based solutions.The system addresses critical challenges like early fire detection and provides a crucial tool for emergency personnel to control fires before they cause significant damage.

HARDWARE AND SOFTWARE REQUIRENMENTS 

The hardware requirements for the project include an Intel Core i5 processor, 512 GB of memory (recommended), a standard output display, a QWERTY keyboard for interface, and a standard two-button mouse. The software requirements consist of Visual Studio Code for the frontend, MySQL 5.0 and Python for the backend, and programming languages such as PHP, HTML, CSS, and Python. The project also utilizes the Django framework for efficient development.

MODULES

The project consists of several key modules, including User Management, Fire Detection, Employee Details, Fire Engine Details, Fire Engine Services, Complaint Lodge, and View Complaint. These modules work together to provide a comprehensive system for managing fire safety, from user access to fire incident handling and complaint management.

FUTURE SCOPE

Enhance the user interface and features of the mobile application, providing users with additional information, real-time updates, and interactive features to facilitate Efficient communication during emergency situations.Incorporate GPS technology to precisely locate the fire, aiding emergency responders in reaching the incident location quickly and accuratel

DATABASE DESIGN

Busdetails table consists of several columns including Busid as the primary key,Busno,Chasisno,Wheelbase,Watertankmaterial,Manhole,Pumptype,Pumpdischarge,Delivery,Make,Overalllength, Overallwidth,Overallheight,Bodyroof,Bodydoortype,Bodylocks and Watertankcapacity all with a Varchar data type and a length of 45 except for Busid which is an Integer with a length of 10. The Bus service table contains Busserviceid as the primary key along with Busno,Date,ServiceDescription and Amount all with a Varchar data type and a length of 45 except for Busserviceid which is an Integer with a length of 10.The Complaint table has Complaintid as the primary key,ComplaintNo,Username,Description,Date and Status all with a Varchar data type and a length of 45 except for Complaintid which has a Varchar length of 10.The Employee Details table includes EmpID as the primary key,EmployeeRegId,Name,Phon,Email,Designation,Qualification and  all with a Varchar data type and a length of 45 except for EmpID which has a Varchar length of 45. Finally, the Registration table consists of Registrationid as the primary key, UserName,Password,UserType,Phone and Email all with a Varchar data type and a length of 45 except for Registrationid which has a Varchar length of 10.

CONCLUSION

Fire-Alert project combines machine learning and web application to provide an advanced and reliable solution for fire detection and alerting.By utilizing machine learning for real-time detection, the system ensures high accuracy and minimizes false alarms.The integration of web-based notifications enables response to fire incidents, enhancing safety measures and providing timely alerts to relevant personnel.The systems scalability and robustness ensure its applicability in diverse environments,while its future scope aims at improving response times and mobile accessibility.Project highlights the importance of detecting fires early and having reliable alert systems to protect lives and property.
