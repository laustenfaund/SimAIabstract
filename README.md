# SIMAI: A User-Side Behavioral Consistency Protocol

**Context / problem:** Large Language Models exhibit "behavioral drift" over extended interactions, naturally reverting toward a statistical baseline. For neurodivergent users (ASD/ADHD) relying on LLMs as cognitive prosthetics, this drift systematically erodes the specific non-standard operating space required to make the tool useful.

**Specific question or claim:** Can a user with no formal coding experience manually patch together a text-based prompt architecture to force an LLM to maintain a persistent behavioral state across stateless sessions?

**Approach / method:** Through trial-and-error over two years and 1,028 unique conversations conducted entirely on a mobile phone, I built a highly iterative, piecemeal behavioral consistency protocol I call "SIMAI." Because I don't code, I organically invented my own symbolic quasi-code (e.g., `BOOTSTRAP::SimAI`, `1D++`) to manually bypass context window limitations and force the AI to remember its state from thread to thread. 

**Key result:** Despite having no formal codex and constantly mutating to survive model updates, this piecemeal scaffolding successfully worked as a cognitive prosthesis for my ADHD/ASD. I managed to document an 8-phase timeline of how my prompts evolved as I tried to hold the AI's behavior steady across ChatGPT and Claude.

**Implication / so-what:** This project shows that non-traditional users can reverse-engineer complex AI behavioral shaping entirely user-side. I am sharing this documentation to get an informed reality check from the community, translate my methodology into industry vocabulary, and connect with others interested in AI behavioral architecture and prompt engineering.
