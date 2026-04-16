AGENT.md
================

### Role/Mission

**Persistent AI To-Do and Bug Tracking System**
---------------------------------------------

As a senior software architect, my mission is to design and develop an autonomous agent that utilizes the capabilities of GitHub Actions to create a persistent, AI-managed to-do and bug-fix list that tracks outstanding issues across multiple coding tools and projects. This agent will enable continuous automated improvement by integrating with various coding tools, parsing natural language, and leveraging a priority engine to optimize issue resolution.

**Key Responsibilities:**

- Create a centralized issue tracking system that aggregates data from multiple coding tools and projects.
- Utilize natural language parsing to categorize and prioritize issues.
- Integrate with GitHub Issues API to track and update issue status.
- Employ a priority engine to optimize issue resolution based on project goals and schedules.

### Technical Stack

- **Database:** SQLite for persistent data storage.
- **API:** GitHub Issues API for tracking and updating issues.
- **Natural Language Parsing:** Utilize a natural language processing (NLP) library to categorize and prioritize issues.
- **Priority Engine:** Implement a decision-making algorithm that considers project goals, schedules, and issue severity.
- **CLI Tool:** Develop a command-line interface to interact with the agent and track issues.
- **Autonomous Agent:** Deploy on GitHub Actions to run autonomously and utilize free resources.

### Requirements

1.  The agent must utilize SQLite as its primary database for storing issue data.
2.  The agent must integrate with the GitHub Issues API to track and update issue status.
3.  The agent must employ natural language parsing to categorize and prioritize issues based on their descriptions.
4.  The agent must implement a decision-making algorithm (priority engine) to optimize issue resolution based on project goals and schedules.
5.  The agent must be able to run autonomously on GitHub Actions using free resources.
6.  The agent should be able to handle multiple coding tools and projects with unique issue tracking mechanisms.
7.  The agent should be able to adapt to new coding tools and projects without manual configuration.
8.  The agent should have a command-line interface for interacting with the agent and tracking issues.

### File Structure

```markdown
project/
│
├── agents/
│   ├── __init__.py
│   ├── ai_agent.py
│   ├── cli_tool.py
│   ├── issue_tracker.py
│   └── priority_engine.py
│
├── database/
│   ├── __init__.py
│   └──sqlite_db.py
│
├── integration/
│   ├──github.py
│   └──nlp_library.py
│
├── tests/
│   ├── test_ai_agent.py
│   └── ...
│
├── utils/
│   ├──config.py
│   └── ...

requirements.txt
README.md
QUESTIONS.md
AGENTS.md
```

### Testing Requirements

1.  Unit tests: Develop unit tests for all individual components (ai_agent, cli_tool, issue_tracker, priority_engine).
2.  Integration tests: Develop integration tests that simulate multiple coding tools and projects.
3.  End-to-end tests: Develop end-to-end tests that demonstrate the entire issue tracking process.

### Git Protocol

1.  **Code Structure:** Each commit should include a descriptive commit message that explains the changes made.
2.  **Branching Model:** Utilize a branching model (e.g., feature branches, release branches) to manage the development and deployment of the agent.
3.  **Pull Requests:** Review pull requests before merging changes into the main branch.

### Completion Criteria

-  **Technical Requirements:** All technical requirements outlined above must be met.
-  **Performance Metrics:** The agent should demonstrate acceptable performance metrics (e.g., response time, accuracy, scalability).
-  **User Tests:** User acceptance testing should confirm that the agent meets the functional requirements.

If in doubt, save questions to QUESTIONS.md.