# Swarms

**Building and scaling Collective Super Intelligence (CSI)**

[![Website](https://img.shields.io/badge/Website-swarms.ai-000000?style=for-the-badge)](https://swarms.ai)
[![Docs](https://img.shields.io/badge/Docs-docs.swarms.world-000000?style=for-the-badge)](https://docs.swarms.world)
[![Marketplace](https://img.shields.io/badge/Marketplace-swarms.world-000000?style=for-the-badge)](https://swarms.world)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/EamjgSaEQf)
[![X](https://img.shields.io/badge/X-@swarms__corp-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/swarms_corp)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/swarms-corp)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@kyegomez3242)

## Mission

No single model will solve every problem. Our mission is to build and scale **Collective Super Intelligence**: intelligence that emerges when many agents plan, debate, specialise and work in parallel, so that the swarm can do what no single agent can.

We build the infrastructure for it: open-source frameworks for orchestrating agents, production systems that run them at scale, and research that measures when and why many agents beat one.

## Start here

```bash
pip install -U swarms
```

```python
from swarms import Agent, SequentialWorkflow

researcher = Agent(agent_name="Researcher", model_name="gpt-5.4")
writer = Agent(agent_name="Writer", model_name="gpt-5.4")

swarm = SequentialWorkflow(agents=[researcher, writer])
print(swarm.run("Explain how swarms of agents outperform a single model."))
```

## Popular repositories

### Frameworks

| Repository | Stars | What it is |
|---|---|---|
| [**swarms**](https://github.com/kyegomez/swarms) | ![](https://img.shields.io/github/stars/kyegomez/swarms?style=flat&label=) | The enterprise-grade multi-agent orchestration framework |
| [swarms-rs](https://github.com/The-Swarm-Corporation/swarms-rs) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/swarms-rs?style=flat&label=) | Multi-agent orchestration in Rust |
| [swarms-js](https://github.com/The-Swarm-Corporation/swarms-js) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/swarms-js?style=flat&label=) | Swarms for JavaScript and TypeScript |
| [swarms-tools](https://github.com/The-Swarm-Corporation/swarms-tools) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/swarms-tools?style=flat&label=) | Pre-built tools and MCP servers for agents |
| [swarms-memory](https://github.com/The-Swarm-Corporation/swarms-memory) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/swarms-memory?style=flat&label=) | RAG wrappers for ChromaDB, Pinecone, Weaviate and more |
| [swarms-cloud](https://github.com/The-Swarm-Corporation/swarms-cloud) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/swarms-cloud?style=flat&label=) | Deploy agents to production |

### Applications

| Repository | Stars | What it is |
|---|---|---|
| [**AutoHedge**](https://github.com/The-Swarm-Corporation/AutoHedge) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/AutoHedge?style=flat&label=) | An autonomous hedge fund run by a swarm of agents |
| [ClawSwarm](https://github.com/The-Swarm-Corporation/ClawSwarm) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/ClawSwarm?style=flat&label=) | A lightweight, natively multi-agent assistant across Telegram, Discord and WhatsApp |
| [MedicalCoderSwarm](https://github.com/The-Swarm-Corporation/MedicalCoderSwarm) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/MedicalCoderSwarm?style=flat&label=) | Multi-agent medical diagnosis and coding |
| [TickrAgent](https://github.com/The-Swarm-Corporation/TickrAgent) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/TickrAgent?style=flat&label=) | Swarms of financial agents for stock analysis |
| [CryptoAgent](https://github.com/The-Swarm-Corporation/CryptoAgent) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/CryptoAgent?style=flat&label=) | Real-time cryptocurrency analysis |
| [HospitalSim](https://github.com/The-Swarm-Corporation/HospitalSim) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/HospitalSim?style=flat&label=) | A multi-agent hospital simulation |

### Research implementations

| Repository | Stars | What it is |
|---|---|---|
| [AI-CoScientist](https://github.com/The-Swarm-Corporation/AI-CoScientist) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/AI-CoScientist?style=flat&label=) | Google's "Towards an AI co-scientist" |
| [Open-MAI-Dx-Orchestrator](https://github.com/The-Swarm-Corporation/Open-MAI-Dx-Orchestrator) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/Open-MAI-Dx-Orchestrator?style=flat&label=) | Microsoft's "Sequential Diagnosis with Language Models" |
| [AdvancedResearch](https://github.com/The-Swarm-Corporation/AdvancedResearch) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/AdvancedResearch?style=flat&label=) | Anthropic's orchestrator-worker research system |
| [PARL](https://github.com/The-Swarm-Corporation/PARL) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/PARL?style=flat&label=) | Training models to split tasks across parallel agents |

### Templates and examples

| Repository | Stars | What it is |
|---|---|---|
| [swarms-examples](https://github.com/The-Swarm-Corporation/swarms-examples) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/swarms-examples?style=flat&label=) | A large collection of swarms examples |
| [Multi-Agent-RAG-Template](https://github.com/The-Swarm-Corporation/Multi-Agent-RAG-Template) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/Multi-Agent-RAG-Template?style=flat&label=) | A team of agents that processes and analyses documents |
| [Multi-Agent-Template-App](https://github.com/The-Swarm-Corporation/Multi-Agent-Template-App) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/Multi-Agent-Template-App?style=flat&label=) | A starting point for multi-agent applications |
| [Cookbook](https://github.com/The-Swarm-Corporation/Cookbook) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/Cookbook?style=flat&label=) | Notebooks and guides |
| [Awesome-Swarms-List](https://github.com/The-Swarm-Corporation/Awesome-Swarms-List) | ![](https://img.shields.io/github/stars/The-Swarm-Corporation/Awesome-Swarms-List?style=flat&label=) | Applications, tools and resources built on swarms |

## We're hiring

We're looking for agent engineers, AI researchers, API and infrastructure engineers, and front-end engineers who want to build collective super intelligence. See the [careers page](https://swarms.ai/hiring), or email [kye@swarms.world](mailto:kye@swarms.world) with a link to your GitHub.

## Contributing

Every repository welcomes contributions. The best place to start is [swarms](https://github.com/kyegomez/swarms): read the [contributing guide](https://github.com/kyegomez/swarms/blob/master/CONTRIBUTING.md) and pick an open [issue](https://github.com/kyegomez/swarms/issues).

## Contact

[kye@swarms.world](mailto:kye@swarms.world) · [swarms.ai](https://swarms.ai) · [Discord](https://discord.gg/EamjgSaEQf)
