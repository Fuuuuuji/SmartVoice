# SmartVoice
SmartVoice is an innovative community participation platform that redefines the interaction model of community governance and resident engagement through a human-AI collaborative paradigm and AI agent technologies. Originating from the research practice of the Tongji University team in Yangpu District, Shanghai, the project aims to address the core contradictions of "insufficient depth" and "limited coverage" in traditional community participation.

## Research Frame
![image](https://github.com/user-attachments/assets/93518841-1fc5-4925-8c21-4fe77d7ea9da)

## Information Theory
![image](https://github.com/user-attachments/assets/fbe1c093-d201-438e-94b0-fc89319d4acd)

## Paradigm Shift
![image](https://github.com/user-attachments/assets/e98f51e5-1888-4f7d-ac0c-8f7a4e1ce8a9)
Traditional community participation suffers from two major paradigm limitations:
![image](https://github.com/user-attachments/assets/1c027d62-2b84-4e54-9084-25d373135edd)
Human-Centered Paradigm: High participation depth but limited coverage ("deep but narrow")

![image](https://github.com/user-attachments/assets/46abc46b-537d-44c8-a2e0-7e465f556888)
Technology-Driven Paradigm: Wide coverage but insufficient participation depth ("broad but shallow")

![image](https://github.com/user-attachments/assets/4b5a6eb5-b0a9-42cb-a503-fd8352a636eb)
SmartVoice constructs a new human-AI collaborative framework by integrating the advantages of both, achieving:
Enhanced participation efficiency and data processing capabilities through AI agents

## System Structure
![image](https://github.com/user-attachments/assets/efe95c47-b63c-4caf-a76f-2cd5f71029d8)
### 📸 Snap & Design (Image-Driven Design)
Capture community real scenes → Upload to the platform → AI generates intelligent design solutions
Supports architectural style transformation, public space optimization, and facility layout suggestions
Automatically extracts design semantics and generates structured requirement tags
### 💬 Chat & Explore (Dialogue-Driven Exploration)
Express community needs through natural language dialogue
AI real-time analysis of needs and association with policy & case knowledge bases
Supports multi-turn dialogue for in-depth mining of latent needs and generates demand analysis reports



## Experiment
### Highlight
In the practice of Pingliang Road Subdistrict, Yangpu, Shanghai:

Participation Efficiency: Demand collection cycle shortened from 2 months to 1 week

Data Scale: 571 valid design solutions collected within 7 days, with an average of 25 suggestions per person

User Experience: System usability score reached 48.76/50 (A+ level), and 91% of users expressed willingness to continue using

Design Insights: Core need dimensions such as "greening enhancement", "art intervention", and "facility optimization" extracted through AI analysis

### Timeline
![image](https://github.com/user-attachments/assets/cbab25b1-9752-4fd6-80da-aa1f570d35f4)

### Results
#### Pre&Post Test
![image](https://github.com/user-attachments/assets/87a72439-1f3f-4ea9-845e-f0951226ff40)
#### System Usiability Scale
![image](https://github.com/user-attachments/assets/ba8ca70b-120e-4325-94c7-a37341859d55)
#### AI-img
The attacks by local residents produced over 1,000 design results, covering three levels: Street, Community, and Resident, demonstrating rich creativity and imagination.

1. Street Level
   ![image](https://github.com/user-attachments/assets/41c3a0b6-3d67-4cc0-9f4c-03d81c535539)

2. Community Level
   ![image](https://github.com/user-attachments/assets/29ad5edd-38cf-412a-8038-934f20bcb0b2)

3. Resident Level
   ![image](https://github.com/user-attachments/assets/71a438a7-a1af-4d95-b4d3-674fe3ddd2cd)
### Analysis
#### GIS & Network Analysis
![image](https://github.com/user-attachments/assets/262de80d-b14b-491f-a127-67d8ea9f9e4f)

#### Paradigm Analysis
![image](https://github.com/user-attachments/assets/977503d8-1828-4e58-99a7-aa4c6a76f69b)
![image](https://github.com/user-attachments/assets/b7d9d96f-954e-4cce-84a3-7a18f79ac789)
![image](https://github.com/user-attachments/assets/ca1cba9a-9d34-4c0f-a110-bafab02b8626)

```
SmartVoice/
├── smartvoice-frontend/              # WeChat Mini Program frontend
│   ├── pages/                        # Page components
│   │   ├── snap-design/              # Shooting design page
│   │   ├── chat-explore/             # Dialogue exploration page
│   │   └── data-review/              # Data details page
│   ├── services/                     # Service layer
│   └── utils/                        # Utility functions
├── smartvoice-backend/               # Backend services
│   ├── models/                       # Data models
│   ├── agents/                       # AI agent modules
│   │   ├── llm/                      # Large language model interface
│   │   ├── rag/                      # Retrieval-augmented generation
│   │   └── cot/                      # Chain of thought reasoning
│   ├── api/                          # API interfaces
│   └── database/                     # Database operations
├── docs/                             # Documentation
│   ├── papers/                       # Research papers
│   ├── case-studies/                 # Case studies
│   └── design-docs/                  # Design documents
├── datasets/                         # Datasets
│   ├── fine-tuning/                  # Model fine-tuning data
│   └── practice-data/                # Community practice data
└── scripts/                          # Auxiliary scripts
```
