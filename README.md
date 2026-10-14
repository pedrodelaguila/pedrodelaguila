<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Pedro del Aguila · Full stack developer · backend-leaning" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/pedro-del-aguila/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-pedro--del--aguila-0A66C2?style=flat-square"></a>
  <a href="mailto:delaguilapedro22@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-delaguilapedro22%40gmail.com-57606a?style=flat-square&logo=gmail&logoColor=white"></a>
  <img alt="Universidad Austral, graduating Dec 2027" src="https://img.shields.io/badge/Universidad_Austral-4th_year_·_grad._Dec_2027-57606a?style=flat-square">
  <img alt="Pilar, Buenos Aires" src="https://img.shields.io/badge/Based_in-Pilar,_Buenos_Aires-57606a?style=flat-square">
  <img alt="Spanish native, English C1" src="https://img.shields.io/badge/Spanish_·_English-native_·_C1-57606a?style=flat-square">
</p>

I like owning a feature end to end: the Prisma schema, the NestJS or Spring service behind it, the React screen that uses it,
and the pipeline that ships it. Lately that also means putting **LLMs and computer vision** to work inside real products.

<table>
  <tr>
    <td><b>Backend</b></td>
    <td><img height="32" src="https://skillicons.dev/icons?i=ts,nestjs,prisma,kotlin,spring,python,fastapi" alt="TypeScript, NestJS, Prisma, Kotlin, Spring, Python, FastAPI"></td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td><img height="32" src="https://skillicons.dev/icons?i=react,tailwind,vite" alt="React, Tailwind, Vite"></td>
  </tr>
  <tr>
    <td><b>Data &amp; infra</b></td>
    <td><img height="32" src="https://skillicons.dev/icons?i=postgres,redis,docker,githubactions" alt="PostgreSQL, Redis, Docker, GitHub Actions"></td>
  </tr>
  <tr>
    <td><b>Applied AI</b></td>
    <td>Claude (vision &amp; extraction) · Gemini · YOLO / RF-DETR</td>
  </tr>
</table>

## Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="#lab-iii-1">Lab III</a></h3>
      <sub>Software Lab III · <b>real client</b> · team of 6</sub>
      <p>AutoCAD electrical plans in; bill of materials, supplier quotes and purchase orders out.</p>
      <p><b>My part:</b> full stack + the AI detection service · 440+ commits, 118 merged PRs</p>
      <a href="#lab-iii-1"><img alt="lab3-liard (private)" src="https://img.shields.io/badge/lab3--liard-private-6e7781?style=flat-square"></a>
      <br><br>
      <a href="#lab-iii-1">Read more ↓</a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/grupo6-ingsis">PrintScript + Snippet Searcher</a></h3>
      <sub>Ingeniería de Sistemas · team of 3</sub>
      <p>A language of our own, published as a Kotlin library and run inside a microservices platform.</p>
      <p><b>My part:</b> linter &amp; formatter, the main API, infra · top contributor in 3 repos</p>
      <a href="https://github.com/grupo6-ingsis"><img alt="grupo6-ingsis" src="https://img.shields.io/badge/grupo6--ingsis-organization-24292f?style=flat-square&logo=github"></a>
      <br><br>
      <a href="#printscript--snippet-searcher-1">Read more ↓</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Bovelez/bovelez">Bovelez</a></h3>
      <sub>Aseguramiento de la Calidad de Software · team of 5</sub>
      <p>Stock portfolio tracker built around testing: unit, integration, Cypress, Appium and Locust.</p>
      <p><b>My part:</b> top contributor · backend, mobile front, the Appium suite and CI</p>
      <a href="https://github.com/Bovelez/bovelez"><img alt="bovelez" src="https://img.shields.io/badge/bovelez-repo-24292f?style=flat-square&logo=github"></a>
      <br><br>
      <a href="#bovelez-1">Read more ↓</a>
    </td>
    <td width="50%" valign="top">
      <h3><a href="#rivalmatch-1">RivalMatch</a></h3>
      <sub>Software Lab II · team of 4</sub>
      <p>Amateur teams find a rival, get matched, then chat, schedule and record the result.</p>
      <p><b>My part:</b> top committer on the UI · real-time chat, maps · search lifecycle in the back</p>
      <a href="#front--rivalmatch-ui"><img alt="rivalmatch-ui (private)" src="https://img.shields.io/badge/rivalmatch--ui-private-6e7781?style=flat-square"></a>
      <a href="#back--rivalmatch-back"><img alt="rivalmatch-back (private)" src="https://img.shields.io/badge/rivalmatch--back-private-6e7781?style=flat-square"></a>
      <br><br>
      <a href="#rivalmatch-1">Read more ↓</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Agustinguglielmelli/coding-agent">Coding Agent</a></h3>
      <sub>Inteligencia Artificial · final project · team of 3</sub>
      <p>A coding agent that plans, implements and validates changes in a NestJS repo, alone or as a chain of 5 subagents.</p>
      <p><b>My part:</b> local RAG, persistent memory, the first multi-agent version, Langfuse tracing</p>
      <a href="https://github.com/Agustinguglielmelli/coding-agent"><img alt="coding-agent" src="https://img.shields.io/badge/coding--agent-repo-24292f?style=flat-square&logo=github"></a>
      <br><br>
      <a href="#coding-agent-1">Read more ↓</a>
    </td>
    <td width="50%" valign="top"></td>
  </tr>
