# chatbot_uml



```mermaid
flowchart LR
     A(OPEN AI) <-- API --> B{chatbot} <-- text --> C{{USER input }}
     B <-- PROMPTS --> C
     C --auth--> D[(Database)]
     B -- auth --> D
    


```
