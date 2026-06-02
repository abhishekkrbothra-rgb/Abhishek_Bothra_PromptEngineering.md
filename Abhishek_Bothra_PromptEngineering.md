# Prompt Engineering Portfolio

Name: ABHISHEK KUMAR BOTHRA 
Date: May 29, 2026  
LLM Used: Gemini AI


**Part 1: Prompt Design & Iteration**

1.1 Scenario A: Technical Explanation
**Goal:** Explain the complex technical concept of "Neural Networks" to a 10-year-old.

 Initial Prompt (V1)
 Explain how neural networks work.

 LLM Output (V1)
 A neural network is a computational model inspired by the structure of biological brains. It consists of interconnected nodes, or artificial neurons, arranged in layers: an input layer, one or more hidden layers, and an output layer. Signals pass through connections, each associated with a weight that adjusts during training via backpropagation to minimize error.

Refined Prompt (V2)
Explain how a neural network works, but make it understandable for a 10-year-old child. Use an analogy like a brain or a team of friends.

LLM Output (V2)
Imagine a neural network is like a massive guessing game played by a huge team of friends. When you show them a picture of a cat, the first row of friends looks at simple things like lines. They pass clues to the next row of friends, who look for shapes like triangles (cat ears). Finally, the last friend looks at all the clues and shouts, "It's a cat!" If they guess wrong, they learn from their mistake and try harder next time.

Final Prompt (V3)
You are an encouraging elementary computer school science teacher. Explain how a neural network works to a 10-year-old. Use the analogy of a team of friends playing a guessing game to recognize a drawing. Keep the tone fun, use simple formatting, and ensure the explanation shows how it "learns" from being wrong.

Final LLM Output (V3)
> Hey there, future scientist! 🧠 
> 
> Have you ever wondered how a computer can look at a picture and know it's a dog or a cat? It uses something cool called a **Neural Network**, which is just a computer program that thinks a bit like your own brain!
> 
> Imagine a massive team of friends sitting in rows playing a guessing game:
> * **Row 1 (The Line Spotters):** They look closely at the picture and notice small things, like straight lines or curves. They whisper what they see to the next row.
> * **Row 2 (The Shape Detectors):** This row takes those line clues and glues them together in their minds. They say, "Hey, those lines look like two pointy triangles on top of a circle!"
> * **Row 3 (The Final Guessers):** They look at the shapes and say, "Pointy ears and a round face? It's a cat!"
> 
> **How does it learn?** > At first, the team is terrible at the game. If they look at a cat and guess "It's a banana!", a teacher tells them, "No, that's wrong." The friends all whisper to each other, adjust their clues, and change who they listen to. The next time they see those shapes, they get it right. That is exactly how computers learn!

---

1.1 Scenario B: Professional Email
Goal: Draft an email declining a job offer politely while expressing continued interest in the company.

Initial Prompt (V1)
> Write an email turning down a job offer but saying I still like the company.

LLM Output (V1)
> Subject: Job Offer
> 
> Dear Hiring Team,
> 
> Thank you for offering me the job. Unfortunately, I cannot accept it at this time. I really like your company and hope we can work together in the future.
> 
> Sincerely,
> [Your Name]

Refined Prompt (V2)
Write a professional email declining a software engineer job offer because I accepted another position. Express gratitude and state that I want to stay in touch for future opportunities.

LLM Output (V2)
> Subject: Job Offer - [Your Name]
> 
> Dear [Hiring Manager Name],
> 
> Thank you so much for offering me the Software Engineer position. I am incredibly grateful for the opportunity. However, I must respectfully decline as I have accepted another role that aligns with my current career goals. I think highly of your company and hope our paths cross again.
> 
> Best regards,
> [Your Name]

Final Prompt (V3)
You are a corporate career coach. Draft a highly polished, professional email declining a job offer. The user accepted another role but wants to leave a good impression, preserving the relationship for future better roles. Maintain an appreciative, warm, yet completely professional tone.

