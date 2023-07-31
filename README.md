# PollingAPI
API for Polling Questions - Coding Ninjas Backend Skill Test Project

Task: Need to create an API where anyone can create questions with options and also add votes to it

---

## Features
- Create a question
- Add options to a question
- Add a vote to an option of question
- Delete a question → (optional: A question can’t be deleted if one of it’s options has votes)
- Delete an option → (optional: An option can’t be deleted if it has even one vote given to it)
- View a question with it’s options and all the votes given to it

## Required Routes
* Create Question :-
``` localhost:8000/api/v1/questions/create/ ```

* Create Option :-
``` localhost:8000/api/v1/options/:id/options/create/ ```

* View Question :-
``` localhost:8000/api/v1/questions/:id/ ```

* Delete Option :-
``` localhost:8000/api/v1/options/:id/delete ```

* Delete Question :-
``` localhost:8000/api/v1/questions/:id/delete ```

## Folder Structure
```
CSV_Upload/
|── |config/
│   |      ├── mongoose.js
|   |
├── routes/
│   |      ├── api/
│   ├── index.js
|   |
├── controllers/
│   ├── OptionsController.js
│   ├── QuestionsController.js
|   |
├── models/
│   ├── options.js
│   ├── questions.js
|   |
├── package-lock.json
├── package.json
├── README.md
