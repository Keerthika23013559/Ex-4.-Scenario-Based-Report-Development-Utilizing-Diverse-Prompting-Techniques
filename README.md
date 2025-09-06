# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.
## Aim: 

To design and develop an AI-powered chatbot using diverse prompting techniques that can handle customer inquiries, provide support, and enhance customer experience in a retail environment.

## Algorithm: 

Step 1: Problem Definition

• Identify the retail environment scenario (e.g., an online clothing store).

• Define customer needs (product inquiries, order status, returns, complaints).

Step 2: Data Collection

• Gather frequently asked questions (FAQs), support scripts, and product data.

Step 3: Prompting Techniques Selection

• Choose diverse AI prompting methods (zero-shot, few-shot, chainof-thought, role prompting, persona-based, self-consistency).

Step 4: Prompt Design & Experimentation

• Construct different prompts for the same scenario using each technique.

• Collect chatbot outputs.

Step 5: Evaluation

• Compare outputs for correctness, coherence, personalization, and customer satisfaction.

Step 6: Report Generation

• Document the process, results, and analysis.


## Prompt:

“Develop a scenario-based report on designing and implementing an AIpowered chatbot for retail customer support.

Apply diverse prompting techniques (Zero-shot, Few-shot, Role-based, Chain-of-Thought, Personabased, Instruction-based, and Scenario-based)"

<img width="480" height="240" alt="image" src="https://github.com/user-attachments/assets/db6fa1f5-14bd-4366-b687-850496253f0d" />

## Output:

Prompts, Outputs, and Results

Zero-Shot Prompting Prompt: "You are a chatbot for a retail clothing store. A customer asks: 'Where is my order?' Respond politely."
Output: "Hello! Could you please provide your order ID so that I can check the status for you?"

Result: Zero-shot prompting works well for simple queries but may lack personalization.

Few-Shot Prompting Prompt: "Example 1: Customer: 'Do you have size M in blue shirt?' → Chatbot: 'Yes, size M in blue is available.'
Example 2: Customer: 'When will my delivery arrive?' → Chatbot: 'Your delivery will arrive in 2–3 business days.' Now, Customer: 'Can I return a product I bought last week?'"

Output: "Yes, you can return your product within 30 days of purchase. Would you like me to guide you through the return process?"

Result: Few-shot improves accuracy and aligns responses with company policy.

Chain-of-Thought Prompting
Prompt: "Step-by-step, think about how a chatbot should answer a customer asking: 'I want to buy shoes under $50.'"

Output: "First, check product database. Filter items under $50. Provide top options. Response: 'Sure! Here are some shoes under $50: Casual Sneakers ($45), Running Shoes ($48), and Sandals ($39). Would you like to see more?'"

Result: Chain-of-thought ensures structured, logical answers for complex queries.

Role Prompting
Prompt: "Act as a customer service representative of TrendyWear Store. A customer asks: 'How do I track my order?'"

Output: "Hello, thank you for shopping with TrendyWear. To track your order, please visit our website and enter your tracking ID on the 'Track My Order' page. Would you like me to send you the link?"

Result: Role prompting improves empathy, professionalism, and tone.

Persona-Based Prompting Prompt: "You are a friendly fashion advisor chatbot. A customer asks: 'What should I wear for a beach party?'"
Output: "For a beach party, I recommend light and airy clothes. A floral shirt with shorts or a sundress would be perfect. Don’t forget sunglasses and flipflops for comfort!

Result: Persona-based prompting improves engagement and adds personality.

6.Self-Consistency Prompting

Prompt: "Suggest the best product return policy explanation. Generate multiple responses and choose the most helpful one."

<img width="1600" height="1000" alt="image" src="https://github.com/user-attachments/assets/e2612821-80eb-4a07-9bb4-feab3484d936" />


Output:

"You can return products within 30 days with the receipt."

"We accept returns within 30 days of purchase for unused items. You can request a refund or exchange."

"Products can be returned within 30 days. Please keep the receipt and original packaging."

Final Response

"We accept returns within 30 days for unused items with the receipt and packaging. You can request a refund or exchange." Outputs of Chatbot using Diverse Prompting Techniques

Zero-Shot Prompting Output Customer Query: "Where is my order?" Chatbot Response: "Hello! Could you please provide your order ID so I can check the status for you? Once I have that, I can give you the exact delivery update."

Few-Shot Prompting Output Customer Query: "Can I return a product I bought last week?" Chatbot Response: "Yes, you can return your product within 30 days of purchase. Please make sure the item is unused and in its original packaging. Would you like me to share the return request link with you?"

Chain-of-Thought Prompting Output Customer Query: "I want to buy shoes under $50." Chatbot Response: "Sure! Let me check. Filtering shoes under $50... Here are a few options: Casual Sneakers – $45, Running Shoes – $48, Sandals – $39. Would you like me to show you more designs in this price range?"

Role Prompting Output Customer Query: "How do I track my order?" Chatbot Response: "Hello, thank you for shopping with TrendyWear! You can easily track your order by visiting our website and entering your tracking number on the 'Track Order' page. If you share your order ID, I can fetch the status for you right now."

Persona-Based Prompting Output Customer Query: "What should I wear for a beach party?" Chatbot Response: "For a beach party, I’d recommend something stylish yet comfortable! A floral shirt with shorts or a flowy sundress would be perfect. Don’t forget your sunglasses, flip-flops, and a light hat to stay cool and trendy!"

Self-Consistency Prompting Output Customer Query: "Can you explain the return policy?"

Generated Responses: "You can return products within 30 days with the receipt." "We accept returns within 30 days of purchase for unused items. You may request a refund or exchange." "Products can be returned within 30 days. Please keep the receipt and original packaging."

Final Optimized Response (Selected):

"Our return policy allows you to return unused items within 30 days of purchase, provided you have the receipt and original packaging. You may choose either a refund or an exchange. Would you like me to guide you to the return page?"

<img width="864" height="533" alt="image" src="https://github.com/user-attachments/assets/b5bb59bf-7fb1-4cd2-b861-c863c34e854f" />

## Result:

The analysis shows that Role-based prompting delivers the best customer experience through professionalism and empathy, while Instruction-based prompting is the most efficient for quick, simple support. Few-shot prompting provides richer, detailed answers but at the cost of efficiency, whereas Zero-shot and One-shot prompting are faster but less personalized.
