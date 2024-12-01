# Found it : Building Generative AI Application using Gemma

## Short Description of the project 
Have you had a mini heart attack searching for your phone? It's a moment we all laugh about. But imagine if most of your memories and sense of self were fading away. Watching our aging parents struggle to find things, especially while living abroad, leaves me feeling helpless. I aim to create assistive technology that empowers our parents and grandparents to live more independently.

## Technical Overview

Aging parents and grandparents often struggle with memory lapses, making it challenging to locate everyday items like keys, glasses, or pens. For their children, especially those living abroad, these struggles can evoke feelings of helplessness. This project addresses this issue with an AI-powered assistive application that uses Gemma models to analyze video data and answer natural language queries like "Where did I last see my keys?".

The solution processes video frames from local cameras, generating embeddings stored in ChromaDB alongside metadata like timestamps and object detections. By converting queries into embeddings and performing similarity searches, the system retrieves frames showing the item’s last-known location.

Designed for elderly individuals and their caregivers, the application features a simple, accessible interface for seamless interaction. Initial offline processing ensures privacy, while cloud scalability allows real-time use. Unique benefits include empowering older adults to live independently, reducing caregiver stress, and enabling remote support for families, fostering peace of mind.

## Prerequisite
Run the notebook in colab and set up access to PaliGemma Model in kaggle.
