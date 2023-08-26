# chatbot_uml






```mermaid
flowchart TB
     subgraph one
     A(OPEN AI) <-- API --> B{chatbot} <-- text --> C{{USER input }}
     B <-- PROMPTS --> C
     C --auth--> D[(Database)]
     B -- auth --> D
     end
     subgraph two
     A1(user) <-- login --> D[(Database)] <-- auth --> C1{{ auth:TRUE }}
     A1  <-- AUTH --> C1
     end
  
    


```
