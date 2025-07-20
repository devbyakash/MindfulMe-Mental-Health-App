MindfulMe is a comprehensive mental wellness web application designed to help users track and improve their mental well-being through a suite of integrated tools. The project is built with a modern frontend using HTML and Tailwind CSS, and it is powered by a Supabase backend for user authentication and data storage.

### Core Features:

**1. User Authentication & Profile Management:**
-   **Secure Sign-up and Login:** Users can create an account or log in securely using their email and password. The authentication system includes password validation to ensure strength.
-   **User Profile:** Once logged in, the application personalizes the experience, displaying the user's email and an avatar. A profile dropdown menu allows users to log out.

**2. Interactive Dashboard (`dashboard.html`):**
The central hub of the application provides a holistic overview of the user's mental wellness at a glance.
-   **Welcome Message:** Greets the user upon logging in.
-   **Quick-View Cards:**
    -   **MBTI Profile:** Displays the user's latest Myers-Briggs Type Indicator (MBTI) result.
    -   **Mood Tracker:** Shows the most recently logged mood, complete with a corresponding emoji.
    -   **Meditation Player:** An embedded audio player with controls (play/pause, next, previous) for guided meditation tracks.
    -   **Calendar:** A mini-calendar that highlights the current date.
-   **Latest News:** A feed of recent articles related to mental health, which can be refreshed by the user.
-   **Today's Tasks:** A summary of daily wellbeing tasks to encourage healthy habits.

**3. MBTI Personality Test (`mbti.html`):**
This feature allows users to discover their personality type.
-   **15-Question Test:** Users answer a series of questions to determine their four-letter MBTI type (e.g., ISTJ, ENFP).
-   **Instant Results:** Upon completion, a modal window displays the resulting personality type and a detailed description.
-   **Data Storage:** The test results, including individual scores for each dimension (e.g., Introversion/Extraversion, Sensing/Intuition), are saved to the Supabase database.

**4. Mood Tracker (`mood.html`):**
A visually engaging tool for logging daily emotions.
-   **Emotion Selection:** Users can choose from a grid of ten emotions (e.g., Happy, Calm, Anxious), each represented by a unique SVG icon and color scheme.
-   **Dynamic Backgrounds:** The page features animated backgrounds and confetti effects that change based on the selected mood, creating an immersive experience.
-   **Database Integration:** Mood entries are saved to Supabase, linking them to the logged-in user.

**5. Mental Health News (`news.html`):**
Keeps users informed with the latest articles and insights on mental wellness.
-   **Article Feed:** Displays a grid of news articles fetched from a news API, with fallback data to ensure content is always available.
-   **Infinite Scrolling:** Users can load more articles as they scroll, providing a continuous stream of information.
-   **Direct Links:** Each article summary includes a link to read the full story on the original source's website.

**6. Wellbeing Tasks (`task.html`):**
A tool designed to help users build healthy habits through daily activities.
-   **Task List:** Presents ten daily tasks focused on mental health, such as meditation, expressing gratitude, and taking a nature walk.
-   **Progress Tracking:** Users can check off completed tasks. A progress ring and a counter dynamically update to show the percentage of tasks completed.
-   **Local Storage:** Task completion status is saved in the browser's local storage, allowing progress to persist between sessions.

The project's frontend is styled using **Tailwind CSS**, with custom color variables and fonts ('Inter' and 'Space Grotesk') to create a clean, modern, and cohesive user interface across all pages. JavaScript is used to handle dynamic content, user interactions, and communication with the Supabase backend.


https://github.com/user-attachments/assets/def5fed2-6a06-4f88-81af-82b37507e379

