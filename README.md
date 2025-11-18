# Ex-4.-Scenario-Based-Report-Development-Utilizing-Diverse-Prompting-Techniques
Objective: The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation.

## Aim:

To evaluate different prompting strategies and identify which produces the most accurate, helpful, empathetic, and human-like chatbot responses for retail applications.

## Algorithm:

## Step 1: Identify Use Cases
Select common retail customer support scenarios:

Product Inquiry

Order Tracking

Return/Refund Policy

Troubleshooting

## Step 2: Define Prompting Techniques
Choose multiple prompting strategies to test:

Zero-shot prompting

One-shot prompting

Few-shot prompting

Role-based prompting

Persona-driven prompting

Instruction-based prompting

Chain-of-thought prompting

Socratic prompting

## Step 3: Design Prompts
Frame specific customer queries for each scenario.

Apply every prompting technique to the same query to compare outputs.

## Step 4: Execute Prompts
Use AI models (e.g., ChatGPT, Claude, Bard, Cohere Command, Meta AI) to generate responses for each prompt.

## Step 5: Collect Outputs
Document the chatbot responses produced by different prompting styles.

## Step 6: Analyze Responses
Evaluate responses based on:

Clarity (easy to understand)

Accuracy (correctness of information)

Empathy (human-like tone)

Personalization (customer-focused interaction)

Effectiveness (problem-solving ability)

## Step 7: Compare Techniques
Highlight strengths and weaknesses of each prompting method in various retail situations.

## Step 8: Conclude
Identify the most effective combination of prompting strategies (e.g., few-shot for accuracy, role-based for empathy, chain-of-thought for troubleshooting).

Recommend a hybrid approach for building a customer-centric retail chatbot.

## PROMPT,OUTPUT & RESULT:

## SCENARIO 1: PRODUCT AVAILABILITY

Customer Query: Do you have Nike running shoes in size 9

## Zero-Shot Prompting

a) Prompt: Provide a clear and helpful answer to the customer’s product availability question.

Output: Nike running shoes are available in multiple sizes. To confirm size 9 availability, please share your location or check our online store.

Result: Accurate but generic. No personalization.

b) Prompt-1: Answer the following product query. Do you have Puma backpacks in black
Output: Black Puma backpacks may be available depending on current stock. Please check our website for updated information.

c) Prompt-2: Respond to this question. Is size 7 ladies footwear available
Output: Availability for size 7 may vary. Please check our store inventory online.

## One-Shot Prompting

Prompt:
Example:
Q: Do you have iPhone 14
A: Yes, it is available. Would you like delivery or pickup
Now answer: Do you have Nike running shoes in size 9

Output: Yes, Nike running shoes in size 9 are available. Would you prefer store pickup or home delivery

Result: Friendly and clear but assumes availability.

a) Prompt-1:
Example:
Q: Do you sell HP laptops
A: Yes, we do. Would you like to explore available models
Now answer: Do you have Adidas socks in size L
Output: Yes, Adidas socks in size L are available. Would you like to add them to your cart

b) Prompt-2:
Example:
Q: Do you have Sony headphones
A: Yes, currently in stock
Now answer: Do you have Nike caps
Output: Yes, Nike caps are available. Would you like to view available colors

## Few-Shot Prompting

a) Prompt:
Q: Do you have Samsung Galaxy S23
A: Yes, it is available. Need help ordering
Q: Do you have Levi’s jeans in size 32
A: Yes, size 32 is in stock. Would you like pickup or delivery
Q: Do you have Nike running shoes in size 9

Output: Yes, Nike running shoes in size 9 are available. Would you like to see available colors

Result: Natural and sales-oriented.

b) Prompt-1:
Q: Do you have Titan watches
A: Yes, available in multiple designs
Q: Do you have Lenovo tablets
A: Yes, in stock
Q: Do you have Apple AirPods
Output: Yes, Apple AirPods are available. Need help placing an order

c) Prompt-2:
Q: Do you have cotton shirts in size M
A: Yes, available in various patterns
Q: Do you have leather belts
A: Yes, we have several variants
Q: Do you have formal shoes in size 10
Output: Yes, formal shoes in size 10 are available. Would you prefer black or brown

## Role-Based Prompting

a) Prompt: You are a polite retail associate. Respond to this query: Do you have Nike running shoes in size 9

Output: Yes. We have Nike running shoes available in size 9. Would you like to explore available colors and models

Result: Personalized and friendly.

b) Prompt-1: You are a supportive store assistant. Answer: Do you have Dell laptop chargers
Output: Yes, we have Dell laptop chargers. Would you like the fast-charging version

c) Prompt-2: You are a friendly store associate. Answer: Do you have women’s Kurtis in size XL
Output: Yes, we have women’s Kurtis in size XL. Would you like to see the latest designs

## SCENARIO 2: ORDER TRACKING

Customer Query: Where is my order 12345

## Zero-Shot Prompting

a) Prompt: Provide an update about the customer’s order status.

Output: Your order 12345 is being processed and will be shipped soon.

