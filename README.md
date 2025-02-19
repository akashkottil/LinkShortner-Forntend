# LinkShortner-Frontend

A simple and intuitive URL shortener application built with React. This project allows users to shorten long URLs, track their usage, and manage their shortened links efficiently.

## Features

- **URL Shortening**: Easily shorten long URLs with a single click.
- **Link Management**: View and manage your shortened links in a user-friendly interface.
- **Statistics**: Track how many clicks your shortened URLs receive.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.

## Tech Stack

- **Frontend Framework**: React
- **Styling**: Tailwind CSS
- **State Management**: React Hooks
- **Testing**: React Testing Library
- **Environment Variables**: dotenv for managing API URLs

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LinkShortner-Frontend.git
   ```

2. Navigate to the project directory:
   ```bash
   cd LinkShortner-Frontend
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your API URL:
   ```plaintext
   REACT_APP_API_URL=http://your-api-url.com
   ```

5. Start the development server:
   ```bash
   npm start
   ```

## Usage

- Open your browser and navigate to `http://localhost:3000`.
- Enter a long URL in the input field and click "Shorten it!" to generate a shortened link.
- View your shortened links in the list below the input field.

## Folder Structure

```
src/
├── components/          # Reusable components
│   ├── CallToAction.jsx
│   ├── Header.jsx
│   ├── Hero.jsx
│   ├── Main.jsx
│   ├── Shortener.jsx
│   └── UrlList.jsx
├── images/             # Static images
├── App.js              # Main application component
├── index.js            # Entry point of the application
└── index.css           # Global styles
```

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for styling.
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/) - A library for testing React components.

```

Feel free to modify any sections to better fit your project's specifics or your personal preferences!