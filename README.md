# 🌄 Image Search App

The **Image Search App** is a responsive and modern web application that allows users to search for high-quality images using the **Unsplash API**. Based on the user’s input, the app fetches and displays beautiful images along with short descriptions and direct links to the original source.

---

## 🔍 Features

- 🔎 Search images from Unsplash API  
- 📄 View image descriptions and direct links to their Unsplash pages  
- 📦 "Show More" button to load additional results  
- 📱 Fully responsive design for mobile, tablet, and desktop  
- ⚡ Clean and modern UI with hover effects and smooth animations  
- 🚫 Gracefully handles empty input and no-result searches  

---

## 🛠️ Technologies Used

- **HTML5**  
- **CSS3** – for responsive & aesthetic design  
- **JavaScript** – using Fetch API and DOM manipulation  
- **Unsplash Developer API**  

---

## 📸 How It Works

1. Enter a search keyword (e.g., `"nature"`, `"cats"`, `"space"`).
2. Click the **Search** button.
3. The app fetches images related to the search term.
4. Click **Show More** to load more results.

---

## 📁 Project Structure
image-search-app/
├── index.html # Main HTML structure
├── style.css # App styling (responsive + modern)
├── index.js # JavaScript logic and API integration


---

## 🔑 API Key Setup

To run this project locally:

1. Go to [Unsplash Developer](https://unsplash.com/developers) and create an account.
2. Generate your **Access Key**.
3. Replace the `accessKey` variable in `index.js` with your key:

```javascript
const accessKey = "YOUR_ACCESS_KEY_HERE";

