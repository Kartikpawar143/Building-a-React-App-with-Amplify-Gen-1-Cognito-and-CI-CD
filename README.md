# Create a Quiz using AWS Amplify and Cognito (with CI/CD)

# Setuping new user
Open VS Code and create the folder.<br>
install amplify using npm command.<br>
`npm install -g @aws-amplify/cli`

![Screenshot 2025-01-13 224649](https://github.com/user-attachments/assets/84852616-b793-4b42-8087-ab0a26c68393)

![Screenshot 2025-01-13 225255](https://github.com/user-attachments/assets/ebbdab6c-9ee9-400c-a156-22b6b9222c58)

Enter to continue and select the region (ap-south-1)<br>

![Screenshot 2025-01-13 225612](https://github.com/user-attachments/assets/ebd6a6be-f3dd-4d0e-b3ae-bbf4bc80913d)

![Screenshot 2025-01-13 225947](https://github.com/user-attachments/assets/8e918f3a-cf13-4f0f-a2c1-e69ba245ab00)

Open IAM User and Specify user details.<br>

![Screenshot 2025-01-13 230029](https://github.com/user-attachments/assets/7eacea3a-4aa5-46cf-8004-38bf7fe0d83a)

Enter user name (Amplify-dev).<br>
Enter next.<br>

![Screenshot 2025-01-13 230216](https://github.com/user-attachments/assets/edee375f-3437-4dce-b907-3371e2860af5)

Step 2nd is to set the permissions.<br>

![Screenshot 2025-01-13 230225](https://github.com/user-attachments/assets/fb72e772-d0ef-4a0d-a4ed-096da224d691)

Select the permission option - Attach policies directly.<br>
Select permission policies - AdministratorAccess-Amplify.<br>
Then Next.<br>

![Screenshot 2025-01-13 230338](https://github.com/user-attachments/assets/7dc7bd7d-d54b-440a-b883-e9559370c6f1)

Review and create the user.<br>

![Screenshot 2025-01-13 230530](https://github.com/user-attachments/assets/49673f0a-8b2b-4b3d-9fbf-312a4cdfa308)

![Screenshot 2025-01-13 230542](https://github.com/user-attachments/assets/40e6a255-adca-4178-99d8-aeb19adf9520)

![Screenshot 2025-01-13 230739](https://github.com/user-attachments/assets/011825a9-3761-4e03-9c04-7ccf9cc9449e)

![Screenshot 2025-01-13 230840](https://github.com/user-attachments/assets/4125ab25-7f35-4945-8922-3cf7370c9996)

![Screenshot 2025-01-13 230928](https://github.com/user-attachments/assets/fbd08103-6cfa-482b-a8f8-c3f8c7689922)

![Screenshot 2025-01-13 231000](https://github.com/user-attachments/assets/af32f0ac-21ab-480f-9aca-9780001aab84)

![Screenshot 2025-01-13 231016](https://github.com/user-attachments/assets/f4690729-8f74-400c-9624-b2804e3834d7)


![Screenshot 2025-01-13 231110](https://github.com/user-attachments/assets/62d374de-462c-4b2f-b0ad-98e14bf11d0d)

![Screenshot 2025-01-13 231224](https://github.com/user-attachments/assets/7ce1e2ea-bf5c-4877-954b-18a73e74413e)

![Screenshot 2025-01-14 214700](https://github.com/user-attachments/assets/bf7aff26-b126-4b80-a4c7-f5674d67486f)

![Screenshot 2025-01-14 215741](https://github.com/user-attachments/assets/35c9dbdb-4c9a-473a-ad1f-212e5c70d8e6)

![Screenshot 2025-01-14 215909](https://github.com/user-attachments/assets/246a1a8a-15a7-4d38-957a-8dbe6d37db16)

![Screenshot 2025-01-14 220158](https://github.com/user-attachments/assets/109fc7fd-9cc4-4667-bded-3935f7a77102)

![Screenshot 2025-01-14 220239](https://github.com/user-attachments/assets/e43b2df5-5125-4d13-82d7-77fcac3dfd26)

![Screenshot 2025-01-14 221524](https://github.com/user-attachments/assets/b26ad4d9-90ba-4349-ad16-81cb5bec2a81)

![Screenshot 2025-01-14 221616](https://github.com/user-attachments/assets/8b001cac-f668-4257-9401-caf46d09303f)
- **App.js**: The React application that's configured to use Cognito for authentication
- **Quiz.js**: The Quiz component
- **quizData.js**: The hard-coded questions and answers for the quiz


