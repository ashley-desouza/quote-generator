# Quote Generator

A beautiful, responsive web application that displays inspirational quotes fetched from an external API. Users can generate new quotes with a single click and share their favorites on Twitter.

![Quote Generator](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🚀 Live Demo

**[View Live Demo](https://ashley-desouza.github.io/quote-generator/)**

Experience the quote generator functionality in action! Click the 'New Quote' to get an inspirational quote.

## ✨ Features

- 🎲 **Random Quote Generation**: Get a new inspirational quote with one click
- 🐦 **Twitter Integration**: Share your favorite quotes directly on Twitter
- ⏳ **Loading States**: Smooth loading spinner while fetching quotes
- 📱 **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- 🎨 **Dynamic Styling**: Automatically adjusts font size for longer quotes
- 🔄 **Async API Calls**: Efficient data fetching using modern async/await syntax

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with animations and responsive design
- **Vanilla JavaScript**: No frameworks, pure JavaScript for optimal performance
- **Font Awesome**: Icon library for UI elements
- **Google Fonts**: Montserrat font family
- **External API**: [Quotes API](https://github.com/jacintodesign/quotes-api) by Jacinto Design

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ashley-desouza/quote-generator.git
   cd quote-generator
   ```

2. Open `index.html` in your web browser:
   - **Option 1**: Double-click `index.html` to open it directly
   - **Option 2**: Use a local server (recommended for development):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server -p 8000
     ```
     Then navigate to `http://localhost:8000` in your browser

## 📖 Usage

1. **View a Quote**: When you open the application, a random quote will automatically load
2. **Get New Quote**: Click the "New Quote" button to fetch and display a random quote
3. **Share on Twitter**: Click the Twitter icon button to share the current quote on Twitter

## 📁 Project Structure

```
quote-generator/
│
├── index.html          # Main HTML structure
├── style.css           # Styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🔌 API Information

This project uses the [Quotes API](https://github.com/jacintodesign/quotes-api) which provides a JSON file containing thousands of inspirational quotes.

- **API Endpoint**: `https://jacintodesign.github.io/quotes-api/data/quotes.json`
- **Response Format**: JSON array of quote objects
- **Quote Object Structure**:
  ```json
  {
    "text": "Quote text here",
    "author": "Author name"
  }
  ```

## 🎨 Features in Detail

### Dynamic Quote Styling
- Quotes longer than 100 characters automatically use a smaller font size for better readability
- Smooth transitions between quote changes

### Loading States
- Loading spinner appears while fetching quotes from the API
- Prevents user interaction during data fetching

### Error Handling
- Graceful error handling for API failures
- Console logging for debugging purposes

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/ashley-desouza/quote-generator/issues).

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Ashley DeSouza**

- GitHub: [@ashley-desouza](https://github.com/ashley-desouza)
- LinkedIn: [ashleydesouza](https://www.linkedin.com/in/ashleydesouza/)

## 🙏 Acknowledgments

- [Jacinto Design](https://github.com/jacintodesign) for providing the Quotes API
- [Font Awesome](https://fontawesome.com/) for the icons
- [Google Fonts](https://fonts.google.com/) for the Montserrat font

---

⭐ If you found this project helpful, please consider giving it a star!