</table>

<sub>Grey badges are private repos; they link to the write-up below instead.</sub>

---

## Lab III

<sub><b>Electrical plans → bill of materials</b> · Software Lab III, Universidad Austral · built for a <b>real client</b> · team of 6 · private repo</sub>

Engineers upload AutoCAD plans of electrical panels (DXF, DWG or PDF). A detector finds every symbol, an LLM reads what each
one is, and the result is a bill of materials that gets quoted against supplier catalogs and turned into purchase orders.
It replaces counting symbols by hand, which took from half an hour to a full day per panel.

```mermaid
flowchart LR
    A["Plan<br/>DXF · DWG · PDF"] --> B["Detector<br/>finds symbols"] --> C["Claude<br/>reads each one"]
    C --> D["Bill of materials"] --> E["Quotes &<br/>purchase orders"]
```

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Frontend</b> · <sub>React</sub>
      <ul>
        <li>Auth and onboarding per role (engineer / supplier)</li>
        <li>Purchase orders module</li>
        <li>Plans dashboard and consolidated BOM with Excel/CSV export</li>
        <li>Supplier catalog panel with import history and a review queue</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>Backend</b> · <sub>NestJS + Prisma</sub>
      <ul>
        <li>Projects module and plan processing against the detection service</li>
        <li>Quotations and the catalog matching engine</li>
        <li>Role and onboarding enforcement</li>
        <li><b>AI catalog normalizer</b>: Claude Haiku links each supplier row to a base component type, with measured cost and time</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>Detection service</b> · <sub>Python + FastAPI</sub>
      <ul>
        <li>Started the microservice</li>
        <li>DWG → DXF conversion (LibreDWG compiled into the image)</li>
        <li>A Claude search for symbols the detector missed</li>
        <li>Gemini as a second provider, with cost comparisons</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>Tooling</b> · <sub>GitHub Actions</sub>
      <ul>
        <li>Automated Claude PR review that reads the linked ticket and posts one structured comment</li>
      </ul>
    </td>
  </tr>
</table>

<sub>`React` `TanStack Query` `Zustand` `NestJS` `Prisma` `PostgreSQL` `FastAPI` `YOLO / RF-DETR` `Claude` `Docker` `GitHub Actions`</sub>

