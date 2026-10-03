```text
   _  ___              __  _  __     _ __  
  / |/ (_)__  ___ ____/ / / |/ /__ _(_) /__
 /    / / _ \/ _ `/ _  / /    / _ `/ /  '_/
/_/|_/_/_//_/\_,_/\_,_/ /_/|_/\_,_/_/_/\_\ 
                                           
```

## Hi there 👋, I am Ninad Naik

About me:

- 💼 Backend Developer at [Commotion](https://gocommotion.com), working on integrations, MCP and A2A agent infrastructure
- 🐧 Mentee, [LFX Linux Kernel Mentorship Program, Spring 2026](https://mentorship.lfx.linuxfoundation.org/project/53378ec5-48d7-4c49-a01f-8cbd3948db3d), with 11 patches merged upstream
- 📄 Co-author, *Evaluating Human Speech Confidence with Deep Learning Techniques*, ICCIS 2025 (Springer LNNS)
- 🔭 Interested in backend and distributed systems, AI agent infrastructure, Linux and open source
- 🌌 Outside code: astronomy
- 📄 Resume: [resume.ninadnaik.me](https://resume.ninadnaik.me)
- 📝 Tech Blog: [tech.ninadnaik.me](https://tech.ninadnaik.me)
- 📫 Reach me: <a href="mailto:ninadnaik07&commat;gmail.com" target="_blank" rel="noopener noreferrer">ninadnaik07&commat;gmail.com</a> · [LinkedIn](https://linkedin.com/in/ninadn) · [Portfolio](https://ninadnaik.me)

### ✨ Highlights

- Built and shipped 100+ enterprise integration connectors exposing 3,200+ agent-callable actions and 325 webhook triggers for Voice AI agents
- Worked on MCP gateway performance and correctness: Redis Pub/Sub for OAuth over SSE across autoscaled pods, connection pooling, query indexing and load testing
- Implemented enterprise OAuth 2.0 flows, including authorization code, client credentials and SAML bearer assertion
- 11 patches merged into the mainline Linux kernel: Devicetree binding conversions to DT schema, driver error-handling cleanups and documentation fixes

### ⚙️ Tech Stack

<table>
  <tr>
    <td><b>Languages:</b></td>
    <td>
      <img src="https://go-skill-icons.vercel.app/api/icons?i=c,cpp,py,go,java,js,ts" alt="c, c++, python, go, java, javascript, typescript" height="40"/>
    </td>
  </tr>

  <tr>
    <td><b>Backend:</b></td>
    <td>
      <img src="https://go-skill-icons.vercel.app/api/icons?i=nodejs,nestjs,fastapi,flask,graphql,grpc,kafka,mcp" alt="node.js, nestjs, fastapi, flask, graphql, grpc, kafka, model context protocol" height="40"/>
    </td>
  </tr>

  <tr>
    <td><b>Databases:</b></td>
    <td>
      <img src="https://go-skill-icons.vercel.app/api/icons?i=postgresql,mysql,mongodb,redis,clickhouse" alt="postgresql, mysql, mongodb, redis, clickhouse" height="40"/>
    </td>
  </tr>

  <tr>
    <td><b>Frontend:</b></td>
    <td>
      <img src="https://go-skill-icons.vercel.app/api/icons?i=html,css,tailwind,react,vite,nextjs" alt="html, css, tailwind css, react, vite, next.js" height="40"/>
    </td>
  </tr>

  <tr>
    <td><b>AI / ML:</b></td>
    <td>
      <img src="https://go-skill-icons.vercel.app/api/icons?i=pytorch,tensorflow,sklearn,huggingface" alt="pytorch, tensorflow, scikit-learn, hugging face" height="40"/>
    </td>
  </tr>

  <tr>
    <td><b>Infra / DevOps:</b></td>
    <td>
      <img src="https://go-skill-icons.vercel.app/api/icons?i=docker,kubernetes,helm,nginx,aws,gitlab,prometheus,grafana" alt="docker, kubernetes, helm, nginx, aws, gitlab ci, prometheus, grafana" height="40"/>
    </td>
  </tr>

  <tr>
    <td><b>Systems / Tools:</b></td>
    <td>
      <img src="https://go-skill-icons.vercel.app/api/icons?i=linux,bash,git,qemu,postman" alt="linux, bash, git, qemu, postman" height="40"/>
    </td>
  </tr>
</table>

### 🚀 Featured Projects

- 🔥 [**Redspot**](https://github.com/ninadnaik10/redspot): Event-driven website analytics. A JS tracker sends click events to FastAPI, which publishes them to Kafka for a consumer to persist in ClickHouse, with click heatmaps rendered in React.
- 🔗 [**Shortomega**](https://github.com/ninadnaik10/shortomega) ([live](https://shortomega.ninadnaik.me/)): URL shortener using Redis as the primary data store, with HyperLogLog unique-visitor analytics, Lua scripts, rate limiting and JWT auth. Built with Next.js, NestJS and Docker.
- 🎙️ [**SpeakSure**](https://github.com/ninadnaik10/SpeakSure): AI behavioral-interview analysis. Wav2Vec2 embeddings with an MLP score speech confidence, AssemblyAI transcribes, and Gemini generates hiring insights. Research behind the ICCIS 2025 paper.

<details>
<summary><b>🐧 Linux kernel patches (11, merged upstream)</b></summary>
<br>

- [ALSA: docs: fix dead link to Intel HD-audio spec](https://github.com/torvalds/linux/commit/ff722d025853a33a15b080459e4c52be28d44b6e)
- [Documentation: amd-pstate: fix dead links in the reference section](https://github.com/torvalds/linux/commit/a362ae6e7e85bca4c870c37085d7793c4beec360)
- [Documentation: fix spelling mistake "stucture" -> "structure"](https://github.com/torvalds/linux/commit/1cf4830de25495c071a78f307fd66e83ddd586df)
- [Documentation: hwmon: fix link to ideapad-laptop.c file](https://github.com/torvalds/linux/commit/5ed26ffe57ffca054b7a141ff0c1a07bf3a80f6c)
- [Documentation: kvm: update links in the references section of AMD Memory Encryption](https://github.com/torvalds/linux/commit/80f4a7b8ce7513c203562191426e4d4cc635b095)
- [regulator: dt-bindings: mt6311: Convert to DT schema](https://github.com/torvalds/linux/commit/fd964ee0ac9ef14fdc03e30d0ac73459cd60e469)
- [spi: dt-bindings: octeon: Convert to DT schema](https://github.com/torvalds/linux/commit/cb8c374a632b8bfeb8aa2a4977eeeb293f3566a5)
- [regulator: mcp16502: Convert to dev_err_probe() in mcp16502_probe()](https://github.com/torvalds/linux/commit/25706f1ab9fba4b10169f557bf5fcaf41db0bc65)
- [dt-bindings: leds: bcm6358: Convert to DT schema](https://github.com/torvalds/linux/commit/627666f7c9cd89e7c4023ba790a44610ccfb9471)
- [leds: bcm63138: Use %pe to print pinctrl error instead of %ld](https://github.com/torvalds/linux/commit/b6e08e0ad4cfafab2c2070456e7eeba17608a35d)
- [dt-bindings: leds: lacie,ns2-leds: Convert to DT schema](https://github.com/torvalds/linux/commit/e36f8825616b73a09cd2308f2644aa12d7fb6db0)

</details>

<details>
<summary><b>🧩 Other contributions</b></summary>
<br>

- [**CircuitVerse**](https://github.com/CircuitVerse/CircuitVerse): [fix: deadline label casing in en locales](https://github.com/CircuitVerse/CircuitVerse/pull/7106)
- [**n8n Docs**](https://github.com/n8n-io/n8n-docs):
  - [Update source code file links in white-labelling doc to match latest file path](https://github.com/n8n-io/n8n-docs/pull/3395)
  - [Modify expression in tutorial-first-workflow to match the reference image](https://github.com/n8n-io/n8n-docs/pull/3374)
- [**TSEC App**](https://github.com/TSEC-MAD-Club/Mobile-App) ([Play Store](https://play.google.com/store/apps/details?id=com.madclubtsec.tsec_application&pcampaignid=web_share)): College app built with Flutter and Firebase
- [**GeekSpace Website**](https://github.com/geekspaceclub/geekspaceclub.github.io) ([live](https://geekspaceclub.xyz/)): Club website built with Hexo and GitHub Actions

</details>

<details>
<summary><b>📦 More projects</b></summary>
<br>

| Name | Tech | Links |
| --- | --- | --- |
| Vision Guard | Next.js, shadcn/ui | [Website](https://vision-guard.vercel.app/) · [Repo](https://github.com/ninadnaik10/vision-guard) |
| CodeIT | React, Firebase, AWS, Docker | [Website](https://codeitonline.xyz/) · [Repo](https://github.com/ninadnaik10/codeit) |
| FireSense | Python, Flask, Flutter, Firebase | [Repo](https://github.com/ninadnaik10/FireSense) |
| News Forecast | Flutter | [APK](https://github.com/ninadnaik10/News-Forecast/releases) · [Repo](https://github.com/ninadnaik10/News-Forecast) |
| Expense Splitter | Flutter | [APK](https://github.com/ninadnaik10/Expense-Splitter/releases) · [Web](https://ninadnaik10.github.io/expense-splitter-web/) · [Repo](https://github.com/ninadnaik10/Expense-Splitter) |
| Node Socket Chat App | Node.js, Socket.io | [Repo](https://github.com/ninadnaik10/node-socket) |
| Node.js and Firebase CRUD App | Node.js, Firebase | [Repo](https://github.com/ninadnaik10/nodejs-firebase) |
| PassVault | Java, SQLite | [Repo](https://github.com/ninadnaik10/PassVault) |
| Ninad's Blog | Next.js, Markdown, GitHub Actions | [Website](https://blog.ninadnaik.me/) · [Repo](https://github.com/ninadnaik10/blog) |
| Portfolio | HTML, CSS | [ninadnaik.me](https://ninadnaik.me) · [Repo](https://github.com/ninadnaik10/ninadnaik10.github.io) |
| Weather App | Flutter, Dart | [Repo](https://github.com/ninadnaik10/weather-app) |
| Quick List | Flutter, Firebase | [APK](https://github.com/ninadnaik10/QuickList/releases) · [Repo](https://github.com/ninadnaik10/QuickList) |
| Two Numbers | Android, Java | [APK](https://github.com/ninadnaik10/twonumbers/releases) · [Repo](https://github.com/ninadnaik10/twonumbers) |
| Lichens | HTML, CSS | [Website](https://ninadnaik10.github.io/lichens/) |
| Resume Workflow | LaTeX | [resume.ninadnaik.me](https://resume.ninadnaik.me) · [Repo](https://github.com/ninadnaik10/resume) |
| Dotfiles | Shell | [Repo](https://github.com/ninadnaik10/dotfiles) |
| Scripts | Shell | [Repo](https://github.com/ninadnaik10/scripts) |
| GCV NCV Calculator | C | [Repo](https://github.com/ninadnaik10/gcv_ncv_calculator) |

</details>
