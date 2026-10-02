# Week 01 - The AI Landscape

## Student Information

* **Name:** Shilpa
* **Track:** DFT
* **Program:** VLSIGuru AI Literacy Layer (16-Week Program)

---

# Q1 - AI → ML → DL → Generative AI → Agents

### A - Answer

**Artificial Intelligence (AI)** is the overall area of computing that aims to make machines perform tasks that normally require human-like abilities such as decision-making, learning, and understanding.

**Machine Learning (ML)** is a part of AI where systems learn patterns from examples or data instead of depending completely on manually written rules.

**Deep Learning (DL)** is a type of machine learning that uses neural networks with multiple layers to identify complex patterns in data.

**Generative AI** refers to AI systems that can create new content such as text, images, programs, audio, or other data after learning patterns from existing examples.

**AI Agents** are systems that combine AI models with tools and workflows to achieve a particular objective. They can decide what actions are needed and interact with external systems.

### Concept Relationship

AI is the broadest concept. ML is one approach within AI, and deep learning is a technique within ML. Generative AI commonly uses deep learning models. Agents operate at the application level and may use one or more of these technologies.

### Examples

1. **AI:** A computer system that plays chess.
2. **ML:** A spam detector trained using previous emails.
3. **DL:** A neural-network-based image recognition system.
4. **Generative AI:** ChatGPT generating an explanation from a prompt.
5. **AI Agent:** A system that searches information, uses tools, and completes several steps to achieve a user's goal.

### E - Evidence

The definitions were compared with standard AI and machine-learning educational material and technical references.

### V - Verification

I checked that ML is treated as a part of AI and that deep learning uses multi-layer neural networks. I also compared the distinction between a generative model and an agent-based application.

### R - Reflection

I learned that AI, ML, DL, GenAI, and agents are related but do not mean the same thing. Understanding their roles helps me identify what type of technology is being used in a particular application.

---

# Q2 - Is Everything That Looks Intelligent Actually AI?

### A - Answer

| Example                       | Classification       | Reason                                                           |
| ----------------------------- | -------------------- | ---------------------------------------------------------------- |
| Calculator performing 25 × 16 | Traditional software | Uses a predefined mathematical procedure.                        |
| Temperature alarm above 80°C  | Rule-based system    | Produces an output according to a fixed condition.               |
| Email spam detection          | ML-based AI          | Can learn patterns from previously classified emails.            |
| AI summarization tool         | Generative AI        | Creates a shorter version of given information.                  |
| Navigation ETA                | ML-based prediction  | Uses traffic and historical information to estimate travel time. |

A system does not automatically become AI just because it produces a useful or intelligent-looking result. Traditional software can also perform complicated calculations using explicitly defined instructions.

AI and ML systems generally use learned patterns or models to handle inputs. Therefore, the underlying mechanism should be examined before calling something AI.

### E - Evidence

I classified each example according to whether its behavior comes from fixed programming or learned patterns.

### V - Verification

I compared the classifications with standard definitions of rule-based programming and machine learning.

### R - Reflection

This exercise showed me that automation and AI are not interchangeable terms. A simple `if-else` condition may automate a task but does not necessarily involve AI.

---

# Q3 - What Happens When You Ask an LLM a Question?

### A - Answer

When I enter a question into an LLM, the following general process takes place:

1. The input is converted into **tokens**.
2. These tokens are provided to the model as part of its available context.
3. The neural network processes the input using its trained parameters.
4. The model calculates probabilities for possible next tokens.
5. A next token is selected according to the model's generation process.
6. The process continues repeatedly until the response is completed.

### Simple Flow

`User Prompt → Tokens → Model Processing → Next-Token Probabilities → Token Selection → Response`

Training and inference are different. During training, model parameters are adjusted using large datasets. During inference, the trained model uses those parameters to generate an answer for a given input.

### Why Can an LLM Give Wrong Information?

An LLM can produce text that sounds convincing even when the information is incorrect. A fluent answer should therefore not automatically be considered a verified answer.

### E - Evidence

The explanation was compared with introductory material on transformer-based language models and LLM operation.

### V - Verification

