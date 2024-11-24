## The project "Joint tasks"

### Implemented functionality:

- Display a list of tasks with their description and statuses;
- Ability to create, delete and edit tasks;
- Authorization;
- Any user can view the list of open tasks;
- An authorized user can create and view all tasks;
- You can only edit your own tasks;

Authorization using JWT.

### Installation

```bash
npm install
npm run build
```

### Launch

```bash
# Set the environment variable before starting the project
export JWT_SECRET=<secret string>

cd backend
npm install
npm run app
```
