**LinkVault** is a personal link management web application that allows users to organize frequently used websites into customizable categories. This app is especially useful for saving educational resources, coding sites, research material, and other useful links, all accessible from a single interface.

## Features

- **Category-based Link Organization**: Easily group links into sections like "School," "Coding/Reading," "AI," and more.
- **Link Editing**: Add new links, update URLs, and remove outdated links.
- **Local Storage**: Saves all link data to local storage, ensuring persistence across sessions.
- **Responsive Design**: The layout adapts to various screen sizes for a seamless experience on mobile and desktop devices.
- **Lightweight UI**: Minimalistic interface with user-friendly editing and navigation.

## Structure

The application structure consists of:
- **Sections**: Each category, like "School," "Design," and "Research," is presented as a section with the ability to view, add, or delete links.
- **Edit Mode**: Each section has an "Edit Links" button, enabling users to add or delete links as needed.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LinkVault.git
   ```
2. Open the `index.html` file in your preferred browser.

## Usage

1. **Add Links**: 
   - Select the category by clicking "Edit Links."
   - Enter the link title and URL in the input fields.
   - Click "Add Link" to save it to the category.

2. **Delete Links**:
   - While in edit mode, click the "Delete" button beside a saved link to remove it.

3. **Persistent Storage**:
   - All links are saved locally, so even if the page is refreshed, your saved links remain available.

## Customization

- **CSS Styling**: Modify the CSS section in `index.html` to customize the theme, colors, or layout.
- **JavaScript Functionality**: Enhance or change features by modifying the JavaScript functions for additional link or category functionalities.

## Technical Details

- **HTML/CSS**: Provides structure and design for an organized user interface.
- **JavaScript (Vanilla)**: Manages the addition, deletion, and storage of links through the local storage API.
- **Local Storage**: All links are stored in the browser's local storage, enabling data persistence without requiring a backend.

## Contributing

1. Fork the repository.
2. Create a new branch (`feature/new-feature`).
3. Commit your changes.
4. Push the branch and create a pull request.

---

**Note**: This app uses local storage for persistence. Clearing your browser's cache will delete the stored links.
