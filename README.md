# Community-Based Social Media Platform (Java Springboot Backend)
## Overview
This project is a community-based social media platform where users can join communities, share their thoughts, interests, and opinions, and interact with other users. Users can like posts, leave comments, view > a feed of posts from communities they have joined, and view posts from people they follow.

## Features
- User Authentication and Authorization
- Sign up, login, and logout functionality.
- JWT-based security for APIs.

## User Profiles
- Users can create and update their profiles.
- Users can follow and unfollow other users.

## Communities
- Users can create, join, and leave communities.
- Users can view posts from the communities they have joined.

## Posts and Comments
- Users can create, edit, and delete posts.
- Users can like and comment on posts.
- Users can view and interact with posts from communities they belong to or from users they follow.

## Feed
- Personalized feed showing posts from communities the user has joined and from users they follow.

## Technology Stack
- Backend: Java Spring Boot
- Database: PostgreSQL
- Security: Spring Security with JWT
- Build Tool: Maven
- ORM: Hibernate/JPA

## Prerequisites
- Java 17+
- Maven 3+
- PostgreSQL 13+

## Installation
Clone the repository:
- git clone https://aniket156/Community_Based_Social_Media_Platform.git

Configure PostgreSQL:
- Create a database named social_media.
- Update the application.properties with your PostgreSQL credentials.

Example:
- spring.datasource.url=jdbc:postgresql://localhost:5432/social_media
- spring.datasource.username=your_db_username
- spring.datasource.password=your_db_password
- spring.jpa.hibernate.ddl-auto=update
