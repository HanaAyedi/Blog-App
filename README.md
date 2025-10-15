# Blog App

A modern Blog web application built with React and TypeScript. Create, browse, edit, and delete blog posts with a responsive and user-friendly interface.

---

## Features

### Blog Post List
- Paginated list of blog posts showing title, excerpt, and image.
- Search bar to filter posts by title.
- Sort posts by date or title in ascending/descending order.
- Loading state and graceful handling when no posts are found.
- Responsive grid layout.

### Blog Post Detail
- Displays full post content, title, image, and creation date.
- Edit and Delete buttons with confirmation modal.
- Back button to return to the blog list.
- Clean card-based design.

### Create & Edit Blog Post
- Form with title, content (WYSIWYG editor optional), and optional image URL.
- Redirects to detail page after successful submission.
- Validation for required fields (title and content).
- Cancel button to return without saving changes.

### Modern Design
- Fully responsive for mobile, tablet, and desktop.
- Stylish cards, buttons, and form layout.
- Smooth hover effects for cards and buttons.

---

## Getting Started

### Prerequisites
- Node.js v20+  
- npm v10+

### Installation
```bash
# Clone the repository
git clone https://github.com/HanaAyedi/Blog-App.git
cd blog-app

# Install dependencies
npm install

# Start the development server
npm start
