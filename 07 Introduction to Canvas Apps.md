# Creating Power Apps

There are multiple options that developers can use to create a Power App:

## Creating an App Using Copilot
Copilot in Power Apps leverages AI to assist users in app creation by suggesting features, generating app components, and automating design tasks. This feature streamlines the development process, especially for beginners.

## Creating an App from Data
Power Apps can automatically generate an app based on your existing data sources like SharePoint, Excel, or Dataverse. This method accelerates development by creating basic forms and views directly linked to the data structure.

## Creating an App Using a Page Design
Page design refers to a layout-based approach where users build apps using predefined templates or components for specific pages. This method ensures consistency in design, improving user experience and reducing development time.

## Creating an App from a Template
Power Apps provides various prebuilt templates for common business scenarios (e.g., leave requests, expense trackers). These templates are ideal for learning Power Platform features and accelerating solution deployment by reducing the need for design and functionality planning.
![image](https://github.com/user-attachments/assets/771bafc6-7166-41cb-ad41-cc16fac44e05)

---

## Creating an App Using Copilot
- Accepts a prompt, generates tables, and creates an app based on tables.
![image](https://github.com/user-attachments/assets/52f00e9f-be3c-4787-aa99-ab1290970649)


## Creating an App from Data
- Allows you to create or select a table/data source and generates basic CRUD in the app.
![image](https://github.com/user-attachments/assets/afbd5ded-6dbd-4050-a63b-24b8df2900a1)


## App Generated from Data or Copilot
- Allows you to create or select a table/data source and generates basic CRUD in the app.
![image](https://github.com/user-attachments/assets/eefe39fb-9323-49a6-aa41-2a32623a09b9)


## Creating an App Using a Page Design
- Allows you to select a design and generates a basic view in the app, not connected to data.
![image](https://github.com/user-attachments/assets/bfbbbc7c-5cc9-446a-a81e-b17b2738a614)


---

## Creating an App Using a Page Design – Inserting Image/Figma
- As seen in the image, you can add hand-drawn designs or Figma designs to the app.
- It creates additional components and can require rework if you do not design the Figma using the toolkit.
![image](https://github.com/user-attachments/assets/b9384aea-b029-42ee-961d-2de4ffdeda78)


## Creating an App Using a Page Design – Split Screen
- Here we can see what happens when we create an app using the split-screen page design as an example.
![image](https://github.com/user-attachments/assets/5e049f42-5523-445d-ae79-1539dc07f56d)


## Creating an App from a Template
- Allows you to select a template and automatically creates the app with styling and associated data.
![image](https://github.com/user-attachments/assets/d9d9dad5-dccb-4ca9-a63f-860164512bdc)


## Creating an App from a Template – Meeting Capture Template
- Here we can see what is created automatically when we select a template.
![image](https://github.com/user-attachments/assets/688b3008-8ce9-42d3-a07b-0a7ad1e2494e)


---

# Working with Controls, Forms, and Layouts
![image](https://github.com/user-attachments/assets/ce1a9a5f-ba10-4fd7-8a42-5278b4bd21cb)

---

## Adding a New Screen & Connecting an Existing Data Source
- Here we can see how easy it is to create new screens and rename them.
- Once we’ve created a screen with a user-friendly design, we can easily connect an existing data source.
- Here we are using the **Program Registration** data we connected the app to from the **"Create app from data"** option.
- The SharePoint list data was written to a **Dataverse** table.

## Adding a New Screen & Connecting a New Data Source
- Here we can see how easy it is to create new screens and rename them.
- Once we’ve created a screen with a user-friendly design, we can easily connect a **new data source**.
- Here we are using a **SharePoint list** as a data source.

---

## Edit Functionality of a Button
- Here we are changing the **OnSelect** property of the button to **Navigate** to a different page once the form has been submitted (which was created by default to ensure that the data saves back to the data source).

## Editing Form Components
- Here we are editing the **Text** property of a form that is connected to a data source.
- By default, the form components automatically created with the form will be linked to the data source.
- The binding can be **unlocked** and changed, allowing for further customization of the form components.

---

# Publishing and Testing Canvas Apps

## Publishing:
- Save and publish the app to make it available to users.
- Share the app with your team or organization.

## Testing:
- Use the **preview mode** to test functionality.
- Debug issues using **app checker** and **monitor tools**.

**Tips:** Regularly save versions and test on multiple devices.

---

## Publishing Canvas Apps
- Here we can see how we should save and publish the app.
