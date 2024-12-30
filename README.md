# Xoeus

<div align="center">
  <img 
    src="https://media.githubusercontent.com/media/xoeus/xoeus/main/assets/docs/demo.gif" 
    width="100%" 
    alt="Xoeus Demo" 
  />
</div>

<div align="center">
  <table>
    <tbody>
      <tr>
        <td align="center">
          <a 
            href="https://marketplace.visualstudio.com/items?itemName=saoudrizwan.xoeus-dev" 
            target="_blank"
          >
            <strong>Download on VS Marketplace</strong>
          </a>
        </td>
        <td align="center">
          <a 
            href="https://discord.gg/xoeus" 
            target="_blank"
          >
            <strong>Join the Discord</strong>
          </a>
        </td>
        <td align="center">
          <a 
            href="https://github.com/xoeus/xoeus/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature


Meet Xeous, an AI assistant that is able to use your API, Or local models.




---

1. Enter your task and include images to convert mockups into functional apps or fix bugs using screenshots.  
2. Xoeus begins by analyzing your file structure and source code ASTs, running regex searches, and reading relevant files to understand your project. By carefully managing the information added to its context, Xoeus provides meaningful assistance even for large, complex projects without exceeding the context window.  
3. Once Xoeus has the necessary information, it can:  
   - Create and edit files while monitoring linter and compiler errors, proactively fixing issues like missing imports or syntax errors.  
   - Execute terminal commands and monitor outputs, enabling it to handle tasks like resolving dev server issues after editing a file.  
   - For web development, launch your site in a headless browser to interact with elements, capture screenshots, and log console data, making it easy to address runtime errors and visual bugs.  
4. When a task is complete, Xoeus will present the result with a terminal command like `open -a "Google Chrome" index.html`, which you can execute with a single click.  

> [!TIP]  
> Use the `CMD/CTRL + Shift + P` shortcut to open the command palette and type "Xoeus: Open In New Tab" to launch the extension as a tab in your editor. This lets you work side-by-side with your file explorer while tracking how Xoeus modifies your workspace.  

---

<img align="right" width="340" src="https://github.com/user-attachments/assets/3cf21e04-7ce9-4d22-a7b9-ba2c595e88a4">  

### Use Any API and Model  

Xoeus supports API providers like OpenRouter, Anthropic, OpenAI, Google Gemini, AWS Bedrock, Azure, and GCP Vertex. You can also configure any OpenAI-compatible API or use a local model via LM Studio or Ollama. With OpenRouter, Xoeus automatically fetches the latest model list, ensuring you have access to the newest options as soon as they’re available.  

The extension tracks total token usage and API costs for each task and individual requests, keeping you informed about expenses at every step.  

---

<img align="left" width="370" src="https://github.com/user-attachments/assets/81be79a8-1fdb-4028-9129-5fe055e01e76">  

### Run Commands in the Terminal  

Leveraging [shell integration updates in VSCode v1.93](https://code.visualstudio.com/updates/v1_93#_terminal-shell-integration-api), Xoeus can execute terminal commands and process outputs in real time. It can install packages, run build scripts, deploy applications, manage databases, and execute tests, adapting to your development environment to complete tasks efficiently.  

For long-running processes like dev servers, use the "Proceed While Running" button to allow Xoeus to continue the task while monitoring the terminal for new output. This enables it to react dynamically to issues, such as compile-time errors.  

---

<img align="right" width="400" src="https://github.com/user-attachments/assets/c5977833-d9b8-491e-90f9-05f9cd38c588">  

### Create and Edit Files  

Xoeus can directly create and edit files in your editor, presenting changes in a diff view for easy review and feedback. It monitors linter and compiler errors, addressing issues like missing imports and syntax problems autonomously.  

All modifications are recorded in your file's timeline, making it simple to track or revert changes when necessary.  

---

<img align="left" width="370" src="https://github.com/user-attachments/assets/bc2e85ba-dfeb-4fe6-9942-7cfc4703cbe5">  

### Use the Browser  

With advanced capabilities like [Computer Use](https://www.anthropic.com/news/3-5-models-and-computer-use), Xoeus can interact with a browser, performing tasks such as clicking, typing, scrolling, and capturing screenshots or logs. This makes it ideal for debugging, end-to-end testing, and resolving runtime or visual issues.  

Ask Xoeus to "test the app," and it will launch your dev server, open it in a browser, and run tests to verify functionality.  

---

<img align="right" width="350" src="https://github.com/user-attachments/assets/ac0efa14-5c1f-4c26-a42d-9d7c56f5fadd">  

### Add Custom Tools  

Using the [Model Context Protocol](https://github.com/modelcontextprotocol), Xoeus can extend its functionality with custom tools. You can use community-made servers or have Xoeus create tools tailored to your workflow.  

Examples include:  
- "Add a tool to fetch Jira tickets": Retrieve tickets and start resolving them.  
- "Add a tool to manage AWS EC2s": Check server metrics and adjust instance scaling.  
- "Add a tool to pull the latest PagerDuty incidents": Fetch details and begin fixing related issues.  

---

<img align="left" width="360" src="https://github.com/user-attachments/assets/7fdf41e6-281a-4b4b-ac19-020b838b6970">  

### Enhance Context  

- **`@url`:** Fetch and convert web content into Markdown.  
- **`@problems`:** Share workspace warnings or errors for Xoeus to resolve.  
- **`@file`:** Add a file’s contents without extra API calls.  
- **`@folder`:** Upload an entire folder to streamline workflows.  

---

## Contributing  

To contribute, start with messaging me for further details. 

<details>
<summary>Local Development Instructions</summary>  

1. Clone the repository _(requires [git-lfs](https://git-lfs.com/))_:  
    ```bash  
    git clone https://github.com/xoeus/xoeus.git  
    ```  
2. Open the project in VSCode:  
    ```bash  
    code xoeus  
    ```  
3. Install dependencies:  
    ```bash  
    npm run install:all  
    ```  
4. Launch by pressing `F5` or selecting `Run -> Start Debugging`. If you encounter build issues, install the [esbuild problem matchers extension](https://marketplace.visualstudio.com/items?itemName=connor4312.esbuild-problem-matchers).  

</details>  

---

Let me know if further tweaks are needed!
## License

[Apache 2.0 © 2024 Cline Bot Inc.](./LICENSE)
