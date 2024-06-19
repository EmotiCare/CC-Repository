# Cloud Computing

## API
1. [Tools & Requirements](#tools-cc)
2. [Endpoints](#endpoint-emoticare)
   - [Authentication](#endpoint-authentication)
   - [Mood](#endpoint-mood)

## Tools & Requirements
### Tools
1. Visual Studio Code
2. Postman
3. Google Cloud Platform
4. Google Identity Platform
5. Google Compute Engine
7. Firestore
8. Cloud Storage

### Requirements
1. Node.js
2. Express
3. Python
4. Flask

## Endpoints
### Authentication
**POST** ```http://34.101.52.60:3000/auth/register```


**POST** ```http://34.101.52.60:3000/auth/login``` 

**POST** ```http://34.101.52.60:3000/auth/logout``` 

**GET** ```http://34.101.52.60:3000/user/:id``` 

### Mood
**POST** ```http://34.101.52.60:3000/mood/create/yyyy-mm-dd/:mood```

**PUT** ```http://34.101.52.60:3000/mood/update/yyyy-mm-dd/:mood```

**GET** ```http://34.101.52.60:3000/mood/yyyy-mm-dd```

**GET** ```http://34.101.52.60:3000/mood/get/all ```
