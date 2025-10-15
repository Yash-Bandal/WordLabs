# WordLabs

WordLabs is a web-based text utility application built with React.  
It allows users to perform a wide range of operations on sentences and words — including text formatting, encoding/decoding, and case transformations — in a fast and user-friendly interface.

**Live Demo:** [https://wordlabs.netlify.app/](https://wordlabs.netlify.app/)  
**Repository:** [https://github.com/Yash-Bandal/WordLabs](https://github.com/Yash-Bandal/WordLabs)

<br>

## Features

### Text Formatting
- Apply styles such as **bold**, *italic*, underline, strikethrough, and inline code.  
- Copy formatted text directly to the clipboard.

### Case Conversion
- Convert text to uppercase, lowercase, title case, sentence case, or capitalize each word.

### Encoding / Decoding
- Base64 encoding and decoding  
- URL encoding and decoding  
- HTML entity encoding and decoding

### Text Cleanup
- Remove extra spaces  
- Remove numbers, symbols, or punctuation  
- Count words, characters, and lines

### Additional Utilities
- Reverse words or sentences  
- Sort words alphabetically  
- Find and replace text  
- Word frequency analysis (optional feature)

### User Interface
- Clean and minimal design built with Tailwind CSS  
- Responsive layout for all devices  
- Light and dark mode support

<br>

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Yash-Bandal/WordLabs.git
cd WordLabs
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Application
```bash
npm run dev
```

Then open your browser and navigate to **http://localhost:5173** (if using Vite) or **http://localhost:3000** (if using Create React App).


<br>


## Project Structure

```
WordLabs/
├── public/                     # Static assets served directly (favicon, logos, redirects)
│   ├── logo-wp.png
│   └── _redirects
│
├── src/                        # React source code
│   ├── assets/                 # Local images and icons
│   │   ├── logo-wp.png
│   │   ├── logo.PNG
│   │   └── react.svg
│   │
│   ├── components/             # Reusable UI components
│   │   ├── About.jsx
│   │   ├── Alert.jsx
│   │   ├── Navbar.jsx
│   │   └── TextForm.jsx
│   │
│   ├── App.css                 # Main App styling
│   ├── App.jsx                 # Root React component
│   ├── index.css               # Global CSS (Tailwind imports)
│   └── main.jsx                # Application entry point
└── README.md                   # Project documentation
```



<br>

## Deployment

The project is deployed using Netlify.

To deploy manually:
```bash
npm run build
```
Then upload the contents of the `dist` or `build` folder to Netlify.

<!-- <br>

## Contributing

Contributions are welcome!  
To contribute:

1. Fork the repository  
2. Create a new branch: `git checkout -b feature-name`  
3. Make your changes and commit them: `git commit -m "Add feature"`  
4. Push to your fork and open a pull request -->

<br>

## Author

**Yash Bandal**  
[GitHub Profile](https://github.com/Yash-Bandal)

<br>

## License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project as permitted by the license.



<br>

##  Connect
* Author: [@Yash-Bandal](https://github.com/Yash-Bandal)

<br>

## A YB Productions original. 💝
