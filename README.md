# Agent Harness

- Agent = Model + Harness
- ‘하네스(Harness)’는 말을 통제하기 위해 장착하는 고삐, 안장, 줄 등 장비를 뜻한다.
- 하네스 엔지니어링은 AI 직원의 업무 효율을 높이기 위해 시스템을 구축하는 일이다. 참조: [사람 역할은 AI 능률 높이는 '하네스 엔지니어링'](https://www.chosun.com/economy/tech_it/2026/03/16/N6DM6IKF7NFHHCVB7OMSSDUWBU/)

### Harness의 구성

[The Anatomy of an Agent Harness](https://blog.langchain.com/the-anatomy-of-an-agent-harness/)에서 얘기하는 Harness의 구성은 아래와 같습니다.


- System Prompts
- Tools, Skills, MCPs + and their descriptions
- Bundled Infrastructure (filesystem, sandbox, browser)
- Orchestration Logic (subagent spawning, handoffs, model routing)
- Hooks/Middleware for deterministic execution (compaction, continuation, lint checks)


## Reference 

[The Anatomy of an Agent Harness](https://blog.langchain.com/the-anatomy-of-an-agent-harness/)

[사람 역할은 AI 능률 높이는 '하네스 엔지니어링'](https://www.chosun.com/economy/tech_it/2026/03/16/N6DM6IKF7NFHHCVB7OMSSDUWBU/)

[[LangChain] The Anatomy of an Agent Harness](https://www.notion.so/LangChain-The-Anatomy-of-an-Agent-Harness-32ee14767c3d816a9d86fa0db911c241)

[Agent Harness 완전 정리](https://www.notion.so/Agent-Harness-32ee14767c3d8180a9c0f3cd66ba6b4f)

[Building a Production-Ready AI Agent Harness](https://dev.to/apssouza22/building-a-production-ready-ai-agent-harness-2570)

[[Anthropic] Effective Harnesses for Long-Running Agents](https://www.notion.so/Anthropic-Effective-Harnesses-for-Long-Running-Agents-32ee14767c3d810ea5d7d1448045479c)
