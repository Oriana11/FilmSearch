# Film Finder

A web application to discover random movies by genre using the TMDB API.

<img width="1920" height="919" alt="image" src="https://github.com/user-attachments/assets/55be9514-b0d4-417b-a82e-90d3eb9214e9" />
<img width="1920" height="919" alt="image" src="https://github.com/user-attachments/assets/cabd4802-001b-4aac-bcaf-90d3d8efe0e7" />



## Setup Instructions

### 1. Get a TMDB API Key
- Sign up for a free account at [The Movie Database (TMDB)](https://www.themoviedb.org/)
- Go to your account settings
- Navigate to the API section
- Request an API key (choose "Developer" option)

### 2. Configure Your API Key
1. Navigate to the `public` folder
2. Copy the `config.example.js` file and rename it to `config.js`
3. Open `config.js` and replace `'YOUR_TMDB_API_KEY'` with your actual API key

```javascript
const config = {
    tmdbKey: 'your_actual_api_key_here'
};
```

### 3. Run the Project
- Open `index.html` in your web browser
- The `config.js` file is in `.gitignore` and will NOT be uploaded to GitHub, keeping your API key safe!

## Important Notes
- **Never** commit your `config.js` file to GitHub
- The `config.example.js` is the template - don't put your real API key there
- If someone clones your project, they'll need to create their own `config.js` from the example file

### Credits
Image by <a href="https://pixabay.com/users/arttower-5337/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7138980">Brigitte Werner</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7138980">Pixabay</a>
