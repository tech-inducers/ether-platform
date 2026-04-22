# Ether-Platform :Agentic Development Platform


----------------------------------------------------------------------------

![](https://raw.githubusercontent.com/tech-inducers/ether/main/images/ether_architecture.jpg)
![](https://raw.githubusercontent.com/tech-inducers/ether/main/images/ether_screen.png)


-----------------------------------------------------------------------------


## Features
* Distributed in design - can generate, validate and run agents on remote/local/cloud environment 
* Components: 
           *Control Plane - execute and monitor agents
           *Design Plane  - generate agent ,agent with integration protocol support defined in the flow
            *Agents       - Python agent generated with protocol support /mqtt/Kafka/local environment with configuration including task provided to LLM.
                                                                                   
## Prerequisite
install nodered
https://github.com/node-red/node-red
node red custom node deployment
https://nodered.org/docs/creating-nodes/first-node

install Ollama or use any public LLM with .env files for api key.
https://ollama.com/ 

----------------------------------------------------------------------------

![](https://raw.githubusercontent.com/tech-inducers/ether/main/images/local_exec.png)

-----------------------------------------------------------------------------


Download Flow.json including generate, validate and run configuration 

https://github.com/tech-inducers/ether/tree/main/idea/marketplace/local_env



