# Langflow-Chef
A highly opinionated, Gordon Ramsay-inspired AI kitchen assistant built with Langflow and Google Gemini 2.5 Flash. This agent doesn't just find recipes—it judges your culinary "disasters" through image recognition, maintains a memory of your kitchen failures, and provides structured shopping lists (while insulting you the entire time).

🚀 Key Features
Persona-Driven Logic: Custom Prompt Engineering that maintains a consistent, witty, and grumpy British Chef personality.

Multi-Modal "Eyes": Uses Gemini 2.5 Flash to analyze uploaded images of food for "soggy bottoms" or "incinerated bread."

Real-Time Recipe Search: Integrated with the Tavily AI Search Tool to fetch authentic recipes from the web.

Persistent Memory: A built-in chat memory component so the Chef can reference your previous mistakes in future conversations.

Structured Data Extraction: Automatically transforms the Chef's rambling insults into a clean, Markdown-formatted shopping list.

🛠️ Tech Stack
Orchestration: Langflow (Low-code AI builder)

Model: Google Gemini 2.5 Flash

Search Engine: Tavily AI (Agentic Search)

Data Handling: Structured Output & Parser nodes for ingredient extraction.

📸 How it Works
Input: The user asks a question or uploads a photo of their meal.

Process: The Agent uses Gemini to "see" the image or Tavily to "research" a recipe.

Output: The Chef delivers a scathing review and a structured ingredient table.

"Dave, you absolute menace. I'm looking at this thing you've produced... the pastry isn't a soggy disaster. I'm almost disappointed." — The Chef

📂 Repository Structure
chef_flow.json: The exported Langflow blueprint (import this into your Langflow instance).

outputs/: Example shopping lists and chat logs.

assets/: Screenshots of the flow diagram.



🥘 A grumpy British Chef AI that judges your cooking via image recognition and finds recipes using Tavily + Gemini 2.5 Flash. Built on Langflow.
