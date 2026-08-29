# I'm Octavio Martínez 👋
**Senior Full-stack Developer | Software Architect**

<p>Developer with over 8 years of professional experience focused on the JavaScript ecosystem, Node.js, and React. My approach is built on architectural integrity, creating useful software experiences that enhance developers' day-to-day work, and implementing emerging technologies, especially Artificial Intelligence.</p>

## 🚀 Featured Projects
### 🤖 SOPL-A
It is a Python-based DSL for AI Agent orchestration. Its core feature is treating Context as a first-class citizen with dedicated operations that optimize it before it is consumed by an LLM, thereby optimizing token usage and reducing costs.
```Javascript
Tool tool = Tool("tools/tool.py")
LLM tiny = Model.get("google/gemma-3-1b")
tiny.set_temperature(0)
Context ctx
ctx.push("system", "...")
ctx.push("assistant", "...")
ctx.push("user", "...")

loop main(input_user) {
    Object response = tiny.call(input_user, ctx.get_all())
    Object data = tool.execute(response.data)
    if( data.ok ) {
      return data.result
    }
}
```

### 🧠 Project Corpus 1900
Abductive Leap simulation experiment ("The Einstein Challenge") using a **TinyLlama-1.1B** model.

* **Objective:** Evaluate an LLM's ability to generate a paradigm shift (Relativity) when exposed to physical anomalies (Michelson-Morley) without access to post-1900 data.

### 🌉 Claumini Bridge
Local proxy consisting of a **Node.js** server and a Chrome extension that converts free Gemini, ChatGPT, or Claude accounts into an OpenAI-standard compatible API.

* **Utility:** Connects IDEs (Trae, Cursor, Continue) and libraries (LangChain, AutoGen) directly to the browser tab to save on API costs.

## 🛠️ Other Projects
* **[Rag-router](https://www.npmjs.com/package/rag-router):** NPM module that allows deploying a RAG architecture on Express.js in just a few lines of code..
* **[Prompt Box](https://chromewebstore.google.com/detail/prompt-box/odcagcgihohglhnolhimdoeahaaefilm):** React extension with over 200 users for managing AI prompts.
* **[Kommiter IA](https://www.npmjs.com/package/kommiter-ia):** Semantic commit generator based on file changes.
* **Check Repo IA:** Code quality assessment tool that got me accepted into the GitHub Developer Program.
* **Search Dependencies:** Next.js and Firebase app to locate dependencies used in previous projects using the GitHub API.

## 📚 Technical Writing and Research
In addition to development, I dedicate time to documentation and theoretical research:

* **Books:** Author of "[Lo que no te van a enseñar en un curso de React](https://www.amazon.com/Lo-que-ense%C3%B1an-curso-React-ebook/dp/B0FQKVZFDD)" (What They Won't Teach You in a React Course) and currently writing "La Filosofía de React" (The Philosophy of React).
* **Theoretical Physics:** Published the [Axiom of Topological Distinction](https://zenodo.org/records/17919110) for multitemporal universes, and I am currently working on theories of emergent gravity.

## 💻 Main Tech Stack
React | Node.js | TypeScript | C# / .NET | Next.js | Tailwindcss | PostgreSQL | Oracle

## Contact
<div style="display:flex; flex-direction:row">
  <a href="https://zenx5.pro"><img src="https://img.shields.io/badge/Status-Always Up-lightgreen?style=plastic"/></a>
  <a href="https://www.linkedin.com/in/zenx5/"><img src="https://img.shields.io/badge/LinkedIn-Zenx5-blue?style=plastic&logo=linkedIn"/></a>
  <a href="mailto:omartinez1618@gmail.com"><img src="https://img.shields.io/badge/Mail-omartinez1618@gmail.com-red?style=plastic&logo=gmail"/></a>
</div>
