# rn-assignment3-11336088
# React Native Task Manager

This project is a simple task manager app built using React Native. It allows users to manage their tasks across different categories.

## Components

### TaskItem

The `TaskItem` component is responsible for rendering individual task items. Each task item displays the task text and, optionally, an associated image. Users can interact with task items by clicking on them.

### Category

The `Category` component represents a category of tasks. It displays the category title and a list of tasks belonging to that category. If there are no tasks available in the category, a message indicating the absence of tasks is displayed.

### App

The `App` component serves as the main entry point for the application. It manages the state of tasks and provides functionality for adding new tasks. The `App` component also renders the header, input field for adding tasks, and the list of categories along with their respective tasks.

## Usage

1. **TaskItem**: The `TaskItem` component is used within the `Category` component to display individual tasks. It receives a `task` object as a prop, which contains information about the task such as text and image URL.

2. **Category**: The `Category` component is used within the `App` component to display tasks grouped by category. It receives the `category` name and an array of `tasks` belonging to that category as props.

3. **App**: The `App` component is the main component of the application. It renders the header, input field for adding tasks, and the list of categories along with their respective tasks. It manages the state of tasks and provides functionality for adding new tasks.

## Installation

To run the app locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using npm or yarn: `npm install` or `yarn install`.
4. Start the Metro bundler: `npm start` or `yarn start`.
5. Run the app on your preferred platform using Expo.

## Contributing

Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull requests to help improve the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
