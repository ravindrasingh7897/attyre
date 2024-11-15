# Attyre Color Palette Generator
A web application that recommends personalized color palettes and colors to avoid based on user preferences and attributes.


## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Details](#api-details)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)


## Features
- Generate customized color palettes based on user inputs.
- Show both palettes for "Colors to avoid" and "Recommended colors"
- Mock API integration for dynamic responses using Postman.
- UI built with React.
- Show alerts where needed.
- Required color selections to genrate palette.
- Have optional Advanced Preferences.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
2. cd repository-name
3. npm install
4. npm install -D tailwindcss >> npx tailwindcss init
 5. npm install axios  <!-- for api calls -->
6. npm install react-dropzone <!-- for File handling and image upload -->
7. npm install  color-thief-react <!-- for Image analysis (for basic color extraction) -->
8. npm start


## Usage
- Open the app in your browser at `http://localhost:3000/`.
- Add and image for which you want to genrate a color pallete.
- Select Required colors such as Skin, Eye and Hair  from uploaded photo.
- Select Optional Advanced Preferences. That contains options such as Color Intensity, Seasonal, Occasion-Based, and Personal Style.
- View the generated color palette and recommendations.


## API Details
- **POST Request**:
  - Endpoint: `https://61caa913-f113-46c6-9697-4a520e742c7c.mock.pstmn.io/generate-palette`
  - Example Payload:
    ```json
    {
      "skin_color": "fair",
      "eye_color": "blue",
      "hair_color": "brown",
      "undertone": "warm",
      "preferences": "vivid colors"
    }
    ```
  - Example Response:
    ```json
    {
      "the data that provided in the assignment "
    }
    ```
## Screenshots
![Navbar](./public/screenshots/Navbar.png)
![Home Page](./public/screenshots/HomePage.png)
![Alerts](./public/screenshots/Alert.png)
![Advanced Preferences](./public/screenshots/AdvancedPreferences.png)
![Footer](./public/screenshots/Footer.png)
![Generated Palette](./public/screenshots/ColorPalette.png)


## Technologies Used
- React
- Tailwind CSS
- Mock API (Postman)
- Vercel (for deployment)


## Contributing
Contributions are welcome!  
- Fork the repo.
- Create a new branch for your feature/bugfix.
- Commit and push your changes.
- Open a pull request.
#   A t t y r e  
 #   a t t y r e 1  
 #   a t t y r e 1  
 #   a t t y r e 1  
 #   a t t y r e 1  
 #   A t t y r e 2  
 #   A t t y r e  
 #   a t t y r e  
 