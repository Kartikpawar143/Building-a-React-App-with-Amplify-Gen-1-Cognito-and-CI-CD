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

![Screenshot 2025-01-14 221903](https://github.com/user-attachments/assets/2c834182-357c-4ab0-a3d4-8d4cb0fef35e)

![Screenshot 2025-01-14 221944](https://github.com/user-attachments/assets/8256f208-e398-4c3a-b405-9eeedd725a72)

![Screenshot 2025-01-14 222629](https://github.com/user-attachments/assets/f8a26ec6-845b-4873-9585-f55f99747e7b)

![Screenshot 2025-01-14 223118](https://github.com/user-attachments/assets/3dc0a2cc-1d91-4251-94f8-16319463e769)

![Screenshot 2025-01-14 223132](https://github.com/user-attachments/assets/0d500045-76e7-4c57-b4e5-1ad7afdff609)

![Screenshot 2025-01-14 224207](https://github.com/user-attachments/assets/6fc0a147-b51d-4428-878a-ff77d8420a26)

![Screenshot 2025-01-14 224223](https://github.com/user-attachments/assets/64f196bd-b154-445a-a451-11b06c79d25b)

![Screenshot 2025-01-14 224937](https://github.com/user-attachments/assets/210af764-b63e-4148-8e39-151d0657b4fc)

![Screenshot 2025-01-14 224948](https://github.com/user-attachments/assets/b2fcd7d2-e9af-4c1d-81dc-e65c269e57fa)

![Screenshot 2025-01-14 225018](https://github.com/user-attachments/assets/df10e5f7-647a-4ee7-8e51-b3634408b5c9)

![Screenshot 2025-01-14 225033](https://github.com/user-attachments/assets/4245ec4e-0a34-4c6b-8217-00c9b8102a00)

![Screenshot 2025-01-14 225108](https://github.com/user-attachments/assets/f4097819-f11a-44b4-87be-8b882d542082)

![Screenshot 2025-01-14 225118](https://github.com/user-attachments/assets/4b202229-1813-4c9c-b251-073b9f530234)

![Screenshot 2025-01-14 225139](https://github.com/user-attachments/assets/0ecee7d0-00d3-4e82-bc59-c08f73c189e1)

![Screenshot 2025-01-14 225316](https://github.com/user-attachments/assets/425acf96-8333-44cb-9c60-180d009205f9)

![Screenshot 2025-01-14 225923](https://github.com/user-attachments/assets/c13bc793-23e4-4153-a5cf-91277ee68317)

![Screenshot 2025-01-14 230116](https://github.com/user-attachments/assets/a01a2e9c-2f3e-4119-a27f-1b3e3bb3a11e)

![Screenshot 2025-01-14 230148](https://github.com/user-attachments/assets/ac5710ca-25aa-4df5-a130-c5c014f3b747)

![Screenshot 2025-01-14 230605](https://github.com/user-attachments/assets/3bd8b26a-02fc-4917-a9e9-079285e41581)

![Screenshot 2025-01-14 230854](https://github.com/user-attachments/assets/a16bc454-7300-4a1c-8af4-29482906896d)

![Screenshot 2025-01-14 231042](https://github.com/user-attachments/assets/204e7766-ef95-4492-9d81-210095bebe71)

![Screenshot 2025-01-14 231340](https://github.com/user-attachments/assets/ac7fe999-f29e-433a-a4d3-b985a80b3c11)

![Screenshot 2025-01-15 000227](https://github.com/user-attachments/assets/2741a719-4277-4e76-8135-b8f10c14500c)

![Screenshot 2025-01-15 000448](https://github.com/user-attachments/assets/b5b00555-676e-4740-9390-518eb2162597)

![Screenshot 2025-01-15 000459](https://github.com/user-attachments/assets/b9a1743f-7c75-4849-80e5-8a5a45935ca9)

![Screenshot 2025-01-15 000542](https://github.com/user-attachments/assets/d9b3b713-866d-4fdf-b0ab-8d2e4a15a6b7)

![Screenshot 2025-01-15 000557](https://github.com/user-attachments/assets/dd847e9d-9fbd-4928-a18d-b2a87ee23d0c)

![Screenshot 2025-01-15 000725](https://github.com/user-attachments/assets/0365140a-1c08-4817-a57f-1968537bab50)

![Screenshot 2025-01-15 001017](https://github.com/user-attachments/assets/d7545e04-acad-46e2-9177-296e05d4e1dd)

![Screenshot 2025-01-15 001133](https://github.com/user-attachments/assets/342d06f4-e267-4329-b1cc-cdd76e4898a4)

![Screenshot 2025-01-15 001157](https://github.com/user-attachments/assets/a280e027-49c9-41fb-8a43-6364aa7b4ba6)

![Screenshot 2025-01-15 001206](https://github.com/user-attachments/assets/2a342bed-2d2c-4799-8525-3440ff8e161d)

![Screenshot 2025-01-15 001246](https://github.com/user-attachments/assets/a986ac5f-5315-4bd4-b91d-47e1b7e15374)

![Screenshot 2025-01-15 001252](https://github.com/user-attachments/assets/27bf679d-e863-42e5-9daa-cb3736fc400a)

![Screenshot 2025-01-15 001338](https://github.com/user-attachments/assets/2228fab8-e809-4bbf-a2d7-f2ab66cac0c4)

![Screenshot 2025-01-15 001401](https://github.com/user-attachments/assets/500d4501-a2cb-44c1-bb49-f6dd4d063546)

![Screenshot 2025-01-15 001409](https://github.com/user-attachments/assets/ba039450-6b3b-4085-8f86-1e43a8c3414c)

![Screenshot 2025-01-15 001757](https://github.com/user-attachments/assets/096c0e86-39f8-451f-a59d-1c8bdc17d12f)

![Screenshot 2025-01-15 001839](https://github.com/user-attachments/assets/2a34f92f-76c7-4c12-b181-1a2531c2772f)

![Screenshot 2025-01-15 002007](https://github.com/user-attachments/assets/8d7793fa-8ba9-461a-84f7-225378aa1ba8)

![Screenshot 2025-01-15 002022](https://github.com/user-attachments/assets/753371da-c0ce-4e1d-b7b0-51935f2372f7)

![Screenshot 2025-01-15 002157](https://github.com/user-attachments/assets/e86f0caa-09a7-4ba4-851b-eddb41eeaa55)

![Screenshot 2025-01-15 002212](https://github.com/user-attachments/assets/2a9dce7a-af65-4694-be1e-5c68c735f37a)

![Screenshot 2025-01-15 002656](https://github.com/user-attachments/assets/a21cd15c-4f57-4296-ad48-9d8b190a0b18)

# You have successfully Builded a simple React app (a quiz app) using AWS Amplify Gen 1 and Cognito.

- **App.js**: The React application that's configured to use Cognito for authentication
- **Quiz.js**: The Quiz component
- **quizData.js**: The hard-coded questions and answers for the quiz


