![](https://i.giphy.com/media/xUOxeS6kx9ZUck6F1e/giphy.webp)
<!-- ![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimages.hellogiggles.com%2Fuploads%2F2016%2F06%2F27083846%2Fcast-away.gif&f=1&nofb=1) -->
<!-- ![](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmedia.giphy.com%2Fmedia%2Fl378gOLudxI4TZe9i%2Fgiphy.gif&f=1&nofb=1) -->

# Toms Personal Job Search Survival Pack

A list of links I wish I had had in one place when I graduated from bootcamp and entered my first job search.

---

## Project Starters & Instructions

[Express / Pug Project Starter](https://github.com/appacademy/modular-curriculum-practices/tree/staging/13/practices/express-group-project)

[Express / React Project Starter Instructions 1/3 - Backend](https://open.appacademy.io/learn/js-py---oct-2021-cohort-1-online/week-15---redux-and-authentication/authenticate-me-part-1--backend)

[Express / React Project Starter Instructions 2/3 - Frontend](https://open.appacademy.io/learn/js-py---oct-2021-cohort-1-online/week-15---redux-and-authentication/continue-authenticate-me-part-2--frontend)

[Express / React Project Starter Instructions 3/3 - Deployment](https://open.appacademy.io/learn/js-py---oct-2021-cohort-1-online/week-15---redux-and-authentication/authenticate-me-part-3--deploy)

<!-- 
Locked Link to Authenticate Me Solution - For a/A Internal Employee Use Only
https://files.slack.com/files-pri/T3BTYDL2V-F02V9CGUTFB/download/authenticate-me-2022.zip
-->

[Flask / React Project Starter](https://github.com/appacademy-starters/python-project-starter)


### ⚠️ Express Project Note: Faker.js is no longer supported
```javascript
// Faker is no longer supported, you will need to accommodate for coep errors by using the following in your backend app.js, this will allow 3rd party or http images to display.

app.use(helmet.crossOriginResourcePolicy({ policy: "cross-origin" }));
```

```bash
# Also you may need to npm install -g create-react-app first, if you are going to use the template.
# Open a terminal and change the directory until you are in the directory where you want to create your React app.
# To begin, install a global version of create-react-app:

npm i -g create-react-app

# You only need to install create-react-app on your computer once, i.e., not before every project.
# Although the official create-react-app documentation no longer recommends installing a global version of create-react-app, App Academy still recommends that you install it globally. This is because App Academy also encourages you to use nvm (Node Version Manager) to manage versions of Node.js. If you run npx create-react-app (see below) without having first installed create-react-app globally, then nvm will cache the version that you run. This cached version effectively gets treated as a global installation, but, because it is hidden by nvm, it is a global installation that is difficult to find and update. Accordingly, when new create-react-app releases appear, the cached version can cause hard-to-resolve version conflicts that will prevent create-react-app from running. A true global version, in contrast, can be updated simply by re-running the npm installation command.
# TL;DR: Installing create-react-app globally enables you to easily update and maintain the create-react-app version that you are using with nvm.
```

---

## Good Projects to Review

### 1. Pokedex Project with Redux

[Pokedex Root Github Link](https://github.com/appacademy/Modular-Curriculum/tree/staging/content/react-redux/aggregates/pokedex/redux-based)

[Pokedex Instructions 1/4](https://github.com/appacademy/Modular-Curriculum/blob/staging/content/react-redux/aggregates/pokedex/redux-based/README-01-first-state.md)

[Pokedex Instructions 2/4](https://github.com/appacademy/Modular-Curriculum/blob/staging/content/react-redux/aggregates/pokedex/redux-based/README-02-second-state.md)

[Pokedex Instructions 3/4](https://github.com/appacademy/Modular-Curriculum/blob/staging/content/react-redux/aggregates/pokedex/redux-based/README-03-third-state.md)

[Pokedex Instructions 4/4](https://github.com/appacademy/Modular-Curriculum/blob/staging/content/react-redux/aggregates/pokedex/redux-based/README-04-fourth-state.md)

---

