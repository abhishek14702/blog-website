# NodeJs, Express, EJS & MongoDB Blog - CRUD

![alt text](/readme-image.jpg?raw=true)

## You need:
- NodeJs
- Database (MongoDB) Free Cluster

## Create .env file
Create a .env file to store your credentials. Example below:

```
MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/blog
JWT_SECRET=MySecretBlog
```

## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm run dev
```

```
blog project
├─ .gitignore
├─ Design Files
│  └─ NodeJs Blog.fig
├─ DummyData.txt
├─ LICENSE
├─ README.md
├─ app.js
├─ package-lock.json
├─ package.json
├─ public
│  ├─ css
│  │  └─ style.css
│  ├─ img
│  │  ├─ hero-image.webp
│  │  └─ img-noise-361x370.png
│  └─ js
│     └─ script.js
├─ readme-image.jpg
├─ server
│  ├─ config
│  │  └─ db.js
│  ├─ helpers
│  │  └─ routeHelpers.js
│  ├─ models
│  │  ├─ Post.js
│  │  └─ User.js
│  └─ routes
│     ├─ admin.js
│     └─ main.js
└─ views
   ├─ about.ejs
   ├─ admin
   │  ├─ add-post.ejs
   │  ├─ dashboard.ejs
   │  ├─ edit-post.ejs
   │  └─ index.ejs
   ├─ index.ejs
   ├─ layouts
   │  ├─ admin.ejs
   │  └─ main.ejs
   ├─ partials
   │  ├─ footer.ejs
   │  ├─ header.ejs
   │  ├─ header_admin.ejs
   │  └─ search.ejs
   ├─ post.ejs
   └─ search.ejs

```