I checked the general process of tokenization, inference, and next-token prediction against technical explanations of LLMs.

### R - Reflection

The most important lesson for me is that an LLM generating a confident response does not guarantee that the response is factually correct. Verification is especially important for technical work.

---

# Q4 - Can AI Sound Confident and Still Be Wrong?

### A - Answer

I compared the response of different AI assistants for a factual question.

| Question                                          | ChatGPT                    | Gemini                     | Verification                               |
| ------------------------------------------------- | -------------------------- | -------------------------- | ------------------------------------------ |
| What is the approximate speed of light in vacuum? | Approximately 300,000 km/s | Approximately 300,000 km/s | Compared with a standard physics reference |

Both systems produced approximately the accepted value. However, this experiment also shows why the result should be checked against a reliable reference instead of trusting the response only because it sounds confident.

### E - Evidence

The AI responses were compared with a recognized scientific reference for the physical constant.

### V - Verification

The numerical result was checked independently rather than accepting either AI response as the final authority.

### R - Reflection

This exercise helped me understand that AI can give a correct answer, but the same method should also be used when an answer appears uncertain or highly technical. Confidence in wording is not proof of correctness.

---

# Q5 - AI Assistant vs Search vs Authoritative Reference

### A - Answer

| Factor          | AI Assistant                       | Search Engine                  | Authoritative Source            |
| --------------- | ---------------------------------- | ------------------------------ | ------------------------------- |
| Main purpose    | Explanation and generation         | Finding information            | Providing verified information  |
| Speed           | Very fast                          | Fast                           | Depends on the source           |
| Explanation     | Usually easy to understand         | Depends on the website         | Usually technical and precise   |
| Traceability    | May require checking citations     | Links to sources               | Usually has clear documentation |
| Main limitation | Can generate incorrect information | Search results vary in quality | May be difficult to understand  |

### When I Would Use Each

* **AI Assistant:** For learning a new concept, brainstorming, summarizing, or getting an initial explanation.
* **Search Engine:** For locating current information and finding relevant websites or documents.
* **Authoritative Reference:** For important technical specifications, standards, design decisions, and final verification.

### E - Evidence

I compared how the three approaches provide and present technical information.

### V - Verification

Important information obtained from an AI response should be compared with the original technical documentation before being used.

### R - Reflection

AI is useful for reducing the time needed to understand a topic, but it should work together with reliable references rather than replace them.

---

# Q6 - What Is an AI Agent?

### A - Answer

The following concepts can be distinguished as follows:

| Concept                  | Meaning                                                                                                 |
| ------------------------ | ------------------------------------------------------------------------------------------------------- |
| **LLM**                  | A trained language model that generates text by processing tokens.                                      |
| **LLM Application**      | An application that uses an LLM to provide a particular service.                                        |
| **RAG**                  | A method where external information is retrieved and supplied to the model before generating an answer. |
| **Tool-Using Assistant** | An AI system that can call external tools such as calculators or APIs.                                  |
| **AI Agent**             | A goal-oriented system that can decide steps, use tools, observe results, and continue a workflow.      |

### Example

Consider an AI travel assistant. The user gives a budget and destination. The system could search available options, calculate costs, compare the results, and prepare an itinerary using different tools.

### E - Evidence

The distinction was studied using common AI application and agent architecture concepts.

### V - Verification

I compared the roles of an LLM, RAG system, tool-using assistant, and agent to understand how each one adds functionality.

### R - Reflection

I learned that an LLM itself mainly generates responses, while an agent can be part of a larger system that performs actions and uses external tools.

---

# Q7 - Where Should Humans Still Make the Decision?

### A - Answer

Human verification remains important when an AI mistake can have significant consequences.

| Situation                | Possible Risk               | Human Verification                    |
| ------------------------ | --------------------------- | ------------------------------------- |
| Safety-critical software | Undetected technical errors | Engineering review and testing        |
| Medical information      | Incorrect recommendation    | Qualified medical review              |
| Legal documents          | Incorrect interpretation    | Legal professional review             |
| Financial decisions      | Financial loss              | Validated analysis and human approval |
| Hiring decisions         | Unfair or biased outcomes   | Human evaluation and fairness checks  |

