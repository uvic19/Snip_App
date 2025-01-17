# Snip Manager

**Snip Manager** is a React-based application designed for managing snippets of information. It provides an intuitive interface for users to create, update, delete, and reset snippets, ensuring data persistence through local storage. The app enhances user experience with real-time feedback via toast notifications, allowing for seamless interaction.

## Features

- **Create Snippets**: Add new snippets with a unique title and content. Each snippet is automatically assigned a unique ID.
- **Update Snippets**: Edit existing snippets easily, allowing for quick modifications without losing data.
- **Delete Snippets**: Remove snippets that are no longer needed. The app will confirm the action and provide feedback on successful deletion.
- **Reset Snippets**: Clear all snippets from the application and local storage in one go. This feature is helpful for users who want a fresh start.
- **Data Persistence**: All snippets are stored in local storage, ensuring they remain available even after refreshing the page or reopening the browser.
- **User Notifications**: Notifications for actions such as creating, updating, and deleting snippets are displayed using toast messages, making the application more interactive and user-friendly.

## Tech Stack

- **React**: The core library used for building the user interface, enabling the development of reusable UI components.
- **Redux Toolkit**: A powerful state management library that simplifies the process of managing complex state in React applications.
- **React Hot Toast**: A lightweight library that provides customizable toast notifications, enhancing user experience with real-time feedback.
- **JavaScript**: The programming language used for implementing application logic and features.
- **HTML/CSS**: Used for structuring and styling the user interface, ensuring a responsive and aesthetically pleasing design.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:
   ```bash
   cd <project-directory>
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Start the development server**:
   ```bash
   npm start
   ```

5. **Open your browser** and navigate to `http://localhost:3000` to view the application.

## Usage

1. **Adding a Snippet**: 
   - Enter a title and content for your snippet in the input fields.
   - Click the **"Add Snip"** button to create a new snippet. If a snippet with the same title already exists, an error notification will appear.

2. **Updating a Snippet**:
   - Click on the snippet you wish to edit, make your changes, and save. A success notification will confirm the update.

3. **Deleting a Snippet**:
   - Click on the delete icon associated with the snippet. A confirmation toast will notify you that the snippet has been successfully deleted.

4. **Resetting All Snippets**:
   - Click the **"Reset Snips"** button to remove all snippets and clear local storage. A confirmation message will appear.

5. **Notifications**: 
   - After every action, you will receive a toast notification at the bottom of the screen indicating the success or failure of your action.

## Example Snippet Structure

When creating a snippet, the structure includes:
```json
{
  "_id": "unique-id",
  "title": "Snippet Title",
  "content": "Snippet Content"
}
```

## Contributing

Contributions are welcome! If you have suggestions for improvements, feel free to submit a pull request or open an issue. Make sure to follow the standard coding practices and add relevant tests if necessary.

### To Contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```

4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- Thank you to the contributors and libraries that made this project possible.
- Special thanks to the open-source community for their invaluable resources and support.
