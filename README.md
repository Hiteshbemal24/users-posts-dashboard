# User Dashboard with Posts

This is a Next.js application that displays a dashboard of users. Users can be searched and sorted, and clicking on a user will show detailed information about that user along with their posts.

## Features

- **User  List**: Displays a list of users fetched from the JSONPlaceholder API.
- **Search Functionality**: Users can search by name or email.
- **Sorting**: Users can be sorted by name or company.
- **Dynamic User Detail Page**: Clicking on a user card navigates to a detailed view showing the user's information and their posts.
- **Pagination**: Posts are paginated, showing 5 posts per page.

## Technologies Used

- Next.js
- React
- React Query
- Tailwind CSS
- JSONPlaceholder API

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (version 12 or later)
- npm (Node Package Manager)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Hiteshbemal24/users-posts-dashboard/tree/main
   cd user-dashboard
   ```

2. **Install dependencies**:
    ```bash
    npm install
    ```
3. **Running the Application**:
    ```bash
    npm run dev
    ```
    - Open your browser and navigate to `http://localhost:3000`.

## Usage
- Dashboard: You will see a list of users. You can search for users by name or email and sort them by name or company.
- User Detail: Click on a user card to view detailed information about the user and their posts.
- Pagination: Posts are displayed with pagination, allowing you to navigate through multiple pages of posts.

## API Used
- Users: `https://jsonplaceholder.typicode.com/users`
- Posts: `https://jsonplaceholder.typicode.com/posts`

  ### THANK YOU
