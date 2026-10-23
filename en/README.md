<div align="center">
  <h1>Tools, MCP and Skills</h1>
  <h3><em>Designing, publishing and protecting the tools of open language models in Python</em></h3>
  <p>by <strong>Hernán Díaz Rodríguez, PhD</strong> · Professor at the University of Oviedo</p>
  <p>
    <a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg" alt="License: CC BY-NC 4.0"></a>
    <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Colab-free%20T4%20GPU-orange?logo=googlecolab" alt="Colab">
  </p>
</div>

---

## The book

**Tools, MCP and Skills** teaches how to build the tools that language models use: functions the model asks to run to look up data, book appointments or send notices. Over twelve chapters, **Northside Veterinary Clinic**, a clinic in Portland, Oregon, goes from handing a model its API as it is to an ecosystem of tools: names, descriptions and results designed for the model, schemas and contracts, servers and clients with the **MCP** protocol, resources and elicitation, long-running tasks without duplicate charges, defenses against poisoned tools, skills, gateways and registries.

Each chapter changes something in the tools, never in the model, and measures how much the agent improves. Everything runs with **free, open models**, with no API keys or paid services: Qwen3-4B-Instruct-2507 on Colab's free GPU and, without a GPU, Qwen3-1.7B. The MCP servers and clients are written with the official Python SDK, and every figure in the book comes from an experiment you can repeat in the chapter's notebook. This edition is not a plain translation: the clinic, its data and every experiment are its own, run in English.

It belongs to the **AI in Practice** series: hands-on books on artificial intelligence, with original experiments, a notebook and a video in every chapter.

> *¿Prefieres español?* La edición española, **Herramientas, MCP y skills**, está en la [raíz del repositorio](../).

---

## Chapters

Each chapter has its notebook on Google Colab and its video, with Robotín and the author.

| Ch. | Title | Notebook | Video |
|-----|-------|----------|-------|
| 1 | A tool's interface | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/1_A_tools_interface.ipynb) | coming soon |
| 2 | Function calling in depth | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/2_Function_calling_in_depth.ipynb) | coming soon |
| 3 | Schemas and contracts | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/3_Schemas_and_contracts.ipynb) | coming soon |
| 4 | MCP fundamentals | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/4_MCP_fundamentals.ipynb) | coming soon |
| 5 | Building an MCP server | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/5_Building_an_MCP_server.ipynb) | coming soon |
| 6 | The client and the transports | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/6_The_client_and_the_transports.ipynb) | coming soon |
| 7 | Resources, prompts, sampling and elicitation | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/7_Resources_prompts_sampling_and_elicitation.ipynb) | coming soon |
| 8 | Long-running tasks and reliability | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/8_Long_running_tasks_and_reliability.ipynb) | coming soon |
| 9 | Security: poisoned tools and authorization | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/9_Security.ipynb) | coming soon |
| 10 | Skills | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/10_Skills.ipynb) | coming soon |
| 11 | Gateways, registries and A2A | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/11_Gateways_and_registries.ipynb) | coming soon |
| 12 | Project: a tool ecosystem | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/ai-tools-mcp-skills/blob/main/en/notebooks/12_Project_a_tool_ecosystem.ipynb) | coming soon |

---

## How to use the notebooks

- Click **Open in Colab** and run the cells in order. The first cell installs the library versions the book was checked with (`transformers` 5.19.0 and `mcp` 2.3.0, among others).
- Turn on the free GPU: *Runtime → Change runtime type → T4 GPU*. The model takes about 8 GB and the first time it takes a few minutes to download. Without a GPU, the notebooks choose Qwen3-1.7B by themselves, smaller and slower, which fails quite a bit more as an agent.
- The notebooks download the files of the `data/` folder by themselves the first time. The MCP servers and the skills of each chapter are written from the notebook itself.
- MCP's HTTP transport (chapter 6) works on Colab and on Linux; with `mcp` 2.3.0 it does not work on Windows.

---

## Data

Northside Veterinary Clinic and all its data are fictional. The tools work on a copy of the clinic that is reset for every test, so you can make mistakes without consequences. The date of the data is Tuesday, October 20, 2026.

| File | Contents |
|------|----------|
| `pets.json` | The 29 pets, with species, breed, weight, allergies and owner |
| `owners.json` | The 26 clients, with their phone, their e-mail and how they prefer to be notified |
| `history.json` | Each pet's visits: reason, treatment and weight |
| `vaccines.json` | Each pet's vaccines and the date of the next one |
| `appointments.json` | The week's schedule of the three vets |
| `pharmacy.json` | The medicines: presentation, dose per kilo, stock, price and restock |
| `invoices.json` | The clients' invoices, paid and pending |
| `vets.json` | The three vets |
| `prices.json` | The price of each service |

---

## License

This material is distributed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) license: it can be used and adapted for teaching and study, crediting the author, but not for commercial purposes. The models used by the notebooks have their own licenses: Qwen3 (Apache 2.0) and multilingual-e5-small (MIT). The MCP SDK for Python is distributed under the MIT license.
