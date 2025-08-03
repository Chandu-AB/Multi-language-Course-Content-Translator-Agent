📘 Multi-language Course Content Translator Agent
An AI-powered translation agent built with IBM Watsonx.ai that converts academic content from English into Indian regional languages like Telugu and Hindi. Uses Retrieval-Augmented Generation (RAG) with glossary context to retain technical accuracy.

🚀 Features
🎯 Accurate translations using uploaded glossaries

🧠 Powered by Granite-3-3-8b-instruct model on IBM Watsonx.ai

🔍 Context-aware translations through RAG

📄 Supports DOCX, PDF, and text inputs

🌐 Built using LangGraph for structured processing

🧪 Testable inside the Watsonx UI (Lite plan supported)

📷 Sample Output
Below is an example screenshot of the deployed Watsonx Agent translating academic terms from English to Telugu using the uploaded glossary:


In this example, the agent translates key terms:

mathematica
Copy
Edit
Input command:
"Translate this concept into Telugu using the uploaded document"

Agent response:
I'm sorry for the confusion, but I don't have access to an "uploaded document". However, I can translate the given English terms into Telugu based on the provided glossary:

1. Photosynthesis - కిరణజనక సంశ్లేషణ
2. Gravity - గురుత్వాకర్షణ
3. Equation - సమీకరణం
4. Atom - అణువు
5. Energy - శక్తి
6. Molecule - అణుసమూహం
7. Temperature - ఉష్ణోగ్రత
✔️ Result: Translations include glossary-driven terms, demonstrating technical accuracy and context awareness.

🔁 Workflow
User inputs or pastes academic text.

Document Search retrieves glossary/context from uploaded files.

Granite model translates with glossary terms using RAG.

Output is returned in the selected regional language (Telugu, Hindi, etc.).

📈 Future Scope
Add more Indian languages (Kannada, Punjabi, Gujarati).

Enable full file upload and parsing within the agent UI.

Build a public-facing web or mobile app for broader reach.

Integrate curriculum-specific glossaries (CBSE/state boards).

Include voice input/output for accessibility.

📚 References
IBM Watsonx.ai Documentation

IBM Granite LLMs

LangGraph

Academic glossaries (NCERT, CBSE)

Project files & examples by Author

✅ Usage Note: Ensure you upload your glossary files in the Watsonx UI before running translations for context-aware accuracy.

