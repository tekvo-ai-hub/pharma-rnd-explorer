# Research Paper Explorer

**Industry:** Pharma

**Repository:** [tekvo-ai-hub/pharma-rnd-explorer](https://github.com/tekvo-ai-hub/pharma-rnd-explorer)

## Description
A secure assistant for querying proprietary pharma research and trial data.

## Requirements
### Functional
- Ingest clinical trial papers.
- Enable natural language search.
- Highlight compound performance.
### Non-Functional
- GxP-compliant logging.
- Private cloud only.
- High accuracy.
## Solution Design
**LLM:** Nous Hermes 2
**Vector DB:** Weaviate

### Components
- Research PDF Parser
- Vector Indexer
- LLM Q&A Layer
- Compound Trend Analyzer
### Data Flow
$ PDF → Extract → Embed → Index → Retrieve → Answer

### Tech Stack
- **Frontend:** Dash
- **Backend:** Flask
- **Storage:** S3 (Private)
- **Deployment:** AWS Private VPC
