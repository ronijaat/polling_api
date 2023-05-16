# Polling system API

This is a backend api for creating questions and adding options to a specific question. Options can be voted. Questions, options can be deleted and questions can be viewed with all of their options.


## Polling system Features

- Create questions
- Add options to question
- Delete a question
- Delete an option
- Add vote to an option
- View a question with all of its options


## API Endpoints

| HTTP Verbs | Endpoints                          | Action                                 |
| ---------- | -----------------------------------| -------------------------------------- |
| POST       | /questions/create                  | To create a  question                  |
| POST       | /questions/:id/options/create      | To add options to a specific question  |
| DELETE     | /questions/:id/delete              | To delete a question                   |
| DELETE     | /options/:id/delete                | To delete an option                    |
| PUT        | /options/:id/add_vote              | To increase the count of votes         |
| GET        | /questions/:id                     | To view a question and its options     |

## Tech stack
* NodeJS
* ExpressJS
* MongoDB
* Mongoose ODM
