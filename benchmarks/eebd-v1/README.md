# Emergence Enterprise Benchmark Dataset (EEBD) - v1

## Overview

The Emergence Enterprise Benchmark Dataset version 1 (EEBD-v1) is designed to evaluate the capabilities of AI agents in performing realistic enterprise workflows. It addresses limitations in existing benchmarks by focusing on tasks that require interaction across multiple applications, adherence to specific processes, and navigation of typical enterprise tools beyond simple web browsing. EEBD-v1 includes 45 distinct tasks representing an initial capture of "Layer 1" (Component Tasks) and "Layer 2" (Cross-Application Workflows), as conceptualized in our layered benchmarking approach (detailed in our upcoming blog post, "Layer by Layer: A Structured Approach to Benchmarking AI Agents in the Enterprise"). The primary goal is to assess an agent's ability to handle contextual complexity, utilize different execution paths (UI and API where applicable), and manage information across diverse enterprise scenarios.

## Key Characteristics

*   **Realistic Enterprise Tasks:** Queries mirror common activities like market research, competitive analysis, IT incident management, documentation, travel booking, and integration management.
*   **Multi-Tool Interaction:** Tasks require agents to use a combination of tools, including:
    *   Web Browsers (for research, accessing public data)
    *   Enterprise Collaboration Platforms (Confluence, Word for documentation)
    *   IT Service Management Tools (JIRA for ticketing/task tracking)
    *   APIs (Amadeus for travel planning, JIRA, Confluence for integration)
*   **Cross-Application Workflows:** Many tasks involve gathering information from one source (e.g., Web) and using it within another (e.g., Confluence, JIRA, Word).
*   **Varied Complexity:** Tasks range from straightforward information retrieval to complex multi-step planning and data synthesis.
*   **Diverse Categories:** Covers domains including Research, Competitive Analysis, Financial Analysis, Integration Management, Incident Management, Sales/Bids, and Travel.

## Dataset Structure

The dataset is provided in a CSV format with the following columns:

*   `qid`: A unique identifier for each query/task.
*   `query`: The natural language instruction describing the task for the AI agent.
*   `category`: The general domain or type of the enterprise task.
*   `tools`: The primary tools or platforms required to complete the task.

## Scope of EEBD-v1

This initial version (v1) contains 45 tasks. Examples include:
*   Researching market data online and documenting findings in Confluence or Word.
*   Performing competitive analysis using web searches.
*   Monitoring service status pages and creating corresponding JIRA tickets.
*   Planning complex travel itineraries using the Amadeus API.
*   Managing software integration updates between different platforms like Slack, JIRA, and Confluence.

## Evaluation

Given the open-ended nature and reliance on specific enterprise environments/tools for many tasks, evaluation often requires manual verification to confirm successful completion according to the query's core requirements.

## Citation

This dataset was developed as part of the work described in the blog post: "Beyond the Browser: Benchmarking the Next Generation of Enterprise AI Agents".
