# 3. Future Roadmap

The Sniffing project is evolving rapidly. Following the successful validation of the core generative engine, our development roadmap focuses on scaling the platform into a robust, self-service SaaS and deepening the collaborative intelligence of our AI agents.

## Phase 1: V2 Self-Service Platform (In Progress)
The immediate goal is to transition from a managed prototype to a fully autonomous, user-facing SaaS platform.

- **Authentication & User Management:** Secure login systems (OAuth, Email) allowing individual researchers and teams to manage their profiles and data.
- **Personalized Workspaces:** Users will be able to create independent projects, uploading their own PDFs to generate private or shared knowledge graphs.
- **Real-Time Extraction Pipeline:** An optimized backend architecture to process documents asynchronously, providing users with live progress updates during the extraction and vectorization phases.
- **Billing & Subscription Models:** Implementation of a tiered SaaS model (Freemium, Pro, Enterprise) to monetize API usage and advanced multi-agent features.

## Phase 2: Advanced Collaborative Agents
The heart of Sniffing is the Dialogue Table. The next iteration will significantly expand the agents' capabilities.

- **Dynamic Persona Generation:** Instead of fixed roles, the system will dynamically instantiate agents with specific academic backgrounds tailored to the intersection being debated (e.g., spawning a "Biochemist" and a "Data Scientist" when those fields collide).
- **Tool Use & Fact-Checking:** Agents will be equipped with tools to query external databases (e.g., PubMed, ArXiv) in real-time to validate their arguments during the debate.
- **Epistemic Tension Resolution:** Improved algorithms to manage contradictions between papers, allowing agents to constructively debate conflicting data and propose synthesis rather than hallucinating consensus.
- **User Intervention:** Allowing the human researcher to step into the Dialogue Table at any point to steer the debate, ask clarifying questions, or inject new constraints.

## Phase 3: Ecosystem Integration
- **API & Integrations:** Allowing university libraries and corporate R&D departments to connect their existing repositories (SharePoint, DSpace) directly to the Sniffing ingestion engine.
- **Global Cross-Pollination Graph:** An opt-in global graph where researchers can anonymously discover if their private "Needs" match the public "Contributions" of other teams worldwide, fostering organic academic collaboration.
