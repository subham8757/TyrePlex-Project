# TyrePlex 🚗✨

## Overview

**TyrePlex** is a modern web application developed using HTML, CSS, and Bootstrap 5.3. It features a sleek and responsive interface designed with usability and aesthetics in mind. 🌟🚀

## Features

- **Responsive Design**: Built with Bootstrap 5.3, ensuring compatibility across various devices and screen sizes. 📱💻
- **Custom Styling**: Utilizes custom CSS for unique design elements and styling, including smooth animations. 🎨🌀
- **Modern Typography**: Integrates the Poppins font from Google Fonts for a clean and contemporary look. 🅰️
- **Iconography**: Includes Font Awesome for scalable and customizable icons with animation effects. ⚙️

## Technologies Used

- **HTML**: Provides the foundational structure and content of the web application. 🏗️
- **CSS**: Custom styles and animations applied to enhance visual presentation and layout. 🖌️💫
- **Bootstrap 5.3**: A powerful front-end framework used for responsive design and pre-designed components. 📐
- **Google Fonts**: Poppins font for improved typography. ✨
- **Font Awesome**: Provides animated icons for various UI elements. 🖼️

## Animation Highlights

- **Smooth Transitions**: CSS animations create smooth transitions between states and enhance user interactions. ⚡
- **Hover Effects**: Custom hover effects applied to buttons and links for a more interactive experience. 🖱️
- **Load Animations**: Subtle animations when loading content to improve user engagement. ⏳

### Adding Animation to Emojis and Icons

**For Emojis**: You can use CSS keyframes to animate emojis. Here's an example of a bouncing emoji:

```css
@keyframes bounce {
  0%, 20%, 50%, 80%, 100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(-30px);
  }
  60% {
    transform: translateY(-15px);
  }
}

.animated-emoji {
  display: inline-block;
  animation: bounce 2s infinite;
}
```

Use the `animated-emoji` class in your HTML:

```html
<span class="animated-emoji">🚗</span>
```

**For Font Awesome Icons**: Use CSS animations for icons. For example, to add a rotating effect:

```css
@keyframes rotate {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}

.animated-icon {
  display: inline-block;
  animation: rotate 2s linear infinite;
}
```

Use the `animated-icon` class with Font Awesome icons:

```html
<i class="fas fa-cogs animated-icon"></i>
```

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:
   ```bash
   cd TyrePlex
   ```

3. **Open the `index.html` file in your preferred web browser** to view the application. 🌐

## Usage

- **HTML**: Defines the structure of the web application in the `index.html` file. 📄
- **CSS**: Contains custom styles and animations in the `style.css` file. Modify as needed to adjust the design and effects. 🛠️
- **Bootstrap**: Utilize Bootstrap’s responsive classes and components. Refer to the [Bootstrap documentation](https://getbootstrap.com/docs/5.3/) for more details. 📚
- **Google Fonts**: The Poppins font is linked in the `<head>` section. Adjust font weights and styles as necessary. 🔠
- **Font Awesome**: Use icons for UI enhancements. Check the [Font Awesome documentation](https://fontawesome.com/docs) for details. 🗂️

## Contributing

1. **Fork the repository** to your own GitHub account. 🍴
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add new feature or fix bug"
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature-branch
   ```
5. **Submit a pull request** detailing your changes. 🔄

## License

This project is licensed under the [MIT License](LICENSE). 📜

## Contact

For any inquiries or feedback, please reach out to:

- **Email**: [subhammazumdar8757@gmail.com](mailto:subhammazumdar8757@gmail.com) 📧
- **GitHub**: [https://github.com/subham8757](https://github.com/subham8757) 🧑‍💻

---

Feel free to adjust the animations and effects according to your design preferences!
