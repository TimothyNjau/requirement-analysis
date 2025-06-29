# Requirement Analysis in Software Development
The purpose of this repository is to aid in understanding why Requirement analysis is necessary in any software development project.

## What is Requirement Analysis?
Requirement Analysis is a part of the software development lifecycle (SDLC) where we gather, analyze, and define the requirements of the software product to be developed.
It is a crucial step in software development, as it allows us to define the scope of the project backed by documented and factual data.

## Why is Requirement Analysis Important?
- It helps to define the scope of the project.
- Ensures the final product meets the specified requirements, leading to higher customer satisfaction.
- Helps to clarify and understand what the stakeholders expect from the software.
- Gives us an accurate estimation of the project cost, resources, and time.
- Provides a solid foundation for designing and developing the system.
  
## Key Activities in Requirement Analysis
1. Requirement Gathering - methods we can use to gather requirements from the relevant stakeholders, this can be done via: interviews, workshops, surveys. We can also gather information from existing documentation and systems to understand current requirements.
2. Requiring Elicitation - this is refining the requirements that were collected in the first step. This process may entail the following:
   - Conducting brainstorming sessions.
   - Holding focus groups with selected stakeholders to gather detailed requirements.
   - Creating prototypes to help stakeholders visualize the system.
3. Requirement Documentation - this entails giving a detailed documentation of functional and non-functional requirements of the project. One can also create use case stories and diagrams to show the varied interactions between different users and the system.
4. Requirement Analysis and Modelling - creating a model to visualize and analyze requirements, e.g., data flow diagrams, entity-relationship diagrams. There is also an assessment on the feasibility of requirements in terms of technical, financial, and time constraints.
5. Requirement Validation - Review the documented requirements with stakeholders to ensure accuracy and completeness. Definition of acceptance criteria for each requirement to ensure they meet the expected standards.  

## Types of Requirements
  ## Functional 
  These describe what the system should do. For a booking management system, they include: 
   -User registration - create an account with personal and login credentials
   - User authentication - providing a secure login and registration process
   - Property search - ability to search for properties based on various criteria such as location, price, and availability.
   - Booking System - Ability to book properties, view booking details, and manage their bookings.
   - Property Listing - display properties with essential details and images.

  ## Non-functional
  These describe how the system should perform. For a booking system, they include:
   - Performance - able to load a page within 2 seconds and handle up to 1000 concurrent users.
   - Security - Provide data encryption, secure login, and protection against common vulnerabilities.
   - Scalability - Able to be scaled to handle increased traffic.
   - Usability - The System has an intuitive UI/UX, making it easy for users to navigate and perform tasks.
   - Reliability - the system should have an uptime of 99.9% and recover quickly from any failures.

 ## Use Case Diagrams
 This is a visual representation of interactions between users and the system. They show how different users interact with the system to achieve specific goals(use cases).  
*Benefits of Use Case Diagrams*  
- Help in identifying and organizing system requirements.
- Provide a clear visual representation of system functionalities.
- Facilitate communication among stakeholders and the development team.  
 ![alx-booking-uc.png](https://drive.google.com/file/d/1LjZ9stJbHxDGpYBH8ahfUOzHeDgK_4pU/view?usp=drive_link)
![alx-booking-uc](https://github.com/user-attachments/assets/6d8d1ef6-3e9d-49fb-8104-3d2f875c401d)

## Acceptance Criteria
This defines the conditions that a feature must meet to be accepted by the stakeholders.
It should be specific and measurable, and include both functional and non-functional aspects.
An example of an acceptance criterion for a Checkout feature in a booking system > After identifying available dates and booking those particular dates, users should be able to securely pay to book the venue and receive payment confirmation in their email within 2 minutes after payment.

