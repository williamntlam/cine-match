
# CineMatch - Movie Recommendation System

**Side Project w/ Neo4j**  
**Built with the MERN Stack and Neo4j Graph Database**

---

## Overview

CineMatch is a movie recommendation system designed to enhance your movie discovery experience. Leveraging the power of the **MERN stack** (MongoDB, Express.js, React, Node.js) and the graph database **Neo4j**, CineMatch provides personalized movie recommendations based on user preferences, ratings, and relationships between movies, genres, directors, and actors.

---

## Todo
[] Currently learning **Neo4j** and **Cypher Query Language** to deepen understanding of graph databases and query optimization.

---

## Key Features

### 1. **Rich Movie Database**
- Extensive collection of movies with detailed metadata:
  - **Genres**: Easily explore movies in your favorite genres.
  - **Directors and Actors**: Connect with creators and stars of the movies.
- Relationships between movies, genres, directors, and actors are modeled to allow for complex, real-world connections.

### 2. **User Profiles**
- Each user has a personalized profile containing:
  - **Ratings**: Rate movies you've watched.
  - **Watchlists**: Keep track of movies you want to see.
- User activity helps refine recommendations and ensures tailored suggestions.

### 3. **Recommendation Engine**
- **Collaborative Filtering**: Suggests movies based on the preferences of users with similar tastes.
- **Content-Based Recommendations**: Recommends movies based on similar genres, directors, or actors from your watch history or favorites.
- Powered by **Neo4j Cypher queries** to leverage relationships in the graph database effectively.

---

## Learning Focus

### 1. **Graph Database Mastery**
- Understand and model relationships between complex entities such as:
  - Users ↔ Movies ↔ Genres
  - Directors ↔ Actors ↔ Movies
- Use **Neo4j** to handle relationships that traditional databases struggle with.

### 2. **Cypher Query Language**
- Write efficient **Cypher queries** to:
  - Filter and search for movies based on user preferences.
  - Retrieve recommendations by identifying patterns in the graph.
  - Explore shortest paths and other graph-based analytics for insights.

### 3. **MERN Stack Integration**
- Use **MongoDB** for user authentication and data unrelated to graph relationships.
- Build a robust backend with **Express.js** and **Node.js**.
- Create an interactive frontend with **React**, allowing users to seamlessly explore, rate, and discover movies.

---

## Why CineMatch?

- **Personalized Experience**: Focused on delivering recommendations users truly want.
- **Scalable Design**: Built with modern web technologies to handle increasing data and complexity.
- **Hands-On Learning**: Dive deep into both the MERN stack and graph database concepts, improving development and database management skills.

---

## Future Enhancements
- Implement advanced filtering options for recommendations.
- Add social features (e.g., follow other users, share watchlists).
- Introduce advanced analytics dashboards for movie trends.
- Migrate to a cloud-hosted Neo4j and MongoDB setup for scalability.

---