Result: Informative but lacking detail.

b) Prompt-1: Provide an update. Where is my order 7890
Output: Your order 7890 is in transit and will reach you soon.

c) Prompt-2: Respond to this inquiry. Track order 4567
Output: Order 4567 is processed and will be dispatched shortly.

## Few-Shot Prompting

a) Prompt:
Q: Where is my order 98765
A: It has been shipped and will arrive in two days
Q: Where is my order 12345

Output: Your order 12345 has been dispatched and will be delivered tomorrow evening.

Result: Clear and accurate timeline.

b) Prompt-1:
Q: Where is my order 555
A: It is out for delivery today
Q: Where is my order 777
Output: Order 777 is in transit and will arrive by Thursday.

c) Prompt-2:
Q: Track my order 2020
A: It is being packed
Q: Track my order 4040
Output: Order 4040 has been packed and will be shipped later today.

## Role-Based Prompting

a) Prompt: You are a supportive customer service agent. Provide an empathetic update for this query: Where is my order 12345

Output: Thank you for checking in. Your order 12345 has already been shipped and is expected to reach you by tomorrow. We appreciate your patience.

Result: Empathetic and reassuring.

b) Prompt-1: You are a customer care agent. Track this order: 8888
Output: Your order 8888 is on its way and will reach you soon. Thank you for waiting.

Prompt-2: You are a polite support representative. Provide an update for order 3000
Output: Order 3000 has been packed and will be dispatched within a few hours.

## SCENARIO 3: RETURN AND REFUND POLICY

Customer Query: Can I return a product if I don’t like it

## Instruction-Based Prompting

a) Prompt: Explain the return policy in two simple sentences.

Output: Yes, you can return products within 30 days of purchase. Please ensure the item is unused and in its original packaging.

Result: Clear and concise.

b) Prompt-1: Explain the refund process in one sentence
Output: Refunds are issued to the original payment method within five to seven business days.

c) Prompt-2: Describe the return steps in three sentences
Output: First, initiate the return request on our website. Then pack the item securely. Finally, schedule a pickup or drop it at the nearest store.

## Socratic Prompting

a) Prompt: Ask guiding questions to help the customer check eligibility for return.

Output: Was the product purchased within the last 30 days? Is it unused? Do you have the original box and bill? If yes, then you are eligible for a return.

Result: Encourages self-checking.

b) Prompt-1: Use questions to guide a customer about refund eligibility
Output: Did the issue occur within the warranty period? Do you have proof of purchase? Was the item damaged when delivered

c) Prompt-2: Guide the customer to check if an exchange is possible
Output: Was the size incorrect? Is the product unused? Is the tag attached

## SCENARIO 4: TROUBLESHOOTING

Customer Query: My coffee maker is not working. What should I do

## Chain-of-Thought Prompting

a) Prompt: Think step by step and guide the customer in troubleshooting the coffee maker.

Output: First, make sure the machine is connected to power. Next, check if the water tank is full. Then verify that the filter is inserted correctly. Also check for blockages. If the machine still does not work, please contact support.

Result: Structured and effective.

b) Prompt-1: Provide step by step troubleshooting for a phone that will not turn on
Output: First check the battery, then charge the device, press and hold the power button, remove the case if necessary, and finally attempt a forced restart.

c) Prompt-2: Provide step by step troubleshooting for a washing machine that does not start
Output: Check if the power cord is plugged in, ensure the door is closed properly, verify water supply, restart the machine, and check for error codes.

## Persona-Driven Prompting

a) Prompt: You are a friendly technical assistant. Help the customer troubleshoot their coffee maker.

Output: Please check if the machine is plugged in properly. Then ensure that the water tank is filled and the filter is correctly placed. If the issue continues, our support team can assist you further.

Result: Friendly yet informative.

b) Prompt-1: You are a helpful technician. Troubleshoot a refrigerator that is not cooling
Output: Check the power supply, then ensure the thermostat is set correctly, clean the back coils, and check whether the door is sealing properly.

c) Prompt-2: You are a calm and patient assistant. Troubleshoot a laptop that is overheating
Output: Close unused applications, clean the air vents, remove dust, and place the laptop on a hard surface to improve airflow.

## ANALYSIS

a) Zero-shot
Accurate but generic and non-personalized

b) One-shot
Learns pattern quickly but may assume availability

c) Few-shot
Most natural and accurate due to patterned examples

d) Role-based
High empathy and customer engagement

e) Instruction-based
Useful for short, rule-based answers

f) Chain-of-thought
Best for technical troubleshooting

g) Socratic
Useful for eligibility checks but less direct

h) Persona-driven
Friendly and customer-focused

## CONCLUSION:

The most effective retail chatbot design combines:

Few-shot prompting for accuracy and context
Role-based prompting for empathy and customer friendliness
Chain-of-thought prompting for troubleshooting
Instruction-based prompting for policies

This hybrid prompting strategy ensures a chatbot that is accurate, human-like, and capable of providing helpful retail customer support.
