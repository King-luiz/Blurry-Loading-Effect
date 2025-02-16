# Blurry Loading Effect

## 🚀 Project Overview
Blurry Loading is a simple yet visually appealing project that applies a smooth blur-to-clear transition effect as the page loads. It enhances the user experience by displaying a progressive loading percentage while gradually revealing the background image.

## 📌 Features
- **Dynamic Blurring Effect**: Background image starts with a heavy blur and clears as the loading progresses.
- **Smooth Percentage Loader**: A loading counter from `0%` to `100%` with a fade-out effect.
- **Minimalist Design**: Uses CSS for aesthetics and JavaScript for interactivity.
- **Responsive Layout**: Works seamlessly across different screen sizes.

## 🛠️ Technologies Used
- HTML5
- CSS3 (Including Google Fonts)
- JavaScript (DOM Manipulation, setInterval, and Custom Mapping Function)

## 📂 Project Structure
```
📁 BlurryLoading
│── 📄 index.html      # Main HTML file
│── 🎨 style.css       # Styling with blur effects
│── 🛠️ script.js       # JavaScript logic for loading effect
```

## 🎨 How It Works
1. The background image starts with a `30px` blur effect.
2. A counter updates from `0%` to `100%` in small intervals.
3. As the counter increases, the blur effect decreases progressively.
4. Once the loading reaches `100%`, the text fades away and the image appears clear.


## 🚀 Getting Started
### 🔧 Setup Instructions
1. **Clone the repository**
   ```bash
   git clone https://github.com/King-luiz/blurry-loading.git
   ```
2. **Navigate to the project folder**
   ```bash
   cd blurry-loading
   ```
3. **Open `index.html` in your browser**
   ```bash
   open index.html
   ```

## 📜 Code Explanation
### `script.js`
- Uses `setInterval` to increase the `load` variable from `0` to `100`.
- Updates the opacity of the loading text using the `scale()` function.
- Reduces the blur effect dynamically.


## 📌 Customization
- Change the **background image** in `style.css` by updating the `background: url(...)` property.
- Adjust the **blur intensity** in `script.js` by modifying the `scale()` function values.
- Modify the **loading speed** by tweaking the interval timing in `setInterval(blurring, 30);`

## 📧 Contact Information
-📩 Email: Mureithilewins@gmail.com
-📞 Phone: +254-112-876-340

```
**📝 License:** MIT License. Free to use and modify! Happy coding! 🚀

