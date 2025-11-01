# Film Finder

A web application to discover random movies by genre using the TMDB API.

<img width="1920" height="919" alt="image" src="https://github.com/user-attachments/assets/73d96ca6-23c5-4e8c-ac82-00471e43c819" />
<img width="1920" height="919" alt="image" src="https://github.com/user-attachments/assets/024b7cf1-3956-4896-a81a-ba2a450df1d2" />


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
