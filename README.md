# My Angular App

This is a simple Angular application that demonstrates a basic messaging feature. The application includes a text box for inputting messages, a send button to submit the messages, and a list to display all sent messages.

## Project Structure

```
my-angular-app
├── src
│   ├── index.html          # Main HTML file
│   ├── main.ts             # Entry point for the Angular application
│   ├── polyfills.ts        # Polyfills for browser compatibility
│   ├── styles.css          # Global styles
│   ├── app
│   │   ├── app.module.ts   # Root module of the application
│   │   ├── app.component.ts # Main component logic
│   │   ├── app.component.html # HTML template for the main component
│   │   ├── app.component.css  # Styles for the main component
│   │   ├── message.service.ts  # Service for handling messages
│   │   └── models
│   │       └── message.model.ts # Message model definition
│   └── environments
│       ├── environment.ts   # Development environment settings
│       └── environment.prod.ts # Production environment settings
├── angular.json            # Angular CLI configuration
├── package.json            # npm configuration
├── tsconfig.json           # TypeScript configuration
└── README.md               # Project documentation
```

## Features

- Input box for entering messages.
- Send button to submit messages.
- Display of all sent messages in a list.

## Getting Started

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd my-angular-app
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Run the application:
   ```
   ng serve
   ```

5. Open your browser and navigate to `http://localhost:4200` to see the application in action.

## License

This project is licensed under the MIT License.