<h1 align="center">LLM Engineering</h1>

`main image`

## Description:
Outline for general FULLSTACK DEVELOPMENT PROJECTs

## Notes:
<p align="center">Please reference the screenshot folder for more available images</p>

`selected image 1`

Transformer
Context Engineering
Agent Loops
Tokens
Context Windows
Parameter
API cost 

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
- **[Huggy Face](https://huggingface.co/)** The platform where the machine learning community collaborates on [models](https://huggingface.co/models), [datasets](https://huggingface.co/datasets), [spaces](https://huggingface.co/spaces) and applications. [Documentation](https://huggingface.co/docs) 


- **Ollama** is the easiest way to automate your work using open [models](https://ollama.com/)
    - **Gemmma3** The current, most capable model that runs on a single [GPU](https://ollama.com/library/gemma3)
<p align="center"><a href="https://ollama.com/"><img src="./images/OllamaGraphic.jpg"></img></a></p>

- **Cursor** is an AI editor and coding [agent](https://cursor.com/) / [docs](https://cursor.com/docs)

- **Astral’s** mission is to make the Python ecosystem more productive by building high-performance developer tools, starting with [Ruff](https://astral.sh/).
    - **[UV](https://docs.astral.sh/uv/)** manages project dependencies and environments, with support for lockfiles, workspaces, and more

- **[OpenAI](https://openai.com/)** AI (artificial intelligence) research company that produces **GPT** [here](https://chatgpt.com/?utm_source=google&utm_medium=paid_search&utm_campaign=GOOG_C_SEM_GBR_Core_CHT_BAU_ACQ_PER_MIX_ALL_NAMER_US_EN_091724&c_id=21714513245&c_agid=169187630082&c_crid=713941893304&c_kwid={keywordid}&c_ims=&c_pms=9031964&c_nw=g&c_dvc=c&gad_source=1&gad_campaignid=21714513245&gbraid=0AAAAA-I0E5eW2pdZt9FqG5T43-hUSa9ra&gclid=Cj0KCQiA-YvMBhDtARIsAHZuUzLZrMa-_BdjyJ08uDhvdO13d-jJcyj4Ffj-gnaJlau-FGtC7lRmGiwaAoBuEALw_wcB)
- **[Anthropic](https://www.anthropic.com/)** AI (artificial intelligence) research company that stems from **OpenAI** produces **Claude** [here](https://claude.ai/login)
- **[Google](https://www.google.com/?zx=1770251942244&no_sw_cr=1)** software engineering company that produces **Gemini** [here](https://gemini.google.com/?is_sa=1&is_sa=1&android-min-version=301356232&ios-min-version=322.0&campaign_id=bkws&utm_source=sem&utm_medium=paid-media&utm_campaign=bkws&pt=9008&mt=8&ct=p-growth-sem-bkws&gclsrc=aw.ds&gad_source=1&gad_campaignid=20108148196&gbraid=0AAAAApk5Bhkj4r2gzCNLbxQprdyV0KcL2&gclid=Cj0KCQiA-YvMBhDtARIsAHZuUzK0Fd4K_sx_kP3fOeG2WQ6Z3yMJ2dqzAaQ0uU-v0ikMNR_ygfKptogaAq7aEALw_wcB)
- **[X.ai](https://x.ai/)**: Truth-seeking AI companion for unfiltered answers with advanced capabilities in reasoning, coding, and visual processing **Grok** [here](https://x.ai/grok)

### Large Language Models (LLM)
- **[Meta](https://www.meta.com/)** has [Llama](https://www.llama.com/)
- **[Mistral](https://mistral.ai/)** has [mixtral](https://mistral.ai/news/mixtral-of-experts)
- **[Alibaba Cloud](https://www.alibabacloud.com/help/en/model-studio/what-is-qwen-llm)** has [Gwen](https://qwen.ai/home)


- **[Vellum](https://www.vellum.ai/llm-leaderboard?utm_source=google&utm_medium=organic)** This LLM leaderboard displays the latest public benchmark performance for SOTA model versions released after April 2024. The data comes from model providers as well as independently run evaluations by Vellum or the open-source community. We feature results from non-saturated benchmarks, excluding outdated benchmarks (e.g. MMLU).


`uv --version`

- Prompt Engineers, Copilots, Context Engineering (RAG), Agentic AI

<p align="center"><a href="https://docs.astral.sh/uv/"><img src="./images/UVversion.jpg"></img></a></p>

`uv self update`

<p align="center"><a href="https://docs.astral.sh/uv/getting-started/installation/"><img src="./images/UVconfirmation.jpg"></img></a></p>

`uv sync`
    
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
