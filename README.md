# Large File Upload System - MERN Stack Challenge

## Overview
This project entails developing a MERN (MongoDB, Express.js, React, Node.js) stack application designed to handle large file uploads (files over 1GB) under significant server constraints (16GB RAM). The system must support simultaneous uploads from 100 users without extending server capacity.

## Objective
Create a robust and optimized solution using the MERN stack that facilitates the uploading of large files (up to 1GB per file) by multiple users concurrently, ensuring efficient memory management and system stability.

## Requirements

### Technical Requirements
- **Backend Framework**: Express 4.x with TypeScript
- **Frontend Library**: React 18.x with TypeScript
- **CSS Framework**: Tailwind CSS with SCSS for styling
- **Database**: MongoDB
- **Node.js Version**: 18.x
- **Concurrency**: Support for 100 simultaneous users
- **File Size Limit**: Ability to handle file uploads over 1GB

### Functional Requirements
- Users must be able to upload files larger than 1GB.
- The application should support 100 concurrent uploads.
- Implement file upload progress indicators.
- Provide clear error messages and handle exceptions gracefully.

### Performance Requirements
- Optimize memory usage to operate within the constraints of 16GB RAM.
- Minimize response times and manage back-pressure effectively.

## Architecture

### Backend
1. **Express.js Setup:** Utilize Express.js with TypeScript for routing and middleware integration.
2. **Database Integration:** Use MongoDB to store file metadata and manage upload states.
3. **Concurrency Management:** Leverage Node.js's non-blocking I/O model to handle multiple user uploads efficiently.

### Frontend
1. **React Application:** Develop the user interface with React, employing hooks and context for state management.
2. **File Upload Component:** Create a file uploader component that supports drag-and-drop and displays upload progress.
3. **Tailwind CSS and SCSS:** Style the application using Tailwind CSS for layout and SCSS for custom styles.