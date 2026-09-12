# Color Code Converter

A simple, interactive web tool that converts color codes between RGB and HEX formats. Enter an RGB value to get its HEX equivalent, or enter a HEX value to get its RGB equivalent — instantly, with built-in validation.

## 🚀 Live Demo

Check out the live demo: [https://www.xn--msiu-goa8b.vn/github/color-code](https://www.xn--msiu-goa8b.vn/github/color-code)

## ✨ Features

- **RGB to HEX Conversion** – Enter an RGB color (e.g., `255, 0, 0`) and get the corresponding HEX code (e.g., `#FF0000`)
- **HEX to RGB Conversion** – Enter a HEX color (e.g., `#FF0000`) and get the corresponding RGB values (e.g., `255, 0, 0`)
- **Input Validation** – Alerts you if the RGB or HEX input is invalid, ensuring only correct formats are processed
- **Dark Theme** – Modern, GitHub-inspired dark interface for comfortable use
- **Responsive Design** – Works seamlessly on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📁 Project Structure

```
color-code/
├── index.html    # Main HTML file
├── style.css     # Stylesheet
├── script.js     # JavaScript conversion logic
└── README.md     # Project documentation
```

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/color-code.git
   ```
2. **Navigate to the project folder**   
   ```bash
   cd color-code
   ```
3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local development server (e.g., Live Server in VS Code)

## 📝 How It Works

The tool provides two conversion directions:

### RGB → HEX

1. Enter an RGB color in the "RGB" input field using the format `R, G, B` (e.g., `255, 0, 0`)
2. Click the "Chuyển sang HEX" (Convert to HEX) button
3. The corresponding HEX code appears in the "HEX" input field

### HEX → RGB

1. Enter a HEX color in the "HEX" input field (e.g., `#FF0000` or `FF0000`)
2. Click the "Chuyển sang RGB" (Convert to RGB) button
3. The corresponding RGB values appear in the "RGB" input field

### Validation:

- RGB input must contain exactly three numbers, each between 0 and 255
- HEX input must be a valid 3-byte hex code (with or without the `#` prefix)
- If the input is invalid, an alert message prompts you to correct the format

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
This project is open-source and available under the MIT License.
