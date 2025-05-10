
# ChillnCharm

Android shopping app built with MVVM Clean Architecture.

This application was developed as a freelance project during my summer stint with Freelancer.com.
The client of the application envisioned a comprehensive e-commerce application designed to provide an exceptional online shopping experience for their brand, ChillnCharm. ChillnCharm is a dynamic lifestyle brand dedicated to providing customers with the latest in technology, electronics, and casual fashion. Their goal was to offer customers a platform that seamlessly integrates robust functionality with a user-friendly interface, ensuring a smooth and engaging shopping journey for users.


## UI/UX Design

To ensure the application's interface was intuitive and visually appealing, I utilized Figma to design the user interface. From wireframes to high-fidelity prototypes, I crafted a cohesive design system tailored to the client's brand identity. The design process involved creating interactive prototypes to test user flows, such as registration, product browsing, and checkout, ensuring the UI aligned with both user needs and modern e-commerce design standards. This collaborative process helped refine the app’s aesthetics, enhancing the shopping experience through clean layouts, responsive elements, and seamless navigation.

Breakdown:

- **Wireframes and High-Fidelity Prototypes:** I created low-fidelity wireframes to map out user flows (e.g., registration, product browsing, checkout) and then transitioned to high-fidelity prototypes for interactive testing.
- **Design System:** Developed a scalable design system with reusable components (buttons, typography, and color palettes) aligned with ChillnCharm's branding for consistency across screens.
- **Responsive and Adaptive Design:** Ensured seamless functionality across devices with varying screen sizes by adhering to Material Design principles, focusing on responsive layouts and interactive elements.
- **Developer Handoff:** Used Figma’s export and specification tools to streamline the integration of UI assets into Android Studio, ensuring efficient handoff and alignment between the design and implementation phases.

## Screenshots
| Splash Screen       | Login Screen      | Sign-up Screen      |
|----------------|----------------|----------------|
|  ![Screenshot #1](https://github.com/user-attachments/assets/eb4232ef-7dfe-448d-bee8-e58d34d8816e) | ![Screenshot #2](https://github.com/user-attachments/assets/e3ec9189-d2ba-46c0-8474-44668839677c) | ![Screenshot #3](https://github.com/user-attachments/assets/854c9bad-c9c0-4c43-9efb-f886716aaf5e)




| All Products Screen      | Electronics Products Screen       | Jewelery Products Screen       |
|----------------|----------------|----------------|
| ![Screenshot #4](https://github.com/user-attachments/assets/26dbb1b9-1543-486f-a7e4-8d2078d661ac) | ![Screenshot #5](https://github.com/user-attachments/assets/db4bd37a-31ab-4c49-9415-4fc922e53fca) | ![Screenshot #6](https://github.com/user-attachments/assets/d803cb92-4421-4eb0-9354-d490a0fff4a1)








| Men's Clothing Products Screen       | Product Details Screen       | Shopping Cart Screen       |
|----------------|----------------|----------------|
| ![Screenshot #7](https://github.com/user-attachments/assets/ace84541-e9a8-4cb1-8d21-2d96c113e769) | ![Screenshot #8](https://github.com/user-attachments/assets/b8baa588-a200-4905-a554-cc6cd8537e12)| ![Screenshot #9](https://github.com/user-attachments/assets/4a3f966c-0e96-4277-80f4-02072843309f)











| Wishlist Screen       | Searching Screen       | Profile Screen       |
|----------------|----------------|----------------|
![Screenshot #10](https://github.com/user-attachments/assets/1f28f728-2d26-4aa9-8231-5685b4c080ca) | ![Screenshot #11](https://github.com/user-attachments/assets/166c2350-8b0a-4f3f-9990-c1d043b48967) |![Screenshot #12](https://github.com/user-attachments/assets/dd7734a9-f38d-457c-956b-42dc8f465064)











| Edit Profile Screen 1       | Edit Profile Screen 2       | 
|----------------|----------------|
| ![Screenshot #13](https://github.com/user-attachments/assets/22422b4b-130c-4209-add9-79a494fc3d4c) | ![Screenshot #14](https://github.com/user-attachments/assets/dbc323fa-f952-4ec4-969a-16f10b370e3d) 



## Design and Architecture

The application employs a combination of Model-View-ViewModel (MVVM) architecture, the Repository pattern, and Clean Architecture principles. These methodologies were integrated to ensure a modular, scalable, and maintainable codebase with minimal coupling between components.

The project is organized into three distinct layers, implemented within a single module:

1. Data Layer: Manages data retrieval from various sources, including both local and remote. For this project, the remote data source is accessed via the FAKE STORE API using Retrofit, while the local data source utilizes ROOM Database for persistent storage.

2. Domain Layer: Contains the core business logic of the application. This layer interacts with the Data Layer through an abstraction, the Repository Interface, and processes data before passing it to the UI Layer.

3. Presentation Layer: Handles the display of content to the user. The ViewModel in this layer coordinates with the Domain Layer through use-case classes, managing data flow and reacting to user interactions.




## 🎥 Demo Video
A short walkthrough of the application is available below.

▶️ Watch the full demo here:
https://youtu.be/D_8MEBWp0xc


