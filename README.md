# 🎬 Netflix Custom Clone

A **React.js**-based Netflix clone that replicates the look and feel of Netflix while adding unique improvements.  
This custom build includes **Dark/Light Mode**, **Scroll-to-Top Button**, **Hover Animations**, and a fully responsive design.  
It uses the **TMDb API** to fetch live movie and TV show data.

---

## ✨ Features
- 🎥 **Netflix-style interface** – Browse movies & TV shows in category rows.
- 🌗 **Dark/Light Mode Toggle** – Instantly switch between themes.
- ⬆ **Scroll-to-Top Button** – Quickly jump to the top of the page.
- 🎨 **Hover Animations** – Smooth transitions when hovering over thumbnails.
- 📱 **Fully Responsive** – Works on desktop, tablet, and mobile devices.
- 🔗 **Live Data** – Powered by The Movie Database (TMDb) API.
- 📂 **Clean Code Structure** – Easy to read, modify, and maintain.

---

## 🛠 Tech Stack
- **Frontend:** React.js, HTML5, CSS3, JavaScript (ES6+)
- **API:** [TMDb API](https://www.themoviedb.org/documentation/api)
- **Styling:** Custom CSS inspired by Netflix’s UI
- **Icons:** React Icons
- **Deployment:** Vercel / Netlify / GitHub Pages

---

## 📂 Project Structure
Netflix-Custom-Clone/
├── public/
│   ├── index.html
│   ├── favicon.ico
├── src/
│   ├── components/     # Reusable React components
│   ├── pages/          # Main page layouts
│   ├── App.jsx         # Main application logic
│   ├── index.js        # Entry point
│   ├── styles/         # CSS files
├── .env                # API keys and environment variables
├── package.json
├── README.md

---

## ⚙️ Installation & Setup
Follow these steps to run the project locally:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/netflix-custom-clone.git
```
### 2. Navigate to the project folder
```
cd netflix-custom-clone
```
### 3. Install dependencies
```
npm install
```
### 4. Start the development server
```
npm start
````
🔑 API Configuration
	- 1.	Sign up at TMDb for a free account.
	- 2.	Go to Settings > API and generate your API key.
	- 3.	Create a .env file in the root directory and add:

```bash
REACT_APP_TMDB_API_KEY=your_api_key_here
```
##4.	Restart your development server.

# 📸 Screenshots

- Home Page

- Movie Row

- Log In Page

- Search Display

# 🚀 Deployment

You can deploy this project to:

- [Vercel → Vercel Deployment Guide](https://vercel.com/docs)
- [Netlify → Netlify Deployment Guide](https://docs.netlify.com/)
- [GitHub Pages → GitHub Pages Guide](https://pages.github.com/)

---

## 🛠 Troubleshooting

- **API key not working** → Ensure `.env` file is set correctly and restart the dev server.
- **CORS error** → Check if the API endpoint requires additional headers.
- **Styles not loading** → Confirm CSS file imports are correct.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch  
```
git checkout -b feature-xyz
```
3. Commit changes
```
git commit -m "Added new feature"
```
4. Push to the branch
```
git push origin feature-xyz
```
5. Open a Full Request


# 📜 License

This project is for educational purposes only and is not affiliated with or endorsed by Netflix.


💡 Acknowledgements
- TMDb API for providing movie data.
- Netflix for UI inspiration.
- React.js community for open-source libraries.
