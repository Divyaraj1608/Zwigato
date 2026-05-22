# Zwigato 
# Food & Grocery Delivery Android App

It is a modern, robust, and feature-rich Android application for food and grocery delivery. This project is built using **Kotlin** and follows modern Android development best practices, leveraging the **MVVM** architecture pattern and a fully reactive tech stack.

##  Features

- **User Authentication:** Secure login and registration powered by Firebase.
- **Dynamic Catalog:** Browse and search through various food and grocery items.
- **Real-time Data:** Seamless data fetching from a GraphQL endpoint using the Apollo library.
- **Cart & Checkout Management:** Smooth item handling with local/remote state updates.
- **Modern UI/UX:** Responsive layouts with seamless navigation transitions.

##  Architecture & Tech Stack

This project strictly adheres to the **MVVM (Model-View-ViewModel)** architecture pattern to ensure clean separation of concerns, testability, and maintainability.

- **Language:** [Kotlin](https://kotlinlang.org/) - First-class language for Android development.
- **UI Architecture:**
  - **View Binding & Data Binding:** To bind UI components directly to data sources safely and efficiently.
  - **Navigation Component:** For managing in-app navigation, fragment transactions, and safe argument passing.
- **Asynchronous Execution:**
  - **Kotlin Coroutines:** For managing background tasks smoothly without blocking the main thread.
- **State Management:**
  - **ViewModel:** Stores and manages UI-related data in a lifecycle-conscious way.
  - **LiveData:** Observable data holder class to notify views of data changes.
- **Dependency Injection:**
  - **Hilt (Dagger-Hilt):** Standardizes dependency injection across the application for modularity and easy testing.
- **Networking:**
  - **Apollo Kotlin (GraphQL):** Used to execute queries and mutations against a backend GraphQL endpoint.
- **Backend Services:**
  - **Firebase:** Utilized for core services like authentication, database storage, or cloud messaging.



<img width="1080" height="2400" alt="home" src="https://github.com/user-attachments/assets/db857c36-025d-41c3-a363-3e47da56206a" />
<img width="1080" height="2400" alt="merchant" src="https://github.com/user-attachments/assets/74f78aeb-d14a-4c03-828d-283eff7da71e" />
<img width="1080" height="2400" alt="product" src="https://github.com/user-attachments/assets/e31ba7a1-c9f8-401b-8254-5ddee5b8a104" />


