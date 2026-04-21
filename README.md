# AI Experiences

This repository contains a collection of AI experiences, showcasing various applications and implementations of artificial intelligence. Each experience is designed to demonstrate the capabilities and potential of AI in different domains.

In some ways this is a collection of learning expereiences for me, but I hope that others can also find value in exploring these projects and learning from the approaches taken.  The projects range from more technical implementations to more user-facing experiences, providing a broad overview of the possibilities in AI development.

I publish to github under dtehan (personal) and dtehan-td (Teradata) accounts, the dtehan-td account is where I publish projects that are more closely related to Teradata and its ecosystem, while the dtehan account is where I publish projects that are more general in nature.  Some projects may be published under both accounts if they are relevant to both audiences.

## Table of Contents
- [AI Experiences](#ai-experiences)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [License](#license)

## Learnings
Through the development of these experiences, I have gained valuable insights into the challenges and opportunities in AI development. Some key learnings include:
- The idea of custom experience developed by GenAI is compelling, but the development process is still complex and requires significant effort to create a polished experience.
- I can see a day when custom experiences is the norm.
- The need to anchor custom experiences with a trusted knowledge layer is critical for the experience to add value to the user community, it is easy to build AI experiences that look great but have little substance, by anchoring the experience with a trusted knowledge layer, we can ensure that the experience provides accurate and valuable information to users.
- The technology and techniques used in AI development are rapidly evolving, the LLM alone is not sufficient to create a compelling experience, but it is a critical component that can be leveraged in various ways to enhance the experience.
- Building a successful AI experience requires a combination of technical expertise, creativity, and a deep understanding of the subject matter.
- Many people are going to build custom experiences, but few will want to support custom expereiences.  We will need to find ways for customer experiences to be self sustaining.



## Getting Started
To get started with a specific AI experience, follow the instructions provided in the respective experience's README file. Each experience may have its own dependencies and setup requirements, so be sure to read the documentation carefully.  Most recent experiences will be at the top of the list.

### Enterprise Memory
This is an experiment in building an enterprise memory system, it is designed to be a central repository for agents to store and retrieve information.  The goal of this project is to create a system that can be used to manage the knowledge and information that agents need to perform their tasks effectively.
- [enterprise-memory](https://github.com/dtehan/Enterprise-Memory)
- This is an exploration into what an enterprise memory system would need to look like to support a large number of agents in an enterprise setting.  It is still in early stages of development, but it serves as a starting point for building a more advanced enterprise memory system in the future.
- Currently under a more restrictive license.

### second-brain 
This is my second brain code.  It is a MCP server that manages a knowledge graph and provides an interface for querying and updating the knowledge graph.  The goal of this project is to create a personal knowledge management system that can be used to store and retrieve information in a structured way.
- [brain](https://github.com/dtehan/second-brain)
- This was built in April 2026, it superscedes my first brain project that was built ealier in the year based on a vector database approach.  This version moved to a database and wiki approach.
- I have since moved to the obisidian approach.

### leadership-team
This is a smaller team that levereages pi agent teams.  We are using a structure that is less command and control in this approach.
- [leadership-team](https://github.com/dtehan/leadership-team)
- This experience was developed in April 2026, it is an experiment in using pi agent.

### leadership-agent
This is an experiement of a team of agents working under a command and control process, the CEO leads the discussion around a questions and generates a memo.  Each team member contributes to the discussion and the CEO synthesizes the information into a final memo.  Team members all have memory of past decisions and of their collegues.  Team members can be made more real by adding profile information about them, such as their background, their personality, their preferences, etc.
- [leadership-agent](https://github.com/dtehan/leadership-agent)
- this experiment was developed in April 2026.

### dba
This is a Teradata DBA GUI agent that can perform various database administration tasks.
- [dba](https://github.com/dtehan/dba)
- This experience was build in 2026, it aims to balance a portal with a chat interface, allowing users to interact through the [Teradata MCP Community Edition](https://github.com/Teradata/teradata-mcp-server) we have packaged the work from [tdsql-mcp](https://github.com/ksturgeon-td/tdsql-mcp) into the experience to ensure that usable Teradata SQL is available to users.  We have also include a number of agents to help a DBA with common tasks.  These agents are intitial drafts and would require further developement to be production ready, but they serve as a starting point for building more advanced DBA agents in the future.

### MVC Agent
This is leveraging a simplier meta agent for the purpose of building a Multi Value Compression expert agent.  This was built to show how expert agents in conjunction with Subject Mater Experts could build agents.
- [MVC Agent](https://github.com/dtehan/mvc-agent)
- This experience was built in 2025-2026.  It is technical in nature.

### lineage
This is one of the first large scale software projects built using the [gsd](https://github.com/gsd-build/get-shit-done) framework.  The tool parses Teradata DBQL to build a lineage data repository and provides a GUI experience for looking at the lineage data.
- [lineage](https://github.com/dtehan/lineage)
- This experience was build in 2025-2026, while the GUI is most complete, the DBQL parsers require significant amount of work to cover all the SQL use cases.

### learning
This is a learning MCP server that provides micro educational content on demand, when the topic does not exist it will attempt to create it by building the assets.  The intent is that this would then interface with tools that would take the learning guidline and build the content, such as a video or a document.
- [learning](https://github.com/dtehan/learningMCP)
- This experience was build in 2025, it is an early prototype looking at how a MCP server could become a middleware for learning content, it is not production ready but serves as a starting point for exploring this concept further.

### Agent Builder
This is a meta agent for building agents with Teradata capabilities.
- [Agent Builder](https://github.com/dtehan/AgentBuilder)
- This experience was build in 2025, many of the approaches and techniques used may be outdated by the time you read this. However, it serves as a historical reference for the state of AI development at that time.

### Teradata MCP Server
This is the project that kicked it off, it is a MCP server that provides an interface for building agents with Teradata capabilities.  It is designed to be a flexible and extensible platform for building a wide range of AI experiences.  
- [Teradata MCP Community Edition](https://github.com/Teradata/teradata-mcp-server)
- We started to build this project in 2025, and the project is still under active development.  It serves as the foundation for many of the other experiences in this repository, and we will continue to build on it to support more advanced capabilities and use cases in the future.

## License
These projects are licensed under the MIT License, unless otherwise noted - see the [LICENSE](./LICENSE.md) file for details.
