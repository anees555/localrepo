graph TD
    A[Frontend (React/HTML/CSS)] -->|API Calls| B[Backend (FastAPI, WebSocket)]
    B -->|Database Queries| C[Database (PostgreSQL)]
    
    A1[Registration/Login (Forms, Validation)] --> A
    A2[Friend Recommendations (Cosine Similarity)] --> A
    A3[Real-Time Chat (WebSocket)] --> A
    
    B1[Profile Management (Create, Update)] --> B
    B2[Friend Recommendations (Cosine Similarity)] --> B
    B3[Real-Time Chat API (WebSocket)] --> B
    
    C1[User Information (ID, Bio, Interests, Connections)] --> C
    C2[Messages, Chat History] --> C