<sub>[↑ back to projects](#projects)</sub>

## PrintScript + Snippet Searcher

<sub><b>A language and the platform that runs it</b> · Ingeniería de Sistemas, Universidad Austral · team of 3 · <a href="https://github.com/grupo6-ingsis">grupo6-ingsis</a></sub>

Two halves of one course: first we wrote a language, then we built a platform that runs it. **PrintScript** is a small typed
language in Kotlin (lexer, parser, AST, interpreter, formatter, configurable linter, CLI) over a streaming pipeline; every push to
`main` **publishes each module to GitHub Packages**. **Snippet Searcher** lets users write, share, lint, format and run PrintScript
snippets, and its engine depends on those published artifacts, so a new language version reaches the app by bumping one dependency.

```mermaid
flowchart LR
    PS["printscript2<br/>Kotlin library"] -- "CI publishes<br/>org.gudelker:*" --> GP[("GitHub<br/>Packages")]
    GP --> EN["snippet-engine<br/>parse · run · lint · format"]
    UI["printscript-ui<br/>React"] --> SS["snippet-service<br/>main API"]
    SS -- "Redis Streams" --> EN
    SS --> AU["authorization<br/>per-snippet permissions"]
```

<table>
  <tr>
    <td width="50%" valign="top">
      <b>The language</b> · <sub>Kotlin + Gradle</sub>
      <ul>
        <li>Linter rules and their integration tests</li>
        <li>Formatter rules</li>
        <li>Positions in the AST</li>
        <li>The streaming pipeline and the publishing tasks</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>The platform</b> · <sub>Spring Boot + Redis Streams</sub>
      <ul>
        <li>Main author of the snippet service: languages and versions, snippets from files, permissions, the Redis lint/format publishers</li>
        <li>The Redis consumers in the engine</li>
        <li>Docker / nginx / Let's Encrypt infra with deploys to VMs</li>
        <li>The Cypress suite of the UI</li>
      </ul>
    </td>
  </tr>
</table>

<p>
  <a href="https://github.com/grupo6-ingsis/printscript2"><img alt="printscript2" src="https://img.shields.io/badge/printscript2-language-24292f?style=flat-square&logo=github"></a>
  <a href="https://github.com/grupo6-ingsis/snippet-service2"><img alt="snippet-service2" src="https://img.shields.io/badge/snippet--service2-main_API-24292f?style=flat-square&logo=github"></a>
  <a href="https://github.com/grupo6-ingsis/snippet-engine2"><img alt="snippet-engine2" src="https://img.shields.io/badge/snippet--engine2-runner-24292f?style=flat-square&logo=github"></a>
  <a href="https://github.com/grupo6-ingsis/infra"><img alt="infra" src="https://img.shields.io/badge/infra-Docker_·_nginx-24292f?style=flat-square&logo=github"></a>
  <a href="https://github.com/grupo6-ingsis/printscript-ui"><img alt="printscript-ui" src="https://img.shields.io/badge/printscript--ui-React_·_Cypress-24292f?style=flat-square&logo=github"></a>
</p>

<sub>`Kotlin` `Spring Boot` `Gradle` `Redis Streams` `PostgreSQL` `Auth0` `React` `Cypress` `Docker` `nginx` `GHCR`</sub>

<sub>[↑ back to projects](#projects)</sub>

## Bovelez

<sub><b>Stock portfolio tracker, graded on its tests</b> · Aseguramiento de la Calidad de Software, Universidad Austral · team of 5 · <a href="https://github.com/Bovelez/bovelez">Bovelez/bovelez</a></sub>

Buy and sell stocks validated against SEC EDGAR and follow the portfolio with live prices, in a project graded on how well it is
tested: unit, integration, Cypress, Appium on Android and Locust load testing.

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Backend</b> · <sub>NestJS + FastAPI</sub>
      <ul>
        <li>Users and the transactions module</li>
        <li>EDGAR and prices integration</li>
        <li>S&amp;P 500 seed and the hourly price batch</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <b>Front &amp; QA</b> · <sub>React + Appium</sub>
      <ul>
        <li>Portfolio screens on web</li>
        <li>Most of the <b>mobile front</b></li>
        <li>The whole <b>Appium mobile e2e suite</b>: auth, portfolio, stock, watchlist, overselling</li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <b>Repo &amp; CI</b> · <sub>GitHub Actions</sub>
      <ul>
        <li>Repo and Docker setup</li>
        <li>A <b>CI that only runs what changed</b></li>
        <li>A weekly release digest by email</li>
      </ul>
    </td>
  </tr>
</table>

<p>
  <a href="https://github.com/Bovelez/bovelez"><img alt="bovelez" src="https://img.shields.io/badge/bovelez-repo-24292f?style=flat-square&logo=github"></a>
</p>

<sub>`NestJS` `Prisma` `FastAPI` `React` `Cypress` `Appium` `Locust` `GitHub Actions` `semantic-release`</sub>

<sub>[↑ back to projects](#projects)</sub>

## RivalMatch

<sub><b>Find a rival team and play them</b> · Software Lab II, Universidad Austral · team of 4 · private repos, front and back</sub>

Amateur teams post a rival search (sport, size, date, place), get matched with compatible teams, then chat, schedule and record
results.

<table>
  <tr>
    <td width="50%" valign="top">

#### Front · rivalmatch-ui

<sub>React + Tailwind · <b>top committer</b></sub>

- Real-time chat over Socket.IO with notifications and read receipts
- Map view with Google Maps marker clustering
- Calendar, "my matches" and match history

</td>
    <td width="50%" valign="top">

#### Back · rivalmatch-back

<sub>NestJS + Prisma</sub>

- Team and RivalSearch entities
- The search lifecycle: expiry, active vs. matched
- Pagination, password change confirmed by email, the CI workflow

</td>
  </tr>
</table>

<sub>`NestJS` `Prisma` `PostgreSQL` `Socket.IO` `React` `Tailwind` `Google Maps`</sub>

<sub>[↑ back to projects](#projects)</sub>

## Coding Agent

<sub><b>An agent that writes code in a real repo</b> · Inteligencia Artificial, Universidad Austral · final project · team of 3 · <a href="https://github.com/Agustinguglielmelli/coding-agent">Agustinguglielmelli/coding-agent</a></sub>

A coding agent in Node.js, with no orchestration framework, pointed at the RivalMatch backend (NestJS). It plans a task, asks for
approval, then works alone or as a chain of five subagents, each with only the permissions its step needs. It reads and writes
files and runs commands under read, write and command policies, with human approval for the sensitive ones. It runs on OpenAI or Gemini.

```mermaid
flowchart LR
    T["Task"] --> EX["Explorer<br/>reads the repo"] --> RE["Researcher<br/>memory · RAG · web"]
    RE --> IM["Implementer<br/>edits files"] --> TE["Tester<br/>runs checks"] --> RV["Reviewer<br/>reviews the diff"]
```

<table>
  <tr>
    <td width="50%" valign="top">
      <b>Context</b> · <sub>RAG + memory</sub>
      <ul>
        <li>The <b>local RAG</b>: chunking, embeddings and similarity search over the project's docs</li>
        <li><b>Persistent project memory</b>: architecture, conventions and decisions kept between sessions</li>
        <li>The agent configuration, and a workspace set by env so it can work on any repo</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>Agents &amp; observability</b> · <sub>Node.js + Langfuse</sub>
      <ul>
        <li>The <b>first version of the multi-agent mode</b> and the five-subagent task</li>
        <li>The OpenAI client used to test it</li>
        <li><b>Langfuse / OpenTelemetry traces</b> per subagent and per tool call</li>
      </ul>
    </td>
  </tr>
</table>

<p>
  <a href="https://github.com/Agustinguglielmelli/coding-agent"><img alt="coding-agent" src="https://img.shields.io/badge/coding--agent-repo-24292f?style=flat-square&logo=github"></a>
</p>

<sub>`Node.js` `OpenAI` `Gemini` `RAG` `Multi-agent` `Langfuse` `OpenTelemetry` `Tavily`</sub>

<sub>[↑ back to projects](#projects)</sub>

---

<details>
<summary><b>Versión en español</b></summary>
<br>

Soy desarrollador **full stack con foco en backend** y estudio 4.º año de Ingeniería Informática en la **Universidad Austral**
(egreso estimado: diciembre 2027). Vivo en Pilar, Buenos Aires. Me gusta hacerme cargo de una funcionalidad de punta a punta:
el esquema, el servicio, la pantalla y el pipeline que la despliega.

- **[Laboratorio III](#lab-iii-1)** (proyecto con un cliente real, equipo de 6, repo privado): convierte planos eléctricos de
  AutoCAD en listado de materiales, cotizaciones y órdenes de compra. Trabajé en front (onboarding, órdenes de compra, BOM,
  catálogo de proveedores), en back (proyectos, procesamiento de planos, cotización y matching, normalización de catálogos con
  Claude) y en el servicio de detección en Python.
- **[PrintScript + Snippet Searcher](https://github.com/grupo6-ingsis)** (Ingeniería de Sistemas, equipo de 3): escribimos un
  lenguaje en Kotlin, lo publicamos como librería en GitHub Packages y lo usamos dentro de una plataforma de microservicios con
  Spring Boot y Redis Streams. Hice reglas del linter y el formatter, el servicio principal, la infraestructura y los tests de Cypress.
- **[Bovelez](https://github.com/Bovelez/bovelez)** (Aseguramiento de la Calidad de Software, equipo de 5): tracker de acciones.
  Armé el repo y el CI, parte del back, el front mobile y toda la suite de e2e mobile con Appium.
- **[RivalMatch](#rivalmatch-1)** (Laboratorio II, equipo de 4, repos privados de front y back): búsqueda de rivales para equipos
  amateurs. Chat en tiempo real, mapa y calendario en el front; equipos y ciclo de vida de las búsquedas en el back.
- **[Coding Agent](https://github.com/Agustinguglielmelli/coding-agent)** (trabajo final de Inteligencia Artificial, equipo de 3):
  un agente de código en Node.js que planifica, implementa y valida cambios en el backend de RivalMatch, solo o con cinco
  subagentes. Hice el RAG local, la memoria persistente del proyecto, la primera versión del modo multiagente y las trazas con Langfuse.

</details>
