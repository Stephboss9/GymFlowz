# GymBro

Created: January 2, 2024 12:40 AM

Web App Features:

ChatGPT’s Recommendations: 

[ChatGPT’s recommendations](https://www.notion.so/ChatGPT-s-recommendations-b0ee7b808639407281d5a52231d587f0?pvs=21)

### Main/Basic Features for the app:

1. A user can register an account on the web app 
    
    **Purpose:** Each user has access to their data and theirs only, no one else can access it without their credentials. This ensures that each user only has access to their data, and can customize/control their experience
    
    **Specifics:**
    
    - Register an account
    - Login
    
    Note: Make sure to account for security here (SQL injection, XSS, CSRF)
    
2. A user can create workout routines using exercises from an API and add custom ones
    
    **Purpose**: Allows for customization and control over workout routines
    
    **Specifics:**
    
    - Name the routine
    - Add exercises from the list of exercises (API) or add a custom one
    - Specify the sets, and reps (optional)
    - potential add feature: Can share this routine to their phones to use on the go
    - Perform this on a dedicated page (Routines)
    
    Notes:
    
    - Consider implementing a search and filter functionality within the exercise database to make it easier for users to find specific exercises.
    
3. A user can log their workouts 
    
    **Purpose**: Allows them to keep track of their progress
    
    **Specifics:**
    
    - Can log a workout using one of the exercise routine templates they’ve created, or customize
    - can keep track of sets, and reps
    - can log time spent and post-workout notes about how the workout went using emojis/words
    
4. A user can set fitness goals for themselves
    
    **Purpose:** Allow them to keep track of their goals and progress of goals
    
    **Specifics:**
    
    - Name the Goal
    - provide a description/overview
    - Set a start and end date
    - Check a goal once it has been completed
    - examples: hit a certain weight for a certain number of reps, go to the gym at least 3 times a week
    

### Advanced Features:

1. Users can add each other as friends
    - See each other's routines, celebrate each other's workouts
    - Can rate each other's routines

1. Users can track their progress through graphs and other visualizations
    - Show progress for bench press over time through a graph, weight on the y-axis, and time on the x-axis
    - Max weight lifted for each exercise
    - Average number of reps for a given set for a given exercise
    - Number of workouts done during the week
    - average number of workouts completed during the month
    
2. A user can explore a catalog of exercise routines created by other users, and rate/review them
    
    **Purpose:** Allows the user to explore and try other routines that they may not have thought of
    
    **Specifics:**
    
    - Can add other users’ routines to their list of routines
    - Can provide a review of others’ routines