# Task Tracker app (Angular)

Angular Crash Course 2021 from [Traversy Media](https://www.youtube.com/watch?v=3dHNOWTI7H8&list=WL&index=41&t=3673s).
It includes the Angular ui as well as JSON-server for our mock backend


## Getting Started
### Prerequisites

Make sure Node and npm are installed from the terminal

```bash
$ node -v
$ npm -v
```

---
## Installation

1. Fork this repo into your own GitHub

2. Clone the repo to your local machine

```bash
# Change to the desired directory
$ cd <desired-directory>

# Clone the repo
$ git clone https://github.com/Megumikawa/task-tracker.git

# Change to the project directory
$ cd tasktracker
```

3. Install dependencies

```bash
$ npm install
```

4. Install npm JSON Server package
- Install JSON Server used:[JSON Server](https://www.npmjs.com/package/json-server): <http://localhost:3000/>
```bash
$ npm install -g json-server
```

- Start JSON Server
```bash
$ json-server --watch db.json
```


Run Angular server: <http://localhost:4200>

```bash
$ ng serve
```

## Local Development

After this initial set-up, you can start with:
- for client should be running at : <http://localhost:4200/>.  
```bash
$ npm start
```

- for the server
```bash
$ npm run server 
 ```




## Command to create new component

Run `ng generate component component-name` to generate a new component. 

## To Build

Run `ng build` to build the project. 


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
