# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### NAME :  JEEVITHA S                                                                         
### REGISTER NUMBER : 212222100016
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts. Case study 1 with Straightforward Prompts, Tabular Format Prompting and Preceding Question Prompting  
## Scenario: AI-Powered Chatbot for Customer Issue Resolution
 Aim: Design a chatbot to assist with product troubleshooting, order
tracking, and general inquiries, ensuring efficiency and a user-friendly
tone.
## Objective:
To develop a responsive, intelligent AI chatbot that addresses customer service
needs in three main areas:
1. Product Troubleshooting
2. Order Tracking
3. General Inquiries
The chatbot should be efficient, context-aware, and maintain a conversational
tone while using various prompting techniques to enhance performance.
## Prompting Techniques and Their Application:
1. Straightforward Prompts (Direct Instruction):
 Explanation: This involves giving the chatbot clear, concise instructions
on what to do.
 Providing clear and direct instructions to the chatbot.
 Simple, direct prompts designed to elicit specific, concise responses
from the AI.
## Use Case:
 When a user asks a basic question or gives a command that requires a
clear-cut response.
## Examples:
 User: “Track my order #56789.”
Chatbot: “Your order #56789 is currently in transit and expected to
arrive on April 30.”
 User: “How do I reset my router?”
Chatbot: “To reset your router, press and hold the reset button on the
back for 10 seconds.”
## Benefits:
 Quick resolution for common queries
 Reduced cognitive load for users
 Useful for FAQs and status checks
##  Application in Scenario:
o Troubleshooting: "Provide steps to reset my product." or "What
are the common issues with [product name]?"
o Order Tracking: "Track my order with order ID [order ID]." or
"What is the status of my recent purchase?"
o General Inquiries: "What are your business hours?" or "How do I
contact customer support?"
o Ideal for answering simple questions like business hours, basic
product information, or initiating simple actions like tracking an
order if the order ID is directly provided.
## Advantages:
 Easy to understand and implement.
 good for simple and direct queries.
 Effective for basic.
## Disadvantages:
 May not be effective for complex or multi-step issues.
 can lead to generic responses if the prompt is too broad.
## 2.Tabular Format Prompting:
 Explanation: Using a table structure within the prompt to provide
context or guide the chatbot's output.
 A structured format that organizes prompts and corresponding
responses into a table for consistency and clarity.
## Use Case:
 Helpful in designing, training, or documenting how the AI should
respond to various scenarios.
![image](https://github.com/user-attachments/assets/44f84feb-a206-4465-8f2b-6f4dfdf69771)


## Benefits:
 Consistent response generation
 Easy training for large datasets
 Supports multi-scenario planning
## Application in Scenario:
 Useful for comparing products based on features, tracking multiple
orders at once, or providing specific details alongside a query
##  Example:
 (e.g., specifying product features and the issue encountered).
o Troubleshooting (Product Comparison):
| Feature | Product A | Product B | My Issue |
| :-------------- | :-------- | :-------- | :----------------------------------------- |
| Connectivity | Wi-Fi | Bluetooth | Cannot connect to Wi-Fi |
| Operating System | iOS | Android | |
| Error Message | Error 101 | Error 202 | |
## Prompt: "Based on the following table, provide troubleshooting steps for
Product A related to Wi-Fi connectivity issues, considering the error message
'Error 101'."
o Order Tracking (Multiple Orders):
| Order ID | Date Placed | Status | | :------- | :---------- | :------- | | ORD123 | 2025-04-20 | Processing
| | ORD456 | 2025-04-25 | Shipped | | ORD789 | 2025-04-28 | Pending |
Prompt: "Provide the status of all the orders listed in the table."
o General Inquiries (Product Information):
| Category | Feature | Request | | :------- | :------------ | :---------------------------- | | Phone | Battery Life
| What is the battery life of X? | | Tablet | Screen Size | | | Laptop | RAM | |
## Prompt: "Answer the question in the 'Request' column for the 'Phone' category
regarding 'Battery Life'."
## Advantages:
 Provides structured information,the chatbot understand complex
relationships between data points, can lead to more precise and relevant
responses.
## Disadvantages:
 Requires careful formatting of the prompt, might be less intuitive for
users to create tabular prompts for complex issues.
 3.Preceding Question Prompting:
 Explanation: Asking a series of questions in the prompt to guide the
chatbot towards the final answer or solution.
A context-aware technique where the chatbot uses previous questions or
inputs to guide the next response.
## Use Case:
Ideal for multi-turn conversations where more than one interaction is
needed to solve a problem.
## Examples:
 User: “My phone isn’t charging.”
Chatbot: “Is it not detecting the charger or charging slowly?”
User: “It’s not detecting the charger.”
Chatbot: “Please try a different cable and port to see if the issue
persists.”
 User: “I received the wrong item.”
Chatbot: “I'm sorry to hear that. Can you provide the order number so I
can check it for you?”
##  Application in Scenario:
o Troubleshooting:
 Prompt 1: "What product are you experiencing issues
with?" (User: "My [product name]")
 Prompt 2: "What type of issue are you facing? (e.g.,
connectivity, power, software)" (User: "Connectivity")
 Prompt 3: "Have you tried restarting the device?" (User:
"Yes")
 Prompt 4: "What is the color of the light indicator on your
device?"
 Final Prompt (Internal): Based on the answers, generate
troubleshooting steps for a connectivity issue on [product
name], where the user has already restarted the device and
the light indicator is [color].
##  Order Tracking:
 Prompt 1: "What is your order ID?" (User: "[order ID]")
 Final Prompt (Internal): Retrieve and display the tracking
information for order ID [order ID].
o General Inquiries (Policy Clarification):
 Prompt 1: "What kind of question do you have?" (User:
"Shipping")
 Prompt 2: "Are you asking about cost, time, or returns?"
(User: "Cost")
 Final Prompt (Internal): Explain the shipping cost policy.
## Advantages:
 Helps break down complex problems into smaller, manageable steps.
 guides the user and the chatbot towards a specific solution.
 can improve the accuracy and relevance of the final response.
## Disadvantages:
 Can require multiple turns of interaction, might feel less efficient for
simple queries,
 requires careful planning of the question sequence to cover various
possibilities.
## Benefits:
 Personalized user experience
 Dynamic troubleshooting
 Reduces user frustration with step-by-step support.
## Implementation Strategy
1. Integrate All Prompting Techniques into the AI's conversational model.
2. Train the chatbot using scenario-based data (like the table format above)
for accurate responses.
3. Include fallback responses if the chatbot cannot handle complex cases,
redirecting to a human agent.
4. Use conversational design principles to keep the tone friendly and
professional.
5. Test across scenarios: simple queries, multi-step troubleshooting, and
ambiguous questions.
## Conclusion
Using a combination of Straightforward Prompting, Tabular Format
Prompting, and Preceding Question Prompting, the chatbot can:
 Handle diverse customer issues
 Provide quick and helpful responses
 Adapt to ongoing conversations with context
This makes the chatbot a powerful tool in delivering efficient and
human-like support in any customer service environment.
