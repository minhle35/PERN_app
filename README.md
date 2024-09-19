### Front End: React
| Action   | HTTP Method     |
|----------|-----------------|
| Create   | HTTP POST       |
| Read     | HTTP GET        |
| Update   | HTTP PUT        |
| Delete   | HTTP DELETE     |

### Backend

**Node/Express**
| Action                                          |
|------------------------------------------------|
| Perform data cleaning                          |
| Send information to Postgres                   |
| Send back confirmation status to React         |

**Error Handling**
| Action                                          |
|------------------------------------------------|
| Handle validation errors in requests           |
| Return appropriate HTTP status codes           |
| Log errors for debugging                        |

**Postgres**
| Action                                                |
|------------------------------------------------------|
| Perform corresponding actions to requests from Node  |

### Authentication
| Method                         | Description                                   |
|--------------------------------|-----------------------------------------------|
| Token-based authentication     | Use JWT (JSON Web Tokens) for user sessions  |
| Session management             | Store user sessions securely in the database  |



### Description of Data Flow

1. **User Actions**: Users interact with the React front end (e.g., submitting a form, clicking buttons).
2. **HTTP Requests**: The front end sends HTTP requests to the Node/Express backend based on user actions.
3. **Data Processing**: The backend processes the requests, performing any necessary data cleaning and validation.
4. **Database Interaction**: The backend communicates with the Postgres database to store or retrieve data.
5. **Response**: The backend sends a response back to the React front end, including confirmation status or requested data.
6. **UI Update**: The front end updates the user interface based on the response received.

### Note on Diagram Creation


