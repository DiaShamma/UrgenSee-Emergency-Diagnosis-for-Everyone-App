# Description & Plan

## UrgenSee-Emergency-Diagnosis-for-Everyone-App

The UrgenSee app will require several scheme files to manage the data and interactions between the user interface and the APIs. The following scheme files are proposed:

1. **Symptom Scheme**: This scheme will define the structure of the symptom data that will be used to evaluate the user's symptoms. It will include fields such as symptom name, severity, and urgency.

2. **API Scheme**: This scheme will define the structure of the API data that will be retrieved and displayed to the user. It will include fields such as API endpoint, data format, and any required authentication.

3. **User Scheme**: This scheme will define the structure of the user data that will be stored in the app's database. It will include fields such as user ID, symptom history, and saved preferences.

4. **Emergency Scheme**: This scheme will define the structure of the emergency data that will be used to determine the appropriate level of medical attention required. It will include fields such as emergency type, severity, and recommended actions.

5. **Error Scheme**: This scheme will define the structure of the error messages that will be displayed to the user in case of API failures or other errors. It will include fields such as error code, message, and suggested actions.

Plan for the UrgenSee App:

## UrgenSee: Emergency Diagnosis for Everyone

The UrgenSee app is designed to assist users in evaluating their symptoms and determining the urgency of seeking medical attention. The app will provide a comprehensive diagnostic guide for emergency cases, enabling users to make informed judgments about physical symptoms and decide whether immediate medical assistance is required or if the situation can be managed at home. The goal is to prioritize the most life-threatening symptoms while emphasizing that consulting a doctor is essential for accurate diagnosis and treatment.

## Project Requirements

To ensure a successful implementation, the following requirements must be met:

### Should-Have Features

1. **Responsive Design**: The application should be responsive, providing a seamless experience across different devices and screen sizes.
2. **Single-Page Application**: The app will be built as a single-page application, with a single index.html file and JavaScript responsible for updating the HTML using DOM manipulation.
3. **API Integration**: The app should interact with suitable APIs to retrieve medical symptom data and emergency case information.
4. **Loading/Error Handling**: Proper loading indicators and error handling mechanisms should be implemented to provide feedback to the user during API interactions.
5. **User Interaction and Multiple API Calls**: The app should enable user interaction to input symptoms and dynamically fetch and display specific symptom-related data from the API.
6. **Independent Implementation**: The project should be developed independently, avoiding code-along or tutorial-based approaches to demonstrate individual skills and problem-solving abilities.
7. **Presentable Application**: The application should adhere to the guidelines for technical assignments, ensuring that it is complete, well-structured, and ready for presentation.

### Nice-to-Have Features

1. **Additional Symptom Details**: Provide additional information about specific symptoms or conditions, such as causes, treatments, or home remedies. Display relevant images or diagrams to aid users in understanding the symptoms.
2. **First Aid Instructions**: Offer step-by-step first aid instructions for specific emergency cases, such as CPR, choking, or bleeding control. Include visual aids or videos to demonstrate proper techniques.
3. **Localization and Language Support**: Implement language support for multiple languages to cater to a broader user base. Provide localized content and translations for symptoms, conditions, and first aid instructions.
4. **User Accounts and Personalization**: Allow users to create accounts to save their symptom history, track previous evaluations, or store relevant medical information. Provide personalized recommendations or suggested actions based on previous evaluations and user preferences.

## APIs

The application will integrate with suitable APIs that provide medical symptom data and emergency case information. The selection of APIs will be based on their reliability, availability, and the provided documentation. The chosen APIs will be responsible for delivering symptom-related data and any additional information required to enhance the app's functionality.

## Directory Layout and Tree

```
.
├── client
│   ├── package.json
│   ├── package-lock.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
|   |    ├── manifest.json
│   │
│   │
│   │
│   ├── README.md
│   └── src
│       ├── App.css
│       ├── App.js
│       ├── atoms
│       │   ├── Button.js
│       │   ├── Dropdown.js
│       │   ├── FlexTable.css
│       │   ├── FlexTable.js
│       │   ├── Icon.js
│       │   |
│       ├── helpers
│       │   ├── formatDate.js
│       │   └── setAuthToken.js
│       ├── img
│       │   └── todo_cover.jpg
│       ├── index.js
│       ├── pages
│       │   ├── auth
│       │   │   ├── Login.js
│       │   │   └── Register.js
|       |   ├── Homepage.js
|       |
│       │
│       │

```
