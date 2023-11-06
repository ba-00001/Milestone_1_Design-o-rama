##project_spec

# Book Review App

## Table of Contents

1. [App Overview](#App-Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Build Notes](#Build-Notes)

## App Overview

### Description 

A Book Review App that connects to a popular book review API, allowing users to access a curated list of popular books, read reviews, and share their own feedback on the books they've read. This project is designed to help beginners grasp the process of integrating book-related APIs, retrieving comprehensive book information, and presenting book reviews and details in a user-friendly and well-organized layout.

As a stretch feature, the app enables users to conduct specific searches for books, enhancing their ability to explore and discover books of interest.

### App Evaluation

- **Category:** Reading / Social
- **Mobile:** 5/5
- **Story:** 4/5
- **Market:** 4/5
- **Habit:** 4/5
- **Scope:** 5/5

## Product Spec

### 1. User Features (Required and Optional)

Required Features:

- User can view a list of books
- User can read reviews of specific books
- User can share their own book reviews
- User can conduct specific searches for books

Stretch Features:

- Users can search for specific books.
- Users can share book reviews on social media.
- Allow users to create curated lists of their favorite books

### 2. Chosen API(s)

- Goodreads API
  - Retrieve book information and reviews
  - Enable user-generated content for reviews and book recommendations
  <!-- - Goodreads API
  - We will utilize the Google Books API to fetch book information, including titles, reviews, and publication years. -->

### 3. User Interaction

Required Feature

- User selects a book from the list
  - => App displays detailed information and reviews for the selected book
- User conducts a specific search for a book
  - => App presents relevant search results based on the user's query

## Wireframes

<!-- Add picture of your hand sketched wireframes in this section -->
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>
🚧 Under Construction 🚧
This section is currently under construction. Please check back later for the completed version.

### [BONUS] Digital Wireframes & Mockups
🚧 Under Construction 🚧
This section is currently under construction. Please check back later for the completed version.


### [BONUS] Interactive Prototype
🚧 Under Construction 🚧
This section is currently under construction. Please check back later for the completed version.


## Build Notes

The Book Review App was built using Kotlin programming language and the Android Studio Integrated Development Environment (IDE). Kotlin is a modern, concise, and expressive language that offers powerful features for Android app development, making it an ideal choice for building the Book Review App.

During the development process, various Android components such as activities, fragments, and RecyclerView were utilized to create a smooth and intuitive user interface for displaying book information and reviews. The app's layout and design were optimized to ensure a seamless user experience across different Android devices and screen sizes.

Furthermore, the integration of the Goodreads API was facilitated through Retrofit, a type-safe HTTP client for Android and Java. Retrofit simplified the process of retrieving book information and reviews from the Goodreads API, allowing for efficient communication between the app and the external API.

Challenges encountered during the development included handling asynchronous network requests, managing UI thread interactions, and ensuring proper error handling for API responses. Thorough testing and debugging were conducted to identify and resolve any potential issues related to network connectivity and data retrieval from the API.

The implementation of the MVVM (Model-View-ViewModel) architecture pattern in conjunction with LiveData and ViewModel components contributed to the app's robust and maintainable codebase. This architecture facilitated the separation of concerns and improved the overall testability and readability of the code.

Overall, Kotlin and Android Studio provided a comprehensive and efficient development environment for creating a feature-rich and user-friendly Book Review App that meets the requirements and expectations of modern Android users.


## License

Copyright 2023 Group_03

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

