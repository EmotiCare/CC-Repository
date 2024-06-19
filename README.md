# Cloud Computing

## API
1. [Tools & Requirements](#tools-cc)
2. [Endpoints](#endpoint-emoticare)
   - [Authentication](#endpoint-authentication)
   - [Mood](#endpoint-mood)
   - [Photo](#photo-user)
   - [Predict](#predict-emoticare)

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
5. JWT Authentication

## Endpoints
### Authentication
**POST** ```http://34.101.52.60:3000/auth/register```

Endpoint for user registration
![auth-regist](https://github.com/EmotiCare/CC-Repository/assets/89828723/2f4d618c-0587-433c-971c-104225022308)

**POST** ```http://34.101.52.60:3000/auth/login``` 

Endpoint for user login
![auth-login](https://github.com/EmotiCare/CC-Repository/assets/89828723/67744c7e-957d-4bac-a68c-013ed8ba5f42)

**POST** ```http://34.101.52.60:3000/auth/logout``` 

Endpoint for user logout
![auth-logout](https://github.com/EmotiCare/CC-Repository/assets/89828723/112e2d59-fc05-4e5f-954c-3fa6e3086474)

**GET** ```http://34.101.52.60:3000/user/:id``` 

Endpoint to retrieve user details by ID
![user-id](https://github.com/EmotiCare/CC-Repository/assets/89828723/fc29447c-b693-4109-b1a6-16099696148f)

### Mood
**POST** ```http://34.101.52.60:3000/mood/create/yyyy-mm-dd/:mood```

Endpoint to create a mood entry for a specific date (yyyy-mm-dd) with a specified mood
![post-mood-date](https://github.com/EmotiCare/CC-Repository/assets/89828723/baea0140-cfc3-4650-a615-e01dc94e1ce8)

**PUT** ```http://34.101.52.60:3000/mood/update/yyyy-mm-dd/:mood```

Endpoint to update the mood entry for a specific date (yyyy-mm-dd) with a new mood
![put-mood-date](https://github.com/EmotiCare/CC-Repository/assets/89828723/5d0b6405-6c13-4413-9909-6aa815c16904)

**GET** ```http://34.101.52.60:3000/mood/yyyy-mm-dd```

Endpoint to retrieve the mood entry for a specific date (yyyy-mm-dd)
![get-mood-date](https://github.com/EmotiCare/CC-Repository/assets/89828723/d13a551e-4661-4d56-a0b1-a3a0d936c6bb)

**GET** ```http://34.101.52.60:3000/mood/get/all ```

Endpoint to retrieve all mood entries

![get-mood-all](https://github.com/EmotiCare/CC-Repository/assets/89828723/b0e0480c-9115-4bc5-891b-abe537fb9e3b)

### Photo
**POST** ```http://34.101.52.60:3000/photo/upload```

Endpoint to upload a photo profile

**GET** ```http://34.101.52.60:3000/photo/get```

Endpoint to retrieve photos

### Predict
**POST** ```http://34.101.52.60:5000/predict```

Endpoint to make predictions for ChatBot
![predict-request](https://github.com/EmotiCare/CC-Repository/assets/89828723/762c9a64-ebf7-4a69-8f70-df948ceb1b12)
![predict-response](https://github.com/EmotiCare/CC-Repository/assets/89828723/29fb6600-b7ce-483e-87ee-d57cb86cd5d3)
