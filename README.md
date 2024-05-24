Overview
This project is a social media application built using React. The application allows users to create, view, and delete posts. It leverages React's Context API for state management, useRef hooks for managing references to DOM elements, and the useReducer hook for handling complex state logic.

Features
Create Post: Users can create new posts with a title and content.
View Posts: Users can view a list of all posts with details.
Delete Post: Users can delete posts.
Technologies Used
React: For building the user interface.
Context API: For global state management.
useRef: For managing DOM references.
useReducer: For handling state transitions.
Project Structure
Components:

PostForm: Form for creating new posts.
PostList: Displays the list of posts.
PostItem: Displays individual post details with a delete option.
Context:

PostContext: Provides and manages the global state for posts.
PostProvider: Wraps the main application to provide context.
Reducer:

postReducer: Handles state transitions for post actions like adding and deleting posts.
