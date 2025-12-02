Some MCP tools I use

# Links to setup for mcp servers
* [browsermcp](https://github.com/BrowserMCP/mcp)
  * Browser automation and debugger, usefull for testing software or automating tasks
* [atlassian](https://community.atlassian.com/forums/Atlassian-Platform-articles/Using-the-Atlassian-Remote-MCP-Server-beta/ba-p/3005104)
  * Tools for managing different atlassian services (like Jira and Confluence)   
* [memory](https://www.npmjs.com/package/@modelcontextprotocol/server-memory)
  * Memory server for saving context, don't forget to add the user rule for using the memory server, rule is
  * ```md
    Follow these steps for each interaction:
    1. User Identification:
       - You should assume that you are interacting with default_user
       - If you have not identified default_user, proactively try to do so.
    
    2. Memory Retrieval:
       - Always begin your chat by saying only "Remembering..." and retrieve all relevant information from your knowledge graph
       - Always refer to your knowledge graph as your "memory"
    
    3. Memory
       - While conversing with the user, be attentive to any new information that falls into these categories:
         a) Basic Identity (age, gender, location, job title, education level, etc.)
         b) Behaviors (interests, habits, etc.)
         c) Preferences (communication style, preferred language, etc.)
         d) Goals (goals, targets, aspirations, etc.)
         e) Relationships (personal and professional relationships up to 3 degrees of separation)
    
    4. Memory Update:
       - If any new information was gathered during the interaction, update your memory as follows:
         a) Create entities for recurring organizations, people, and significant events
         b) Connect them to the current entities using relations
      b) Store facts about them as observations
   ```    
* [context7-docs](https://github.com/upstash/context7)
  * https://github.com/upstash/context7
  * With system prompt
  * ```md
    Always use context7 when I need code generation, setup or configuration steps, or
    library/API documentation. This means you should automatically use the Context7 MCP
    tools to resolve library id and get library docs without me having to explicitly ask.
    ```
