# MyReads


>MyReads is a bookshelf app that allows you to select and categorize books you have read, are currently reading, or want to read.

## Getting Started

Clone this repository in your computer:

```
$ git clone https://github.com/Nivax07/my-reads.git
```

### Prerequisites

The only dependency is [Node and NPM](https://nodejs.org/en/download/) (comes together with Node).

### Installing

Open a terminal at the project root and run `npm install` to install all dependencies.

### NPM scripts

- `npm run start`: runs the app in development mode
- `npm run build`: builds the app for production to the build folder
- `npm run deploy`: deploys the app to GitHub Pages
- `npm run test`: runs the test watcher in an interactive mode

## Running the project

### Development

1. Open a terminal at the app's root folder and run `npm start`
2. Start coding!

## Searching for books

Searching is currently limited to `20` books per search as well as these keywords:
```javascript
'Android', 'Art', 'Artificial Intelligence', 'Astronomy', 'Austen', 'Baseball', 'Basketball', 'Bhagat', 'Biography', 'Brief', 'Business', 'Camus', 'Cervantes', 'Christie', 'Classics', 'Comics', 'Cook', 'Cricket', 'Cycling', 'Desai', 'Design', 'Development', 'Digital Marketing', 'Drama', 'Drawing', 'Dumas', 'Education', 'Everything', 'Fantasy', 'Film', 'Finance', 'First', 'Fitness', 'Football', 'Future', 'Games', 'Gandhi', 'Homer', 'Horror', 'Hugo', 'Ibsen', 'Journey', 'Kafka', 'King', 'Lahiri', 'Larsson', 'Learn', 'Literary Fiction', 'Make', 'Manage', 'Marquez', 'Money', 'Mystery', 'Negotiate', 'Painting', 'Philosophy', 'Photography', 'Poetry', 'Production', 'Programming', 'React', 'Redux', 'River', 'Robotics', 'Rowling', 'Satire', 'Science Fiction', 'Shakespeare', 'Singh', 'Swimming', 'Tale', 'Thrun', 'Time', 'Tolstoy', 'Travel', 'Ultimate', 'Virtual Reality', 'Web Development', 'iOS'
```

### Development

1. Open a terminal at the app's root folder and run `npm start`
2. Start coding!

### Production

Click [here](https://nivax07.github.io/my-reads/) for the live version of this app.

#### :exclamation: Important :exclamation:

The service worker only works in production mode.

## Deployment

1. Configure `package.json` informing your `homepage`
2. Run `npm run deploy`
3. Access http://githubaccount.github.io/repository
