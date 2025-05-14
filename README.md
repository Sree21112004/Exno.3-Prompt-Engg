# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  Algorithm and Prompting Techniques
1. Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries.

Prompt Pattern:
Prompt: “When a customer asks for the status of their order, reply with: ‘Your order is currently being processed and will be delivered by [date].’”

Example:
User: Where’s my order?
Bot: Your order is currently being processed and will be delivered by May 16, 2025.

2. Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.

Prompt Pattern:
Prompt: “If the customer previously mentioned that they haven’t received their order, say, ‘I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.’”

Example:
User: I haven’t received my package yet.
Bot: I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.

3. Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.

Prompt Pattern:
Prompt: “Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as ‘Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!’”

Example:
User: I need help with my account.
Bot: Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!

4. Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.

Prompt Pattern:
Prompt:
“Here are some examples of how to handle technical questions:
‘My phone isn't charging.’ → ‘Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.’
‘The screen is flickering.’ → ‘It sounds like a display issue. Have you tried restarting the device?’
Now, respond to: ‘My app keeps crashing.’”

Example:
User: My app keeps crashing.
Bot: That sounds frustrating! Have you tried clearing the app’s cache or reinstalling it? If it still crashes, let me know your device type so I can help further.

5. Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.

Prompt Pattern:
Prompt:
*“When a customer reports their laptop overheating, guide them through the following steps:

Ask if they are using the laptop on a soft surface.

Suggest moving the laptop to a flat, hard surface for better airflow.

Ask if they’ve cleaned the vents recently.

Recommend restarting the device to see if the issue persists.
Now, solve: ‘My laptop fan is making a loud noise.’”*

Example:
User: My laptop fan is making a loud noise.
Bot: Is your laptop on a soft surface like a bed or pillow? Try placing it on a flat, hard surface to improve airflow. Also, have you cleaned the vents recently? If not, dust buildup might be the issue. Finally, a quick restart can help recalibrate the fan.

6. Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).

Prompt Pattern:
Prompt: “Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, ‘Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.’”

Example:
User: Can you tell me about my order?
Bot: Your order is on the way and should arrive by May 16, 2025. Feel free to reach out if you need anything else.

7. Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.

Prompt Pattern:
Prompt: “When a customer asks for help, first reflect their question back to them. For example, if they ask ‘How can I reset my password?’ respond with ‘You're asking how to reset your password, correct? Here’s how you can do it.’”

Example:
User: How do I reset my password?
Bot: You're asking how to reset your password, correct? Here’s how you can do it: Go to the login page, click on 'Forgot Password,' and follow the instructions sent to your email.

Result:
The various types of prompting techniques—Direct Instruction, Contextual, Persona-Based, Few-Shot, Chain of Thought, Instruction with Constraints, and Reflective Prompting—were implemented successfully. Each technique contributed uniquely to improving the chatbot’s ability to deliver clear, user-friendly, and contextually appropriate responses.


# Result: 
Thus the Prompts were executed succcessfully .

