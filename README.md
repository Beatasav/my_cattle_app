# My Cattle Project

My Cattle Project is a web application designed to assist cattle farmers in managing their cattle, herds, and fields. 
The project aims to provide a centralized platform for recording and accessing essential information about livestock and fields, as well as generating livestock movement reports. 
This README provides an overview of the project, installation instructions, and usage guidelines.

## Features

- **Cattle Management**: Record and manages individual cattle details, including number, name, gender, breed, acquisition, birth and entry dates, loss methods, and more. Allocate cattle to existing herds and update entries seamlessly for accurate management.

- **Herd Management**: Organize cattle into herds. Keep track of important herd details like location, start date, end date, leader, and status. Easily assign one or more cattle to a herd, select existing fields for their location, and update entries seamlessly for precise management.

- **Field Management**: Record details about fields where herds are located. Add information such as field size, location, coordinates, and any specific conditions relevant to the field. Also, assign herds to particular field.
- 
- **Group Management**: Categorize cattle into age groups to simplify farm oversight and reporting.

- **Dashboard**: Displays the count of cattle within each age group currently present on the farm and provides access to all cattle within their respective groups.

- **Efficient Search**: Quick access to information about cattle, herds, and fields through search functionality. 

- **Livestock Movement Report**: Generate detailed reports to track changes in livestock across different age groups. Monitor weight fluctuations, observe acquisition and loss events within selected time periods. 

- **User Authentication**: Secure access to the application with user authentication.

# Deployment

Explore the live version of the application online. Please consider the following:

- **Access URL**: https://mycattle.azurewebsites.net/
- **Limitations**: The deployment is hosted on a free Microsoft Azure account, which might result in occasional slower loading times. If the application doesn't load initially, please try again later.
- **User Access**: To browse, please log in:
Username: 'guest'
Password: 'gu94estuzo85''

# Usage (Deployed Version):

Here's how to effectively use the deployed version of the application:

1. Access the Application: Open your web browser and visit the provided deployment URL mentioned in the "Deployment" section.
2. Log in: Use the following credentials:
Username: 'guest'
Password: 'gu94estuzo85'
3. Explore Cattle Information: On the main page's dashboard, access cattle information by age group, active herd, and active fields.
4. Manage Data: Utilize the navigation panel to access recorded fields, herds, and cattle. From there, perform management actions such as adding new items or updating existing data.
5. Generate Reports: Create livestock movement reports to analyze cattle data.

## Installation

1. Clone the repository: `git clone https://github.com/JeskevicRasa/my_cattle.git
2. Install dependencies: `pip install -r requirements.txt`
3. Set up the database: `python manage.py migrate`
4. Create a superuser: `python manage.py createsuperuser`
5. Start the development server: `python manage.py runserver`

## Usage

1. Access the application in your web browser at `http://localhost:8000`.
2. Log in using your superuser account or create a new account with appropriate permissions.
3. Add cattle information using the provided forms and interfaces.
4. Manage cattle movements, group assignments, and other details from the user-friendly dashboard.
5. Generate reports to analyze cattle data and make informed decisions.


Happy cattle management! 🐮
