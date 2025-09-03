# QuickJot App

- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT, bcrypt
- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Containerization**: Docker & Docker Compose

## Usage

1. **Register/Login**: Create an account or log in with existing credentials
2. **Create Notes**: Use the form at the top to create new notes
3. **View Notes**: All your notes are displayed in a responsive grid layout
4. **Edit Notes**: Click on any note to open the edit modal
5. **Delete Notes**: Use the delete button in the edit modal to remove notes

## Security Features

- **Password Hashing**: Passwords are hashed using bcrypt with salt rounds
- **JWT Authentication**: Secure token-based authentication
- **Input Validation**: Server-side validation for all inputs
- **SQL Injection Protection**: Parameterized queries using pg library
- **CORS**: Cross-origin resource sharing enabled for development

