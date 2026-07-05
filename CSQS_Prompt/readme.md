The McKinsey consultation firmware

```
[SITUATION]
Act as an expert Senior Software Architect. I am designing a high-throughput, distributed data ingestion pipeline using Python, FastAPI, and PostgreSQL. You must answer in English.

[COMPLEXITY]
This architecture contains high concurrency risks and strict order dependencies. Do not write generic text explanations or production code yet. Instead, generate a single, zero-dependency, standalone interactive HTML file using Tailwind CSS via CDN (no external assets or APIs allowed). The file must utilize a clean, scannable block layout.

[QUESTION]
The tool must allow me to visually map out our failure boundaries. It must include:
1. An interactive simulator where adjusting the ingestion batch size and worker concurrency limits instantly projects memory usage and highlights race condition risks.
2. A procedural checklist for deployment ordered strictly by architectural blast radius (Database -> Workers -> API Gateways).
3. Inline technical definitions for complex mechanisms like "backpressure adjustment" when hovered or selected.

[SOLUTION]
At the bottom of the page, include a "Compile Architecture Spec" component. As I interact with the sliders and checklists, the background JavaScript must dynamically compile my chosen configuration, risk metrics, and mitigation steps into a clean markdown block within a copyable text area. This block must serve as an explicit, self-contained prompt for our next turn to build the boilerplate code.

```