AI can assist with analysis, but the final decision should remain with an appropriately qualified person when the consequences of an error are serious.

### E - Evidence

I considered common AI failure modes in high-impact applications and the need for human oversight.

### V - Verification

The principle was compared with responsible-AI and AI-risk-management guidance.

### R - Reflection

AI should support human decision-making rather than remove human responsibility. The level of checking should increase when the consequences of an incorrect result are higher.

---

# Q8 - Find AI Around You

### A - Answer

| Application                 | AI Involved? | Main Task                                  |
| --------------------------- | ------------ | ------------------------------------------ |
| Video recommendations       | Yes          | Recommendation                             |
| Smartphone face recognition | Yes          | Image recognition                          |
| Basic room thermostat       | Usually no   | Rule-based control                         |
| Voice assistant             | Yes          | Speech recognition and language processing |
| Bank fraud detection        | Yes          | Pattern/anomaly detection                  |

Some applications can also combine AI and conventional programming. Therefore, identifying the actual technology used is more useful than relying only on the product's marketing description.

### E - Evidence

I considered common consumer applications and the types of computational tasks they perform.

### V - Verification

The examples were compared with technical descriptions of recommendation, recognition, speech, and fraud-detection systems.

### R - Reflection

I noticed that AI is present in many everyday applications, but not every automated feature requires AI. Understanding the underlying method helps distinguish AI from ordinary automation.

---

# Q9 - Prediction, Classification, and Generation

### A - Answer

1. **Estimating the price of a house:** Prediction / Regression
2. **Determining whether an image contains a cat:** Classification
3. **Creating an email from instructions:** Generation
4. **Determining whether a customer may leave a service:** Classification / Prediction
5. **Creating a summary of a research paper:** Generation
6. **Determining whether a transaction is fraudulent:** Classification
7. **Creating an image from a text prompt:** Generation
8. **Estimating the next token in a sentence:** Prediction

### Difference Between Them

* **Prediction:** Estimates a value or future outcome.
* **Classification:** Assigns an input to one or more categories.
* **Generation:** Produces new content based on an input or instruction.

LLMs can perform many different-looking tasks using the same underlying language-generation process. For example, summarization and email writing both involve generating a sequence of tokens based on the available context.

### E - Evidence

The classifications were compared with standard machine-learning task definitions.

### V - Verification

I checked whether each example produces a numerical estimate, category, or newly generated content.

### R - Reflection

This exercise helped me distinguish the purpose of different AI tasks instead of treating every AI application as simply "prediction."

---

# Q10 - Design Your Personal AI Verification Protocol

### A - Answer

## My 7-Step AI Verification Protocol

**Step 1 - Understand the Requirement**
First, I clearly define what I need from the AI and identify the expected output.

**Step 2 - Check the Assumptions**
I look for assumptions that the AI may have made about the problem, data, or conditions.

**Step 3 - Verify Important Facts**
I check important factual and technical information using reliable documentation or primary sources.

**Step 4 - Test the Output**
For code, calculations, circuits, or technical procedures, I test the result instead of relying only on the explanation.

**Step 5 - Check Edge Cases**
I consider unusual inputs, boundary conditions, missing information, and possible failure cases.

**Step 6 - Review and Modify**
I decide whether the output should be accepted, corrected, or rejected based on the verification results.

**Step 7 - Record the Verification**
For important work, I keep track of the AI prompt, output, sources checked, tests performed, and changes made.

### Example

If AI generates a Python program for processing a dataset:

1. I define what the program should accomplish.
2. I check what assumptions the code makes about the input.
3. I verify important Python functions using documentation.
4. I run the program with sample data.
5. I test empty, incorrect, and unusual inputs.
6. I fix any errors found during testing.
7. I record the final changes and verification steps.

### E - Evidence

The protocol is based on general software testing, verification, and review practices.

### V - Verification

I checked that the process includes requirement definition, source verification, testing, edge-case analysis, human review, and documentation.

### R - Reflection

My main learning from this week is that AI should be treated as a useful assistant rather than an unquestionable source of truth. A structured verification process allows me to use AI efficiently while maintaining responsibility for the final result.
