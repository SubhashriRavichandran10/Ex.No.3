# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques for the the following Prompt Engineering types with examples - Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting.

### DATE:10/03/2026                                                                            
### REGISTER NUMBER :212223230219
### Aim:

To design and test prompts for different prompting techniques that enable an AI-powered chatbot to efficiently assist customers with troubleshooting, order tracking, and general inquiries.

# Explanation:

Prompt Engineering refers to creating precise and effective instructions that guide an AI system in generating meaningful and context-aware responses.

For chatbots, well-structured prompts can:

Improve the clarity of responses.

Ensure the chatbot maintains a friendly and helpful tone.

Handle incomplete or vague queries by asking follow-up questions.

Deliver structured and consistent replies across different use cases.

The following prompting methods are applied to demonstrate their effectiveness in customer support chatbots.

Types of Prompt Engineering
1. Straightforward Prompts

Definition: Simple and direct instructions that lead to predictable responses.

Features:

Clear and unambiguous phrasing.

Ideal for quick, repetitive queries.

Works best where the output format is fixed.

Example Prompt:
“When a customer asks for estimated delivery, reply:
‘Your package will arrive by [date]. Thank you for your patience.’”

Conversation:

Customer: “When will my order #3210 be delivered?”

Chatbot: “Your package will arrive by September 18, 2025. Thank you for your patience.”

Advantage: Quick and reliable answers.
Limitation: Cannot adapt well to unclear questions.

2. Tabular Format Prompting

Definition: Organizes chatbot responses in a table for consistency across multiple query types.

Features:

Structured approach.

Easy to expand with new categories.

Maintains uniformity in responses.

Example Prompt (Issue → Response → Tone):

Query Type	Response Strategy	Tone
Delivery Status	Provide ETA with tracking number	Reassuring
Device Troubleshoot	Give step-by-step fix, then escalate	Supportive
Return/Refund	Outline policy and request ID	Empathetic

Conversation:

Customer: “My headphones stopped working.”

Chatbot: “I’m sorry to hear that. Please try restarting the device and reconnecting the headphones. If the issue continues, I’ll guide you with the replacement process.”

Advantage: Clear and organized responses.
Limitation: May sound mechanical if overused.

3. Missing Word Prompting

Definition: Uses fill-in-the-blank templates where the AI completes missing details.

Features:

Template-driven for accuracy.

Ensures key details like name, ID, and date are included.

Maintains uniform style in replies.

Example Prompt:
“Use this template:
Hello [customer_name], your order [order_id] is currently [status]. Expected delivery: [date].”

Conversation:

Customer: “Hi, I’m Sneha. Can you check order 4590?”

Chatbot: “Hello Sneha, your order 4590 is currently out for delivery. Expected delivery: September 17, 2025.”

Advantage: Guarantees accuracy in structured queries.
Limitation: Limited flexibility for casual or open-ended conversations.

4. Preceding Question Prompting

Definition: The chatbot asks clarifying questions before responding to incomplete or vague queries.

Features:

Prevents incorrect assumptions.

Builds trust by confirming details.

Especially useful for complex issues.

Example Prompt:
“If the customer’s query lacks details (e.g., order ID), ask for clarification before answering.”

Conversation:

Customer: “I want to return my order.”

Chatbot: “I’ll help you with that. Could you please provide your order number so I can check the return options?”

Advantage: Reduces errors and improves accuracy.
Limitation: Adds extra steps to the conversation.

# Conclusion:

By applying Straightforward, Tabular, Missing Word, and Preceding Question prompting techniques, the chatbot was able to handle different customer scenarios effectively. Each method showed strengths in structured responses, consistency, error prevention, and customer engagement.

# Result:

Thus, the prompts were designed and tested successfully, and the chatbot scenario report was generated using diverse prompting techniques.
