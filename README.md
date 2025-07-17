# 🎸 Band Generator 🎶

A fun little Node.js + Express web app that randomly generates band names using EJS templates.

## 🌐 Live Preview

> Currently running on `localhost:3000`  
> Use the **Generate Name** button to get a fun band name composed of a random adjective and noun.


## 🧰 Built With

- **Node.js** – backend runtime
- **Express.js** – server framework
- **EJS (Embedded JavaScript Templates)** – view engine
- **HTML + CSS** – basic styling and structure

## 🗂️ Features

- Dynamic generation of band names using two lists: adjectives and nouns.
- Clean EJS template rendering with conditional logic.
- Modularized header and footer via EJS partials.
- Styled layout with a centered button and dynamic content.

## 🧪 How It Works

1. A GET request to `/` renders the homepage.
2. On clicking **Generate Name**, a POST request is sent to `/submit`.
3. The server picks a random adjective and noun, combines them, and returns it to the view.
4. The name is displayed dynamically using EJS templating.


## 🏁 Getting Started

```bash
git clone https://github.com/your-username/band-generator.git
cd band-generator
npm install
node index.js
```

Then open http://localhost:3000 in your browser.

## 📝 Learnings

Through this project, I practiced:

- Setting up and using EJS with Express
- Writing logic in index.js to handle form submission and dynamic values
- Creating partials and organizing EJS views
- Using body-parser middleware and handling POST requests

