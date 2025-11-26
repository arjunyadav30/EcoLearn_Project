# EcoLearn Project

EcoLearn is a gamified environmental education platform designed to engage students in learning about environmental conservation through interactive games, quizzes, and challenges.

## Project Contributor 

Anmol Sharma - 
Aradhy Raghuwanshi - 
Arjun Yadav - 
Prachi Ahirwar -
Neelu Thakur - 
Bittu Kumar -


## File Structure

```
EcoLearn_Project/
├── Project_Details/
│   ├── ARCHITECTURE_FLOWCHART.md
│   ├── CAMERA_FEATURE_IMPLEMENTATION.md
│   ├── CAMERA_IMPLEMENTATION_SUMMARY.md
│   ├── CAMERA_TESTING_README.md
│   ├── DEBUGGING_GUIDE.md
│   ├── HACKATHON_FEATURES_SUMMARY.md
│   ├── HACKATHON_JUDGING_CRITERIA_ALIGNMENT.md
│   ├── LOCATION_FUNCTIONALITY.md
│   ├── README_SERVER_VALIDATION.md
│   ├── SERVER_SIDE_IMPLEMENTATION.md
│   ├── SOLUTION_SUMMARY.md
│   ├── TEACHER_PROFILE_PHOTO_FEATURE.md
│   └── VIDEO_UPLOAD_FEATURE.md
├── Project_Files/
│   └── src/
│       ├── main/
│       │   ├── java/
│       │   │   ├── com/
│       │   │   │   ├── ecoeducation/
│       │   │   │   │   └── listeners/
│       │   │   │   │       └── DatabaseConnectionListener.java
│       │   │   │   ├── ecolearn/
│       │   │   │   │   ├── dao/
│       │   │   │   │   ├── db/
│       │   │   │   │   ├── model/
│       │   │   │   │   └── util/
│       │   │   │   └── mycompany/
│       │   │   │       └── sih3/
│       │   │   │           ├── entity/
│       │   │   │           │   ├── Achievement.java
│       │   │   │           │   ├── ActivityLog.java
│       │   │   │           │   ├── Challenge.java
│       │   │   │           │   ├── Game.java
│       │   │   │           │   ├── Lesson.java
│       │   │   │           │   ├── Question.java
│       │   │   │           │   ├── QuestionBank.java
│       │   │   │           │   ├── User.java
│       │   │   │           │   ├── UserAchievement.java
│       │   │   │           │   ├── UserChallenge.java
│       │   │   │           │   ├── UserGame.java
│       │   │   │           │   ├── UserStatistics.java
│       │   │   │           │   └── UserType.java
│       │   │   │           ├── repository/
│       │   │   │           │   ├── LessonRepository.java
│       │   │   │           │   ├── QuestionBankRepository.java
│       │   │   │           │   ├── QuestionRepository.java
│       │   │   │           │   └── UserRepository.java
│       │   │   │           ├── resources/
│       │   │   │           │   └── JakartaEE8Resource.java
│       │   │   │           ├── service/
│       │   │   │           ├── servlet/
│       │   │   │           │   ├── AdminAnalyticsServlet.java
│       │   │   │           │   ├── AdminBackupServlet.java
│       │   │   │           │   ├── AdminContentManagementServlet.java
│       │   │   │           │   ├── AdminUserManagementServlet.java
│       │   │   │           │   ├── QuestionServlet.java
│       │   │   │           │   ├── RankingUpdateServlet.java
│       │   │   │           │   ├── UpdatePositionServlet.java
│       │   │   │           │   └── VideoTranscriptionServlet.java
│       │   │   │           ├── util/
│       │   │   │           └── JakartaRestConfiguration.java
│       │   │   │           └── TestQuestionFetching.java
│       │   ├── resources/
│       │   │   ├── META-INF/
│       │   │   │   └── persistence.xml
│       │   │   ├── create_lessons_table.sql
│       │   │   ├── create_question_bank_table.sql
│       │   │   ├── create_questions_table.sql
│       │   │   ├── create_students_table.sql
│       │   │   ├── sample_question_bank_data.sql
│       │   │   ├── setup-question-bank.sql
│       │   │   ├── update_lessons_table.sql
│       │   │   └── update_users_table_avatar.sql
│       │   └── webapp/
│       │       ├── META-INF/
│       │       │   └── context.xml
│       │       ├── Teacher/
│       │       │   ├── add-lesson-unified.jsp
│       │       │   ├── auth_check.jsp
│       │       │   ├── class-management.jsp
│       │       │   ├── create-quiz-manual.jsp
│       │       │   ├── generate-quiz-auto.jsp
│       │       │   ├── initialize-question-bank.jsp
│       │       │   ├── manage-lessons.jsp
│       │       │   ├── manage-quizzes.jsp
│       │       │   ├── profile.jsp
│       │       │   ├── save-quiz.jsp
│       │       │   ├── search-questions-by-title.jsp
│       │       │   ├── settings.jsp
│       │       │   ├── student-progress.jsp
│       │       │   ├── teacherdashboard.jsp
│       │       │   ├── test-transcript.jsp
│       │       │   ├── updateProfile.jsp
│       │       │   ├── video-transcript.jsp
│       │       │   └── video-transcripts.jsp
│       │       ├── WEB-INF/
│       │       │   ├── beans.xml
│       │       │   └── web.xml
│       │       ├── assets/
│       │       ├── css/
│       │       │   ├── animations.css
│       │       │   ├── game.css
│       │       │   ├── main.css
│       │       │   └── style.css
│       │       ├── js/
│       │       │   ├── activity-logger.js
│       │       │   ├── ar-vr-features.js
│       │       │   ├── eco-game.js
│       │       │   ├── main.js
│       │       │   └── theme.js
│       │       ├── jsp/
│       │       │   ├── achievements.jsp
│       │       │   ├── activity-demo.jsp
│       │       │   ├── admin-add-user.jsp
│       │       │   ├── admin-analytics-dashboard.jsp
│       │       │   ├── admin-backup-dashboard.jsp
│       │       │   ├── admin-content-dashboard.jsp
│       │       │   ├── admin-dashboard.jsp
│       │       │   ├── admin-edit-user.jsp
│       │       │   ├── admin-games-management.jsp
│       │       │   ├── admin-lessons-management.jsp
│       │       │   ├── admin-quizzes-management.jsp
│       │       │   ├── admin-register.jsp
│       │       │   ├── admin-users.jsp
│       │       │   ├── admin.jsp
│       │       │   ├── admin_auth_check.jsp
│       │       │   ├── apply-database-changes.jsp
│       │       │   ├── auth_check.jsp
│       │       │   ├── challenges.jsp
│       │       │   ├── check-lessons-table.jsp
│       │       │   ├── community-impact.jsp
│       │       │   ├── complete-challenge.jsp
│       │       │   ├── complete-game.jsp
│       │       │   ├── complete-lesson.jsp
│       │       │   ├── create-database.jsp
│       │       │   ├── create-question-bank-table.jsp
│       │       │   ├── dashboard.jsp
│       │       │   ├── database-info.jsp
│       │       │   ├── debug-question.jsp
│       │       │   ├── games.jsp
│       │       │   ├── get-question.jsp
│       │       │   ├── handleImageUpload.jsp
│       │       │   ├── leaderboard.jsp
│       │       │   ├── lessons.jsp
│       │       │   ├── location.jsp
│       │       │   ├── log-user-activity.jsp
│       │       │   ├── login.jsp
│       │       │   ├── login1.jsp
│       │       │   ├── logout.jsp
│       │       │   ├── multiplayer-challenge.jsp
│       │       │   ├── plant-tree-challenge.jsp
│       │       │   ├── profile.jsp
│       │       │   ├── register.jsp
│       │       │   ├── register1.jsp
│       │       │   ├── saveSettings.jsp
│       │       │   ├── settings.jsp
│       │       │   ├── setup-question-bank.jsp
│       │       │   ├── snake-ladder-pure-jsp.jsp
│       │       │   ├── snake-ladder-quiz.jsp
│       │       │   ├── snakeladder.jsp
│       │       │   ├── startquiz.jsp
│       │       │   ├── test-activity-logging.jsp
│       │       │   ├── test-activity.jsp
│       │       │   ├── updateProfile.jsp
│       │       │   ├── updateProfileGeneral.jsp
│       │       │   ├── validate-answer.jsp
│       │       │   ├── view-lesson.jsp
│       │       │   ├── view-lessons.jsp
│       │       │   └── view-videos.jsp
│       │       ├── uploads/
│       │       │   └── transcripts/
│       │       │       ├── 1.txt
│       │       │       └── 5.txt
│       │       ├── index.jsp
│       │       ├── location.html
│       │       └── location.jsp
└── README.md
```

## Key Components

### Backend (Java)
- **Entities**: Data models for Users, Lessons, Questions, Games, Challenges, etc.
- **Repositories**: Data access layer for interacting with the database
- **Servlets**: Controllers handling HTTP requests and business logic
- **Resources**: REST API endpoints
- **SQL Scripts**: Database schema and sample data

### Frontend (JSP, HTML, CSS, JavaScript)
- **JSP Pages**: Server-side rendered pages for different functionalities
- **Teacher Portal**: Dedicated section for educators to manage content
- **CSS**: Styling files for responsive design
- **JavaScript**: Client-side interactivity and game logic
- **Assets**: Images and other static resources

### Features
- Gamified learning experience with environmental themes
- Teacher dashboard for content management
- Student progress tracking
- Interactive quizzes and challenges
- Location-based features
- Community impact visualization
- Achievement and leaderboard systems

## Technology Stack
- **Backend**: Java, Jakarta EE
- **Frontend**: JSP, HTML, CSS, JavaScript
- **Database**: SQL-based (scripts provided)
- **Server**: Compatible with standard Java web servers
