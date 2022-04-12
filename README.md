# Task Tracker app (Angular)
<img align="right" src="https://user-images.githubusercontent.com/55644602/141805893-fcbb1e38-ed66-47a3-8a76-3b4e96b29f86.gif">

Angular Crash Course 2021 from Traversy Media.
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
npm install
```

4. Install npm JSON Server package
- Install [JSON Server](https://www.npmjs.com/package/json-server)used: `http://localhost:3000/`
```bash
npm install -g json-server
```

- Start JSON Server
```bash
json-server --watch db.json
```


Run Angular server: `http://localhost:4200`

```bash
ng serve
```

## Local Development

After this initial set-up, you can start with:
- for client should be running at : `http://localhost:4200/`
```bash
npm start
```
- for the server
```bash
npm run server 
```




## Usage

- Command to create new component
Run this to generate a new component. 
```bash
ng generate component component-name
```

- To build
Run this to build the project. 
```bash
ng build
```



## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
