#ABM #communities

PROJET: [PROJECT Collective Degrowth Experiments (CODEX)](PROJECT%20Collective%20Degrowth%20Experiments%20(CODEX).md)

## Hypotheses
- Influence of personality traits and governance rules on efficiency
- Effect of diversity on efficiency
- Majority vs. consensus: impact on community cohesion
- Role of leadership 
## **Sustainable Livelihoods Approach**
### 5 core asset categories that influence livelihood strategies:
#### a. Human Capital: 
- Skills, knowledge, education, and health of individuals
- Leadership roles, training, capacity to work
#### b. Social Capital
- Community networks, social norms, trust, and cooperation.
- Governance structures, shared responsibilities, local decision-making.
#### c. Natural Capital
- Land, water, biodiversity, and ecological resources.
- Permaculture practices, renewable energy, waste recycling.
#### d. Physical Capital
- Infrastructure, tools, and technologies that support livelihoods.
- Housing, solar panels, communal kitchens, transport systems.
#### e. Financial Capital
- Income sources, savings, investments, and access to financial resources.
- Cooperative businesses, crowdfunding, public funding
### Defining the agents and their behavior
- **Agents:** Ecovillage residents, external stakeholders (e.g., funders, policymakers).
- **Attributes:** Each agent has different endowments of SLA assets.
- **Decision-Making:**
    - Individual and collective choices are influenced by resource availability, social norms, and environmental changes.
    - Use **utility-based or rule-based decision models.**
- **Interactions:**
    - Cooperation for resource management.
    - Social learning and adaptation.
    - Conflict resolution and governance.
### Designing the environment
- **Spatial and Ecological Layout:**
    - Households, shared spaces, natural resources, and infrastructure.
- **Policies and Institutions:**
    - Rules for land use, conflict resolution, income generation.

### Defining rules and interactions
- **Resource Sharing:** How food, water, and energy are distributed.
- **Social Dynamics:** Trust-building, knowledge exchange, decision-making processes.
- **Economic Activities:** Cooperative work, external trade, and self-sufficiency.
- **Adaptation Strategies:** Responses to climate change, policy shifts, and economic challenges.

## **Institutional Analysis and Development**
### key components:

- Action Arena: The space where individuals interact and make decisions.
Includes actors (individuals, groups) and the action situation (the context in which they make choices).
- Actors (Agents in the Model): Ecovillage residents, external organizations (e.g., NGOs, policymakers). Each agent has distinct preferences, decision rules, and resource endowments.

- Physical/Material Conditions: Availability of natural resources (land, water, food, energy). Infrastructure (housing, shared spaces, roads, internet).
- Attributes of the Community: Social structures, trust levels, past experiences in cooperation. Governance structures (formal and informal institutions).
- Rules-in-Use: **Operational rules**: Daily practices (e.g., how much water can be used per household). **Collective-choice rules**: Decision-making processes (e.g., voting on sustainability projects). **Constitutional rules**: Higher-level governance (e.g., membership policies, land use rights).
- Outcomes & Evaluation: Resource sustainability, economic resilience, social well-being. Conflict resolution mechanisms and adaptability to external shocks

### Agents and Their Behaviors
Each agent represents an ecovillage resident with the ability to:
-  Participate in community decision-making.
- Use and contribute to common-pool resources (food, water, energy).
- Adapt to environmental and economic changes.
Decision Rules:
- Cooperative Agents: Prioritize community well-being (e.g., contribute to shared projects).
- Self-Interested Agents: Prioritize personal gains (e.g., overusing shared water sources).
- Adaptive Agents: Modify behavior based on past interactions and observed community norms.

## Computational model of IAD
Montes, N., Osman, N., & Sierra, C. (2022). A computational model of Ostrom’s Institutional Analysis and Development framework. Artificial Intelligence, 311, 103756.
--> Prolog and [python toolbox](https://www.ai4europe.eu/research/ai-catalog/ngames) for implementing ABM based on IAD 
Unfortunately, Action Situation Language does not include an avenue to model instructions and precepts in a systematic manner -> not concerned with the individual decision-making

Oesterling, N., Ambrose, G., & Kim, J. (2024). Understanding the Emergence of Computational Institutional Science. _International Journal of the Commons_, _18_(1), 425–443.
--> review of all works on ABMs of social interactions

## Multi-agent reinforcement learning
Hertz, U., Köster, R., Janssen, M. A., & Leibo, J. Z. (2025). Beyond the matrix: Experimental approaches to studying cognitive agents in social-ecological systems. _Cognition_, _254_, 105993.

### Pattern-Oriented Modeling of Commons Dilemma Experiments
Janssen, M. A., Radtke, N. P., & Lee, A. (2009). Pattern-Oriented Modeling of Commons Dilemma Experiments. _Adaptive Behavior_, _17_(6), 508–523. [https://doi.org/10.1177/1059712309342488](https://doi.org/10.1177/1059712309342488)


https://link.springer.com/article/10.1007/s10588-012-9107-0?

Textbook: https://myongchang.github.io/research/papers/Handbook-12.05.pdf?

### Toolboxes
##### ABM based on generative AI
[Smallville](https://github.com/joonspk-research/generative_agents)
[Minecraft](https://github.com/MineDojo/Voyager)
[Autogen](https://github.com/microsoft/autogen)

LangChain	Orchestration multi-agents + LLMs open-source
CrewAI	Coordination d'agents IA, très léger et libre
Haystack (de deepset)	Pipelines LLMs complexes
OpenAgents	Early-stage multi-agent systems

###### **Outils concrets gratuits pour tout monter**

|Besoin|Solution gratuite|
|---|---|
|Modèle de langage|LLaMA 2 / Mistral 7B / Mixtral|
|Orchestration multi-agent|CrewAI / LangChain|
|Serveur d'inférence (facultatif)|Ollama (local LLM runner), Hugging Face|
|Simulation / ABM|Mesa (lib Python pour Agent-Based Modeling)|
Exemple de Stack gratuite

1. **LLM local** : Mistral 7B via **[Ollama](https://ollama.com/)** ou Hugging Face.
2. **Coordination des agents** : **[CrewAI](https://github.com/crewAIInc/crewAI)** (Python).
3. **Simulation du monde** : **[Mesa](https://github.com/projectmesa/mesa)** pour gérer environnement/simulation.
4. Possibilité de le situer dans MineCraft via Mineflayer ou MineDojo
5. Possibilité de le situer dans FarmSim
## CR Marco Janssen
### March 26, 2025
2 other visitors
ASU --> biggest campus in the US / many conferences and big guys 
Artist community: will give me info
Biosphere 2 (1990s --> environment) - Arizona / food growing 
Monday seminar - 
National Institute: Global Futures Lab - College of Global Futures - School of sustainability 
Robert Putnam - Join or die / 
Intelligence and collective experiments --> intelligent fare better (numeracy for instance)
Interested in personnality types 

The Art community I mentioned is Arcosanti and can be found here: [https://www.arcosanti.org/](https://www.arcosanti.org/)

Info on Biosphere 2 can be found at [https://biosphere2.org/](https://biosphere2.org/)

More on the project I did 8 years ago can be found here: [https://www.ecologyandsociety.org/vol23/iss4/art8/](https://www.ecologyandsociety.org/vol23/iss4/art8/)