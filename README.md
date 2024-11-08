# CS-361 Course Project

## Overview
Welcome to Movie Hub, a program to track your watched movies in one central location. This project utilizes a microservice architecture to send out movie suggestion reminders, AI recommendations, allow users to register an account, and view the top 10 most popular movies of the week.

## Microservices
1. Movie Suggestion Reminders

2. AI Recommendations

3. Authentication Services

4. Trending Movies

## Project Structure
```
movie_hub/
├── main.py                    # Main CLI program
├── reminder_service/
│   └── reminder.py            # Handles movie reminders
├── recommendation_service/
│   └── recommend.py           # AI recommendations based on the user catalog
├── authentication_service/
│   └── auth.py                # Handles user login, registration, and token verification
├── popular_movies_service/
│   └── popular.py             # Fetches popular movies of the week
```
