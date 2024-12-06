**DESCRIPTION**

Volunteer match is a platform that allows:
People that are currently looking for a volunteer opportunity do so in an easy and effective way according to their preferences.
Volunteering organisations that want to post their volunteer opportunities on a platform to capture future volunteers.

**PREREQUISITES AND ENVIRONMENT**

The project is made to work with Python 3.7 or later, and Google Colab serves as the main working environment. Jupyter Notebook and other local configurations are also supported. It makes use of a number of essential libraries:
datetime for handling date and time objects
json for controlling the loading and saving of JSON files. 
To support future functionalities, heapq and re are also implemented.

**FILES**

1. Finalvolunteer_and_organization_data.json

This file will act as the main database that will store all the user and organization records. Its structure consists of a list of dictionaries, where each dictionary represents a user or organization. Each entry contains attributes such as email address, username, user type (e.g., volunteer or organization), password, and additional information specific to the user or organization. This centralized format makes data easier to access and manage.

2. Colab notebook file: 

Colab Notebook is a Google Colab-based script designed to interact with a database. It allows users to run code, perform database operations, and easily manage user or organization records. Using the available Colab environment, this file makes it easy to execute and test without the need for local setup.

**INSTALLATION AND USER JOURNEY**

1. Installation

Step 1 : First, get the repository.
Get the project directory's ZIP file from the repository.
Extract the ZIP file's contents into a computer folder.

Step 2. : Provide Google Collab with the JSON database.
Open the notebook in Google Colab.
Upload the finalvolunteer_and_organization_database.json file from the file section (left-hand menu).

Step 3: Run the code
Load and Run the Script: Copy and paste the Python code into a Colab notebook cell.
To initialize the database, run the script.
 
Step 4: Save Database Modifications
 To preserve changes made to the database after editing, use the save_database() method.
 To create a backup, download the latest file.


2. User Journey
Once the user enters the app, after signing up or logging in they will have to define the type of user they are. If a person that wants to become a volunteer, they will need to answer some questions in order to apply different filters.These questions include filters such as what type of missions they want to do to see if they prefer to be in a natural environment or if they prefer something health or education related.Another question asks the user if they have any certifications or experience, just to filter the volunteers options that require something specific. Once these questions are answered the user would be able to see the level of compatibility with different organisations and even if they have matched after the application process being able to keep track of their profile status.

If instead the user is an organisation and wants to post a volunteering opportunity, they could also describe the position including important things such as if there is a language level required. Then they could accept and match with the user profiles.

Limitations:
The applications will be in english so people that want to use it will need to speak and understand the language.
There is not a proper user interface yet.


**FEATURES**

Accessibility via several channels and frequent updates. To provide accessibility for both users that access through multiple platforms including mobile apps and websites. Email alerts are one of the platform’s channels, they offer detailed information about upcoming events and matching opportunities. The app itself will be updated often, taking user comments into account and maintaining its functionality with minimal issues. Likewise, a smooth, effective volunteering experience that appeals to a younger tech-savvy generation is made possible by VolunterrMatch’s constant design optimization which keeps the app sensitive to changes in users’ demand. 
Numerous and diverse volunteer opportunities. This offers a wide variety of programs and satisfies a wide range of interests and backgrounds. Volunteers can explore options ranging from worldwide missions to local community activities due to its user-friendly design. Moreover because of its variety, the app may bring together individuals from a wide range of experiences, including those who are passionate about outdoor activities and want to assist in environmental activities or professionals who are ready to support others. This platform specifically focuses  on a young audience, who frequently struggle to identify the best chances because of time restrictions and ignorance. VolunteerMatch promotes easy participation of the user.
Prioritising safety, dependability and effective assistance by placing a high priority on user security.Only verified companies are listed on the app, giving customers confidence in the chances offered. Additionally, volunteerMatch provides several telephone numbers to which the user can call if they need assistance. 


**FURTHER IMPROVEMENTS**

1. Add user validation
 
To guarantee data security and integrity, it is essential to implement strong user validation procedures. This entails checking that email addresses adhere to accepted forms and confirming the strength of passwords using standards like minimum length, special character inclusion, and avoiding popular patterns. These validation tests can help the system avoid mistakes and increase user confidence.

2. Improved score for compatibility 

The process of matching volunteers with organizations may be significantly enhanced by implementing a dynamic compatibility score system. This may entail creating algorithms that take availability, interests, and skill sets into account. Real-time calculation and display of these ratings to both parties promotes meaningful cooperation and improved decision-making.

3. Integration with cloud storage 

Connecting the database with a cloud storage platform such as Google Drive and AWS S3 to improve availability and scalability is a valuable update. Cloud integration will ensure secure storage, simplify data sharing, and allow authorized users to access information from any device. In addition, this approach can support automated backup and disaster recovery, increasing system reliability.

4. User interface development 
	
Designing a user-friendly user interface is essential to improve the usability of an application. A responsive design with intuitive navigation allows users to interact with the app seamlessly, and features such as forms, dashboards, and real-time notifications improve the overall user experience, making your application more accessible and engaging for all stakeholders.

**BIBLIOGRAPHY**

JSON. (n.d.). JSON documentation. Retrieved from https://www.json.org/json-en.html
Google. (n.d.). Google Colab user guide. Retrieved from https://colab.research.google.com/
Python Software Foundation. (n.d.). Python official documentation. Retrieved from https://docs.python.org/3/

**CREDITS**

This project was created in the subject of algorithms and data structures by Sarah López, Micaela Figari, Adriana Oroza, María Muñoz, Claudia Costa and Ángela Álvarez. 
