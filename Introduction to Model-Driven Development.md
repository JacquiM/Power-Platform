# Introduction to Model-Driven Apps

Model-driven apps are a component of Microsoft Power Platform that enable users to create data-centric applications using a declarative, no-code/low-code approach. Unlike canvas apps, which focus on highly customizable layouts, model-driven apps emphasize pre-defined, consistent design patterns and relationships between data entities. Model-driven apps are often built off of Dataverse tables.

---

## Key Characteristics

### Data-Centric:
- Built on Microsoft Dataverse, allowing robust data modeling and management.
- Focuses on structured data with relationships, business rules, and logic.

### Declarative Design:
- Applications are designed by defining components like forms, views, charts, and dashboards without needing extensive coding.
- Developers specify what the app should do, not how it should be done.

### Standardized UI:
- Automatically provides a uniform and responsive user interface across devices.
- Built-in navigation and data interaction patterns reduce the need for custom UI design.

### Business Logic:
- Incorporates business rules, workflows, and processes directly into the application.
- Enables automation and guided experiences through business process flows.

### Integration:
- Seamlessly integrates with other Power Platform components (Power BI, Power Automate, Power Virtual Agents) and Microsoft 365.

---

## Model-Driven Apps Best Practices

Planning is critical to align the app with business processes and user needs. Understanding data modeling is fundamental to creating scalable and maintainable apps. Optimize data by normalizing tables and using lookup fields to define relationships. Leverage Dataverse features like roll-up and calculated fields to simplify logic.

### Plan and Design First
- **Define Requirements:** Identify the business processes the app will support.
- **Data Modeling:** Understand and model the data structure using Dataverse tables, relationships, and fields.
- **User Journeys:** Map the user experience (UX) to align with business needs.

### Optimize Data Structure
- **Normalize Data:** Use proper normalization to avoid redundancy and improve data integrity.
- **Use Lookup Fields:** Establish relationships between tables for relational data.
- **Leverage Dataverse Features:** Use calculated and roll-up fields for real-time computations.

### Prioritize User Experience
- **Minimalistic Navigation:** Ensure simple and logical navigation. Avoid clutter.
- **Use Views Effectively:** Customize views to display only relevant data fields.

#### Intuitive Forms:
- Arrange fields logically.
- Use sections and tabs for grouping related information.
- Leverage conditional visibility and business rules for dynamic forms.

### Secure Your App
- **Role-Based Security:** Use security roles to control access to tables, views, and actions.
- **Field-Level Security:** Restrict access to sensitive fields.
- **Auditing:** Enable auditing to track changes and ensure compliance.

### Focus on Performance
- **Optimize Queries:**
  - Use filtered views to limit the data retrieved.
  - Avoid overly complex queries in views.
- **Load Only Necessary Data:** Use system and personal views to reduce data loading time.
- **Test Scalability:** Simulate high data volumes to ensure acceptable performance.

### Leverage Standardized Components
- **Dashboards:** Create dashboards for an overview of key metrics and insights.
- **Charts:** Use charts to provide visual data insights.
- **Reusable Components:** Build reusable views, forms, and templates.

### Implement Business Logic and Automation
- **Business Rules:** Add rules for data validation and automation directly on forms.
- **Workflows and Power Automate:**
  - Automate repetitive tasks.
  - Implement approval processes and notifications.
- **Business Process Flows:** Guide users through multi-step processes.

### Test Thoroughly
- **Functional Testing:** Ensure that the app behaves as expected.
- **User Acceptance Testing (UAT):** Involve end-users to validate usability.
- **Performance Testing:** Test with real-world data volumes to identify bottlenecks.

---

## Model-Driven App Development

### Creating a Model-Driven App
This video illustrates the creation of two Dataverse tables – Student and Registration, with a relationship created between the two tables.

### Editing a Model-Driven App
This video illustrates how to edit a model-driven app and add fields to a form.

### Creating and Applying a View
Here we are creating a new view through the model-driven app which will take effect on the Dataverse table too. This is another way of creating a Dataverse view.

### Publishing Model-Driven Apps
#### Publishing:
- Save and publish the app to make it available to users.
- Share the app with your team or organization.

#### Testing:
- Use the preview mode to test functionality.
- **Tips:** Regularly save versions and test on multiple devices.

---

## Publishing Model-Driven Apps
Here we can see how we should save and publish the app.
