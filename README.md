# emergence-benchmarks

<img src="figures/emergence_favicon_300x300.png" alt="Icon" width="50">


Custom Benchmarks for Agents.

This repository contains the first version of enterprise benchmarks for web-agents, **E-Web**, designed to evaluate the performance, reliability, and efficiency of automated web-agents. These benchmarks are specifically tailored for enterprise-level applications and provide valuable insights into agent behavior and capabilities.
## 📄 **Affiliated Paper**  
The research paper detailing the development and use of these benchmarks is also available. It provides in-depth information about the methodology, experimental setup, and analysis of the benchmark itself.  This will be available in arXiv soon and the link will be provided here.

[Link to Paper (PDF)](papers/e-web/e-web-v0.pdf)

<!-- ![Project Logo](path/to/logo.png)  <!-- Optional: Add a logo or project image -->


## Project Description

This project aims to provide a standardized benchmark suite for evaluating the performance and capabilities of web agents (automated systems designed for web interaction) in the enterprise setting

### Key Features:
- **Comprehensive Benchmark Suite**: A collection of various prompts to evaluate web-agent performance across different domains and tasks in the enterprise setting. We have covered 15 broad domains and 26 websites(tools/apps).
<img src="figures/Website_distribution.png" alt="Icon" width="600">

- **Focus on underlying skills**: The primary focus of this benchmark is to evaluate the capabilities of agents across core web skills such as manipulating UI elements.
<img src="figures/Skill_Type_distribution.png" alt="Icon" width="600">

- **Data Made Available**: The benchmark dataset currently contains a total of 220 prompts, 65 of which are made available in this repository [here](benchmarks/e-web/e-web_benchmark_lite.csv)

### In the Pipeline/Upcoming:
- Broader, more comprehensive coverage of skills, domains and tools.
- Evaluating capabilities beyond web skills such as API connections, tool calling abilities, etc.

---

### Folder Structure

The repository contains the following structure:

- `benchmarks/`: Contains benchmark data and results.
    - `e-web/`: Specific benchmarks for the e-web project.
        - `e-web_benchmark_lite.csv`: A CSV file with the lite version of the e-web benchmark results.
- `papers/`: Contains research papers and related documents.
    - `e-web/`: Specific papers for the e-web project.
        - `e-web-v0.pdf`: The version 0 of the e-web research paper.
- `figures/` : Contains figures

---
