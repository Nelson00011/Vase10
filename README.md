<h1 align="center">LLM Engineering</h1>

`main image`

## Description:
Outline for general FULLSTACK DEVELOPMENT PROJECTs

## Technology Stack
- **Frontend/Client:** React.js, HTML5, CSS, framework, etc.
- **API:** Api calls or external sources used
- **Backend/Server:** node.js/express or python alternatives, include databases

<h2 align="center">Video:</h2>

## Screen Shots:
<p align="center">Please reference the screenshot folder for more available images</p>

`selected image 1`

`selected image 2`

`selected image 3`

## Run Code (Environment)

### Front-End Instructions `<examples below>`
- confirm that config is appropriate:
```
> node -v
> npm -v
> git --version
```

- Initial package.json & install dependenies(localhost:3000):
    - Must be `cd`'d into frontend/client for install
    - MUI, `react-router-dom`, redux, formik, etc... (see resources)
```
> npx create-react-app <project name>
> cd <project name>
> npm install @mui/icons-material @mui/material @emotion/styled @emotion/react
> npm install --save react-router-dom
> npm install react-redux @reduxjs/toolkit
> npm install formik yup dotenv react-responsive-carousel
> npm install --save @stripe/react-stripe-js @stripe/stripe-js
```
- Test front-end once pages are generated (ctrl-c to exit):
```
> npm run start
```

### Back-End Helpful Instructions `<examples below>`
- Initial package.json & install dependencies:
    - Must be `cd`'d into backend/server for install
```
> npx create-strapi-app@latest <project name>
> cd <project name>
> npm install --save stripe
```
- Strapi Database generated (ctrl-c to exit):
```
> npm run develop
```
- **Avoid** *npm run start* and use the `npm run develop`. 
- Allow server to restart with each edit (see resources): 
    - **Content-Type Builder**: Item entry
    - **Media Library**: upload photos
    - **Permissions**: Settings > Roles > Public
- When using .env variables remember to [install prior](https://www.npmjs.com/package/dotenv/v/14.0.0)
```
npm install dotenv --save
```
-
    - Create a .env file in the root directory of your project.
    - Import and configure dotenv.
    - Establish a .gitignore [here](https://git-scm.com/docs/gitignore)

- In frontend fetch `item` from backend (*localhost:1337*):
```
const grouping = "items"
const items = await fetch(
`http://localhost:1337/api/${grouping}`
)
```
--------------------------
### Deployment



## Contact:
<!--- You can add in your linkedin, medium, stack overflow, dev.to account, etc. here --->
If you want to contact me you can reach me at <nelson@oakhalo.com>.

Connect with me on <a href="https://www.linkedin.com/in/ayla-nelson/">LinkedIn</a>

Connect with me on <a href="https://github.com/oakHalo">Oakhalo.dev</a>

## Resources:
- **Ollama** is the easiest way to automate your work using open [models](https://ollama.com/)
    - **Gemmma3** The current, most capable model that runs on a single [GPU](https://ollama.com/library/gemma3)
<p align="center"><a href="https://ollama.com/"><img src="./images/OllamaGraphic.jpg"></img></a></p>

- **Cursor** is an AI editor and coding [agent](https://cursor.com/) / [docs](https://cursor.com/docs)

-**Astral’s** mission is to make the Python ecosystem more productive by building high-performance developer tools, starting with [Ruff](https://astral.sh/).
    - **[UV](https://docs.astral.sh/uv/)** manages project dependencies and environments, with support for lockfiles, workspaces, and more

    ```
    uv --version
    ```

<p align="center"><a href="https://docs.astral.sh/uv/"><img src="./images/UVversion.jpg"></img></a></p>

    ```
    uv self update
    ```
    
<p align="center"><a href="https://docs.astral.sh/uv/getting-started/installation/"><img src="./images/UVconfirmation.jpg"></img></a></p>

    
- **React.New** allows for testing new React projects [here](react.new)
- `Tech used and links associated`
- `Tech used and links associated`

`<examples below>`



#### **style:** 
- `frameworks and links associated`

- Filler Text [typographic](https://generator.lorem-ipsum.info/)
    - Lorem Ipsum 
- Google Fonts [here](https://fonts.google.com/)

#### **helpful hint:** 
- `useful hints for future projects to go faster`
- console log testing with `ctr-alt-l` 
- Always Stay Positive & Triple Check Permissions :)




<!-- 
### TODO stx: 
Future Structure (stx):
backend
frontend
images
screenShots [contains video link]
troubleShooting [contains issues resolved]


-->
