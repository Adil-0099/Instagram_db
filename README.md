# InstagramDB – SQL Clone of Instagram's Core Database

This project is a simplified SQL-based clone of Instagram's core relational database, designed for practicing and demonstrating database schema design, SQL queries, and data modeling concepts.

## 🧠 About the Project

This SQL script (`instagramdb.sql`) creates a mock database named `ig_clone`, simulating the key functionalities of Instagram including:

- User accounts
- Posts (photos)
- Comments
- Likes
- Follows
- Tags

It includes sample data to allow for testing, querying, and analysis.

## 🏗️ Database Schema

Here’s a breakdown of the main tables and their purpose:

| Table Name     | Description                                 |
|----------------|---------------------------------------------|
| `users`        | Stores user info (username, join date)      |
| `photos`       | User-uploaded images                        |
| `comments`     | Comments on photos by users                 |
| `likes`        | Records which user liked which photo        |
| `follows`      | Tracks user follow relationships            |
| `tags`         | Stores hashtags/tags                        |
| `photo_tags`   | Junction table between photos and tags      |

Each table is normalized and uses appropriate primary and foreign key constraints.

## ⚙️ Setup Instructions

To use this SQL file:

1. Open your MySQL or compatible SQL environment (like MySQL Workbench, XAMPP, or CLI).
2. Run the `instagramdb.sql` script to create and populate the `ig_clone` database.

```bash
mysql -u your_username -p < instagramdb.sql