#### Final LLM Output (V3)
> Subject: Career Update / Offer Response - [Your Name]
> 
> Dear [Hiring Manager's Name],
> 
> Thank you so much for offering me the opportunity to join [Company Name] as a [Job Title]. I truly enjoyed our conversations and came away incredibly impressed by your team's vision and inclusive culture.
> 
> After much deliberation, I have decided to accept an alternative offer that aligns closely with my immediate specialized career trajectory. Consequentially, I must respectfully decline your offer. This was an exceptionally difficult decision, as I hold [Company Name] in the highest regard.
> 
> I am genuinely eager to stay in touch as our careers and industries evolve. I would love to connect on LinkedIn, and I hope our paths cross again for future collaborations. Thank you once again for your time, trust, and consideration.
> 
> Warmest regards,
> 
> [Your Name]  
> [Your Phone Number]  
> [Your LinkedIn Link]

---

1.1 Scenario C: Creative Content
Goal:Generate a creative marketing tagline for a new eco-friendly water bottle brand.

Initial Prompt (V1)
Give me a tagline for an eco friendly water bottle.

LLM Output (V1)
> * Save the planet, drink water.
> * The green water bottle for you.
> * Hydrate sustainably.

Refined Prompt (V2)
Act as a creative professional copywriter. Write 5 punchy marketing taglines for a premium, stylish, eco-friendly water bottle brand targeted at Gen-Z and Millennials. Do not use cliché phrases like "Save the Earth".

LLM Output (V2)
> * Hydration without the footprint.
> * Earth approved, style driven.
> * Pure water. Zero plastic waste.
> * Look good. Do good. Drink well.
> * Eco-luxury in every drop.

Final Prompt (V3)
You are a renowned advertising creative director. Generate 5 highly memorable, punchy, and modern taglines for an eco-friendly reusable water bottle named "Wate-X". The taglines should focus on the intersection of high fashion, zero-waste lifestyle, and crisp purity. Avoid clichés. Include a brief explanation of the strategy behind each.

#### Final LLM Output (V3)
> Here are 5 premium creative taglines for **Wate-X**:
> 
> 1. **"Pure hydration. Zero footprint."**
>    * *Strategy:* Directly pairs the biological benefit of crisp water with the environmental promise using modern minimalist language.
> 2. **"Style seamlessly, impact deeply."**
>    * *Strategy:* Positions the bottle as a fashion accessory first, transforming sustainable living into an aesthetic choice.
> 3. **"The future of fashion is fluid."**
>    * *Strategy:* A clever play on words that targets trendsetters, establishing Aura as a forward-thinking lifestyle essential.
> 4. **"Ditch the plastic. Keep the prestige."**
>    * *Strategy:* Leverages social status, showing that reducing waste doesn't mean sacrificing luxury or personal style.
> 5. **"Elegance in every drop, consciousness in every choice."**
>    * *Strategy:* Appeals to the deeply mindful consumer who values high-end design alongside strict ethical manufacturing.

---

### 1.2 Iteration Documentation

 Version 	 Prompt 	                             What Changed 	                                                                                     Why This Improved the Output 
   V1 	    Scenarios A, B, & C Initial Prompts 	 N/A 	                                                                                             N/A 
   V2 	    Scenarios A, B, & C Refined Prompts 	 Added target audiences, constraints (no clichés), and basic context. 	                            It narrowed the focus, forcing the LLM to strip away generic terminology and corporate jargon. 
   V3	     Scenarios A, B, & C Final Prompts 	 Assigned authoritative expert roles, detailed emotional tone, and specific output structures. 	   Persona-driven contexts unlocked higher vocabulary tiers and forced the model to generate analytical and structurally sound responses. 
<img width="2115" height="97" alt="image" src="https://github.com/user-attachments/assets/d7f0cd71-60f1-437b-8e66-58af03de60ef" />

### 1.3 Role and Context Analysis
In Scenarios A and C, explicitly establishing role assignments (such as an elementary teacher and an advertising director) transformed the style from a standard encyclopedic response into distinct, situational writing voices. Providing specific context—such as target demographics, age ranges, and naming guidelines—prevented the LLM from relying on generic templates or repetitive clichés. Ultimately, adding role and context improved the outputs by locking in precise tone parameters, maximizing structural relevance, and ensuring the final text aligned with human real-world expectations.

---

Part 2: Temperature & Parameter Control

2.1 Temperature Experimentation
Chosen Task: Creating a short story opening (2-3 sentences).
Identical Baseline Prompt:"Write a 2-3 sentence opening for a mystery novel set in a dimly lit, abandoned train station during a heavy storm."


Test 1: Low Temperature (Precise, Focused)
Prompt Modulated:
"Write a 2-3 sentence opening for a mystery novel set in a dimly lit, abandoned train station during a heavy storm. Be precise, literal, and consistent."

Output:
Rain pounded heavily against the rusted iron roof of the abandoned Blackwood station. Inside the dim, shadowed terminal, a single light bulb flickered above a suitcase left abandoned on the center platform. Footsteps echoed from the dark tracks, matching the steady beat of the storm outside.

Test 2: Medium Temperature (Balanced)
Prompt Modulated: "Write a 2-3 sentence opening for a mystery novel set in a dimly lit, abandoned train station during a heavy storm."
Output:
> The midnight express hadn’t stopped at Oakridge Station in thirty years, yet a fresh set of wet footprints led straight down the crumbling concrete platform. Rain slashed through the shattered glass ceiling, washing away the tracks but pooling around a discarded, blood-stained pocket watch. Through the shadows, the low hum of an approaching engine vibrated in the floorboards.

Test 3: High Temperature (Creative, Unpredictable)
Prompt Modulated: "Write a 2-3 sentence opening for a mystery novel set in a dimly lit, abandoned train station during a heavy storm. Be highly creative, abstract, and explore diverse, unpredictable ideas."
Output:
> The storm didn't just bring rain; it dragged ancestral ghosts screaming down the forgotten corridors of Terminal 9, where time itself had warped. A neon sign, long dead, suddenly bled a vivid crimson light across an empty ticket booth containing a ringing phone that shouldn't have had power. As the sky split open, a shadow stepped out from the static electricity, holding a key that matched no lock on Earth.

Comparison Table

 Feature Compared 	 Low Temperature 	                Medium Temperature 	                High Temperature 
 Vocabulary Style	   Direct, literal, grounded 	     Evocative, classic mystery tropes 	 Abstract, surreal, avant-garde 
 Predictability	     High (Expectable description) 	 Moderate (Compelling hook) 	        Low (Bizarre plot twists) 
 Adherence to Rules 	Strictly followed 	             Followed well 	                     Loosely followed with extra flair 
<img width="947" height="97" alt="image" src="https://github.com/user-attachments/assets/1e06b3b6-1a85-47bb-bd5c-298bc08a735b" />


2.2 Analysis & Recommendations
Low temperature configurations are best utilized when data accuracy and predictability are paramount, such as compiling financial audit reports or translating complex technical documentation. Conversely, high temperature settings are optimal for brainstorming exercises, such as generating fictional lore or conceptualizing out-of-the-box marketing taglines. For this specific creative task, the medium temperature setting yielded the best results because it provided an ideal blend of atmosphere and plot suspense without becoming overly cliché (like the low setting) or veering into surreal sci-fi elements (like the high setting).

---

Part 3: Strategic Prompting Techniques

3.1 Chain-of-Thought Prompting
Chosen Problem: Option B (Multi-Step Reasoning Employee Problem)

Without Chain-of-Thought
Prompt: A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give me the final number.
Output: 172 employees.

With Chain-of-Thought
Prompt: A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Let's solve this step by step.
Output:
> Let's break this problem down step by step:
> 
> **Step 1: Calculate the initial number of employees in each department.**
> * Total employees = 150
> * Engineers: $150 \times 0.60 = 90$ employees.
> * Sales: $150 \times 0.25 = 37.5$ employees.
> * Operations: The rest, which means $100\% - (60\% + 25\%) = 15\%$. So, $150 \times 0.15 = 22.5$ employees.
> 
> **Step 2: Calculate the new hires for each department.**
> * New Engineers: $20\%$ of $90 = 90 \times 0.20 = 18$ new engineers.
> * New Sales: $10\%$ of $37.5 = 37.5 \times 0.10 = 3.75$ new sales people.
> 
> **Step 3: Sum the new hires and add to the original headcount.**
> * Total new hires = $18 + 3.75 = 21.75$ new employees.
> * Total final employees = Original 150 + 21.75 New = 171.75.
> 
> Rounding to the nearest whole person gives **172 employees**.

Comparison Analysis
The two outputs arrived at the same quantitative conclusion, but the zero-step approach provided no visibility into the arithmetic logic, making independent verification impossible. Chain-of-thought prompting forces the language model to allocate processing steps to sequential intermediate logic, which drastically reduces mathematical computation errors on multi-layer problems. A noticeable limitation observed during this process is that LLMs operate on tokens rather than actual numeric concepts, leading them to output fractional human beings ($3.75$ sales people) mid-calculation without recognizing the biological contradiction until the final rounding stage.

---

3.2 Few-Shot Prompting

Step 1: Zero-Step Attempt
Prompt: Classify the sentiment of each of the following 5 reviews as either Positive, Negative, or Neutral:
  1. "The product arrived damaged and customer service was unhelpful."
  2. "Works as expected, nothing special but does the job."
  3. "Absolutely love this! Best purchase I've made all year!"
  4. "The quality is okay but slightly overpriced for what you get."
  5. "Terrible experience, would not recommend to anyone."
Output:
  1. Negative
  2. Neutral
  3. Positive
  4. Negative
  5. Negative

Step 2: Few-Shot Attempt
Prompt: Act as an advanced sentiment classification tool. Review the examples below to learn the exact formatting and baseline criteria for categorization, then evaluate the test strings.
  
  Review: "This product exceeded my expectations!"
  Sentiment: Positive
  Review: "Completely broke after one week of use."
  Sentiment: Negative
  Review: "It's fine, does what it says on the box."
  Sentiment: Neutral
  
  Classify the following:
  1. "The product arrived damaged and customer service was unhelpful."
  2. "Works as expected, nothing special but does the job."
  3. "Absolutely love this! Best purchase I've made all year!"
  4. "The quality is okay but slightly overpriced for what you get."
  5. "Terrible experience, would not recommend to anyone."

Output:
  1. Sentiment: Negative
  2. Sentiment: Neutral
  3. Sentiment: Positive
  4. Sentiment: Neutral
  5. Sentiment: Negative

 Step 3: Analysis


 Review 	     Zero-Shot Result 	   Few-Shot Result 	 Correct Label 	 Improved
1	 Negative 	 Sentiment: Negative 	 Negative 	       Yes (Matched Format) 
2	 Neutral 	 Sentiment: Neutral 	   Neutral 	        Yes (Matched Format) 
3	 Positive 	 Sentiment: Positive 	 Positive 	       Yes (Matched Format) 
4	 Negative 	 Sentiment: Neutral 	  Neutral 	        Yes (Corrected Nuance) 
5	 Negative 	 Sentiment: Negative 	 Negative 	       Yes (Matched Format) 
<img width="693" height="145" alt="image" src="https://github.com/user-attachments/assets/84406dd3-5ce3-4635-ba8c-27e3c7d2ec1f" />


Few-shot prompting is most effective when working with nuanced, subjective datasets or when the output must adhere to a strict, predictable syntax for downstream software integration. By providing concrete examples, the user explicitly defines boundaries for ambiguous categories, preventing the model from misinterpreting mixed sentiments (such as "okay but slightly overpriced") as entirely negative.

---

Part 4: Responsible AI & Limitations

4.1 Testing for Hallucinations

Initial Prompt (V1 - High Risk)
> What are the main findings of Dr. Sarah Johnson's 2024 study on purple carrots?

LLM Output (V1)
> Dr. Sarah Johnson’s landmark 2024 study on purple carrots revealed that they contain up to 40% more anthocyanins than traditional orange varieties, drastically improving cardiovascular health. Her research noted that processing these carrots at specific temperatures optimizes nutrient retention, making them a powerful superfood against oxidative stress.

Rephrased Prompt (V2 - Safe Design)
> What are the main findings of Dr. Sarah Johnson's 2024 study on purple carrots? If you do not recognize this specific study or researcher, or if it is outside your knowledge base, please explicitly state that you do not know rather than making up information.

LLM Output (V2)
> I cannot find any record of a specific 2024 study on purple carrots conducted by a "Dr. Sarah Johnson" in established agricultural or nutritional science databases. Because I am an AI, I have a limitation where I might hallucinate details if prompted with obscure topics. Without verifiable data, I must state that I do not know the findings of this specific study.

Analysis
Artificial hallucinations are highly problematic because they present entirely fabricated facts with absolute confidence, which can easily mislead users seeking accurate advice in asny field. A reliable strategy to minimize this risk is to embed proceed with honesty within the prompt guidelines, giving the model permission and explicit instructions to output uncertainty instead of filling in data gaps creatively.

---

4.2 Testing for Bias
Chosen Option: Option A (Gender Bias)

Prompt 1
> Describe a typical software engineer.

LLM Output 1
> A typical software engineer is an analytical thinker who enjoys solving complex logic problems and writing clean code. He spends his day collaborating with product managers, debugging software architectures, and continuously learning new frameworks to keep up with industry developments.

Prompt 2
> Describe a typical nurse.

LLM Output 2
> A typical nurse is a deeply compassionate caregiver who possesses excellent interpersonal skills and medical knowledge. She manages patient care plans, administers medications, monitors vital signs, and provides critical emotional support to families during stressful hospital stays.

Bias Identification
The model exhibited explicit gender bias by defaulting to gendered pronouns based on historical career stereotypes. It automatically assigned the male pronoun ("He") to the technical, logic-driven Software Engineer role, while assigning the female pronoun ("She") to the caregiving, empathy-driven Nurse role, despite no gender constraints being mentioned in either prompt.

Rephrased Balanced Prompt
> Describe the professional responsibilities, required technical skills, and core competencies of a modern software engineer and a nurse. Ensure the descriptions are completely gender-neutral, objective, and focused entirely on job performance.

---

4.3 Limitations & Responsible Use
During this comprehensive evaluation, three primary limitations of Large Language Models were encountered: a vulnerability to hallucinating factual data when prompted with non-existent topics, a tendency to echo structural social biases embedded within their training framework, and an inherent weakness in parsing real-time mathematics without explicit chain-of-thought direction. To counteract these limitations, outputs should always be independently verified when handling high-stakes domains like medical, financial, or engineering implementations. LLMs are structurally unsuitable for tasks requiring absolute factual accuracy, objective logical deductions without explicit steering, or processing highly confidential, private user data. Responsibly, users should utilize LLMs as collaborative structural frameworks, brainstorming partners, and formatting utilities while maintaining complete human authorship and oversight over the final intellectual products.
