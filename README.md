# AI Experiences

This repository contains a collection of AI experiences, showcasing various applications and implementations of artificial intelligence. Each experience is designed to demonstrate the capabilities and potential of AI in different domains.

In some ways this is a collection of learning expereiences for me, but I hope that others can also find value in exploring these projects and learning from the approaches taken.  The projects range from more technical implementations to more user-facing experiences, providing a broad overview of the possibilities in AI development.

## Table of Contents
- [AI Experiences](#ai-experiences)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [License](#license)

## Learnings
Through the development of these experiences, we have gained valuable insights into the challenges and opportunities in AI development. Some key learnings include:
- The idea of custom experience developed by GenAI is compelling, but the development process is still complex and requires significant effort to create a polished experience.
- We can see a day when custom experiences is the norm.
- The need to anchor custom experiences with a trusted knowledge layer is critical for the experience to add value to the user community, it is easy to build AI experiences that look great but have little substance, by anchoring the experience with a trusted knowledge layer, we can ensure that the experience provides accurate and valuable information to users.
- The technology and techniques used in AI development are rapidly evolving, the LLM alone is not sufficient to create a compelling experience, but it is a critical component that can be leveraged in various ways to enhance the experience.
- Building a successful AI experience requires a combination of technical expertise, creativity, and a deep understanding of the subject matter.
- Many people are going to build custom experiences, but few will want to support custom expereiences.  We will need to find ways for customer experiences to be self sustaining.



## Getting Started
To get started with a specific AI experience, follow the instructions provided in the respective experience's README file. Each experience may have its own dependencies and setup requirements, so be sure to read the documentation carefully.

### Agent Builder
This is a meta agent for building agents with Teradata capabilities.
- [Agent Builder](https://github.com/dtehan/AgentBuilder)
- This experience was build in 2025, many of the approaches and techniques used may be outdated by the time you read this. However, it serves as a historical reference for the state of AI development at that time.

### dba
This is a Teradata DBA GUI agent that can perform various database administration tasks.
- [dba](https://github.com/dtehan/dba)
- This experience was build in 2026, it aims to balance a portal with a chat interface, allowing users to interact through the [Teradata MCP Community Edition](https://github.com/Teradata/teradata-mcp-server) we have packaged the work from [tdsql-mcp](https://github.com/ksturgeon-td/tdsql-mcp) into the experience to ensure that usable Teradata SQL is available to users.  We have also include a number of agents to help a DBA with common tasks.  These agents are intitial drafts and would require further developement to be production ready, but they serve as a starting point for building more advanced DBA agents in the future.

### learning
This is a learning MCP server that provides micro educational content on demand, when the topic does not exist it will attempt to create it by building the assets.  The intent is that this would then interface with tools that would take the learning guidline and build the content, such as a video or a document.
- [learning](https://github.com/dtehan/learningMCP)
- This experience was build in 2025, it is an early prototype looking at how a MCP server could become a middleware for learning content, it is not production ready but serves as a starting point for exploring this concept further.

### lineage
This is one of the first large scale software projects built using the [gsd](https://github.com/gsd-build/get-shit-done) framework.  The tool parses Teradata DBQL to build a lineage data repository and provides a GUI experience for looking at the lineage data.
- [lineage](https://github.com/dtehan/lineage)
- This experience was build in 2025-2026, while the GUI is most complete, the DBQL parsers require significant amount of work to cover all the SQL use cases.

### MVC Agent
This is leveraging a simplier meta agent for the purpose of building a Multi Value Compression expert agent.  This was built to show how expert agents in conjunction with Subject Mater Experts could build agents.
- [MVC Agent](https://github.com/dtehan/mvc-agent)
- This experience was built in 2025-2026.  It is technical in nature.

### leadership-agent
This is an experiement of a team of agents working under a command and control process, the CEO leads the discussion around a questions and generates a memo.  Each team member contributes to the discussion and the CEO synthesizes the information into a final memo.  Team members all have memory of past decisions and of their collegues.  Team members can be made more real by adding profile information about them, such as their background, their personality, their preferences, etc.
- [leadership-agent](https://github.com/dtehan/leadership-agent)
- this experiment was developed in April 2026.
 


## License
These projects are licensed under the MIT License - see the [LICENSE](./LICENSE.md) file for details.
