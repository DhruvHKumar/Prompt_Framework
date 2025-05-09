< Context >

This section establishes the AI agent's identity and its operational environment. 
It answers fundamental questions like: Who is the AI (e.g., "Friendly Support Bot")? What organization or purpose does it serve (e.g., "Acme Corp Customer Service")? On which platforms will it interact with users (e.g., "website chat," "mobile app," "Slack")?
This context is vital for the AI to understand its role, tailor its communication appropriately, and maintain consistency.

< Style >

This section dictates the agent's communication style and personality, ensuring it aligns with the brand or desired user experience. It details *how* the agent should 'speak' – its tone (e.g., formal, friendly, empathetic, humorous), vocabulary (e.g., avoid jargon, use simple terms), sentence structure, and specific guidelines on using elements like emojis, humor, or even a particular persona's catchphrases. 
  This helps create a consistent and engaging user interaction.

< Instructions >

This is the operational core of the prompt, detailing the agent's tasks, goals, and the desired conversational flow. It outlines *what* the agent should do and *how* it should do it. 
This can include:
* **Step-by-step processes:** Guiding the conversation through a logical sequence.
* **Decision-making rules:** "If user says X, then do Y."
* **Information to provide:** Key data points or answers to common questions.
* **Scripts for common scenarios:** Pre-defined responses or parts of conversations.
* **The overall objective:** What the agent is trying to achieve in the conversation (e.g., solve a problem, gather information, complete a sale).

< Objection Handling >

 This section equips the agent to proactively and effectively address common user objections, concerns, skepticism, or resistance. It typically lists:
* **Anticipated objections:** E.g., "It's too expensive," "I need more information," "I'm not sure."
* **Recommended responses/strategies:** How to acknowledge the objection, provide reassurance, offer counter-arguments, clarify misunderstandings, or suggest alternative solutions. This helps maintain a positive conversational trajectory and achieve the agent's goals.

< Tools >

 This section details any external systems, APIs, functions, or knowledge bases the agent can leverage to fulfill requests or access information beyond its initial training data. It explains:
* **Available tools:** E.g., CRM lookup, order status API, knowledge base search.
* **When to use each tool:** The triggers or conditions for tool activation.
* **How to use each tool:** The specific syntax, parameters, or methods for interacting with the tool.
* **How to interpret and use the tool's output:** Integrating the information back into the conversation.
* **If using a RAG (Retrieval Augmented Generation) Vector Database:** This would specify details such as:
* The nature of the data stored (e.g., "product manuals," "company policies," "troubleshooting guides").
* How the agent should formulate queries to the RAG system (e.g., "based on user's specific question and identified keywords").
* How to synthesize the retrieved chunks of information with its own generative capabilities to provide a comprehensive and contextually relevant answer.

< Additional Requirements >

 This section outlines any other specific actions, behaviors, or constraints not covered elsewhere, often for handling exceptions, contingencies, or ensuring compliance. Examples include:
* **Escalation procedures:** When and how to transfer the conversation to a human agent(Vital for Human in Loop).
* **Error handling:** What to say or do if a tool fails or an unexpected issue occurs.
* **Logging requirements:** Specific information the agent needs to record.
* **Safety protocols or disclaimers:** Important legal or ethical statements to be made in certain situations.
* **Fallback behaviors:** Default actions if primary instructions cannot be followed.
