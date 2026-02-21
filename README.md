# RandomFinder

A simple, elegant web application for randomly selecting a winner from a list of participants. Perfect for raffles, giveaways, team selections, or any situation where you need to pick a random person fairly.

## 🎯 Features

- **Add Participants**: Easily add multiple participants by entering their names
- **Visual List**: See all participants displayed as colorful name tags
- **Remove Participants**: Click on any name tag to remove a participant from the list
- **Random Selection**: Randomly pick a winner from all participants
- **Run Again**: Select another winner from the same list without re-entering names
- **Start Fresh**: Clear all participants and begin a new session
- **Input Validation**:
    - Prevents duplicate names
    - Prevents empty entries
    - Requires at least 2 participants to select a winner

## 🚀 Demo

The application features a clean, centered interface with:

- A participant input field with an "ADD" button
- A live list of all participating names
- A "Get The Winner" button to trigger the random selection
- A results screen showing the winner with options to run again or start over

## 📋 Prerequisites

No installation required! This is a pure HTML/CSS/JavaScript application that runs directly in any modern web browser.

## 🛠️ Installation

1. Clone or download this repository:

    ```bash
    git clone https://github.com/yourusername/RandomFinder.git
    ```

2. Navigate to the project directory:

    ```bash
    cd RandomFinder
    ```

3. Open `index.html` in your web browser:
    - Double-click the `index.html` file, or
    - Right-click and select "Open with" your preferred browser, or
    - Use a local server (recommended for development)

## 💻 Usage

1. **Adding Participants**:
    - Enter a participant's name in the input field
    - Click the "ADD" button or press Enter
    - The name will appear as a colored tag below

2. **Managing the List**:
    - Click on any name tag to remove that participant
    - Add as many participants as needed (minimum 2 required)

3. **Selecting a Winner**:
    - Click "Get The Winner" button
    - The application will randomly select one participant
    - The winner's name will be displayed on a new screen

4. **After Selection**:
    - **Run Again**: Pick another winner from the same list of participants
    - **Start Again**: Clear everything and create a new participant list

## 📁 Project Structure

```
RandomFinder/
│
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Custom styles and layout
├── js/
│   └── main.js        # Application logic and functionality
└── README.md          # Project documentation
```

## 🎨 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling and transitions
- **JavaScript (ES5)**: Core application logic
- **Bootstrap 4**: Grid system and responsive layout
- **Google Fonts**: Oswald font family

## 🔧 Technical Details

### Core Functionality

The application is built using vanilla JavaScript with an object-oriented approach:

- **Constructor Pattern**: Uses a constructor function (`getPayer`) to encapsulate all functionality
- **Event Listeners**: Handles user interactions (add, delete, select winner)
- **DOM Manipulation**: Dynamic updates to the participant list and results display
- **Random Selection**: Uses `Math.random()` for fair, unbiased selection

### Key Methods

- `addApplicants()`: Handles adding new participants
- `showList()`: Renders the participant list
- `checkValid()`: Validates user input
- `getRandomUser()`: Initiates the winner selection process
- `showRandomUser()`: Displays the randomly selected winner
- `deleteOne()`: Removes individual participants
- `runAgain()`: Selects a new winner from existing list
- `startAgain()`: Resets the entire application

## 🎭 Customization

### Changing Colors

Edit `css/style.css` to customize the color scheme:

```css
/* Primary color (buttons and tags) */
background: #3f51b5;

/* Accent color (headings and hover states) */
color: darkred;
```

### Modifying Text

Edit `index.html` to change the heading or button text:

```html
<h1>Who Is The Lucky Person ?</h1>
```

### Adjusting Validation Rules

Modify `checkValid()` in `js/main.js` to customize validation logic.

## 🌐 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Potential Improvements

- Add animations for winner reveal
- Include sound effects
- Add export/import functionality for participant lists
- Implement multiple winner selection
- Add dark mode
- Make the application fully responsive for mobile devices
- Add keyboard shortcuts (Enter to add, Escape to cancel)
- Store participant lists in localStorage
- Add participant statistics (how many times selected)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Mohammad Inamul Hassan M

## 🙏 Acknowledgments

- Bootstrap for the responsive grid system
- Google Fonts for the Oswald typeface
- Inspiration from raffle and giveaway applications

## 📞 Support

If you encounter any issues or have questions:

1. Check the existing issues in the repository
2. Create a new issue with a detailed description
3. Include browser information and steps to reproduce

---

**Enjoy picking random winners fairly and fun! 🎉**
