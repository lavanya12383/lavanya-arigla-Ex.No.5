

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT:
# 1. Prompting Techniques Overview

Zero-shot prompting → Model is given only the task, no examples.

Few-shot prompting → Model is given task + examples to guide style/format.

Chain-of-thought prompting (CoT) → Model is asked to reason step-by-step before giving the answer.

# 2. Example Scenario

Task: Explain the concept of “Photosynthesis” to a 10-year-old.
We’ll compare broad vs refined prompts across the 3 prompting techniques.

# 3. Responses
A. Zero-Shot Prompting

Broad Prompt: "Photosynthesis"

Refined Prompt: "Explain photosynthesis simply to a 10-year-old child in 3–4 sentences."

Responses:

Broad → "Photosynthesis is the process by which green plants make their food using sunlight, carbon dioxide, and water." (short, vague, no simplification)

Refined → "Photosynthesis is how plants make their own food. They take sunlight, water, and air and turn it into sugar for energy. This also gives us oxygen to breathe. It’s like the plant’s cooking recipe!" (clear, age-appropriate, richer)

B. Few-Shot Prompting

Broad Prompt: "Explain photosynthesis" + Example → "Explain gravity simply: Gravity is a force that pulls things down, like when an apple falls from a tree."

Refined Prompt: "Explain photosynthesis simply for a 10-year-old, like in the gravity example."

Responses:

Broad → "Photosynthesis is a process that plants use to make food. It is important for life." (still too short, lacks structure)

Refined → "Photosynthesis is when plants use sunlight, air, and water to make food. It’s like when you eat food for energy, but plants make their own. At the same time, they give out oxygen that people and animals need to breathe." (better aligned with the example, structured, engaging)

C. Chain-of-Thought Prompting

Broad Prompt: "Photosynthesis" + "Think step by step."

Refined Prompt: "Explain photosynthesis to a 10-year-old step by step. First describe what plants need, then how they use sunlight, and finally what they produce."

Responses:

Broad → "Plants use sunlight, water, and air to make food. The food is glucose. Oxygen is released." (shows some reasoning, but still factual and technical)

Refined → "Step 1: Plants need sunlight, water, and air.
Step 2: They use sunlight like energy to mix water and air.
Step 3: This makes food (sugar) that helps them grow.
Step 4: While making food, they also give us oxygen to breathe." (clear stepwise reasoning, kid-friendly, structured)


# 4. Evaluation (Rubric-Based Scoring)

Criteria: Clarity (1–5), Accuracy (1–5), Depth (1–5)

| Technique | Prompt Type | Clarity | Accuracy | Depth | Avg Score |
| --------- | ----------- | ------- | -------- | ----- | --------- |
| Zero-shot | Broad       | 2       | 4        | 2     | 2.7       |
| Zero-shot | Refined     | 5       | 5        | 4     | 4.7       |
| Few-shot  | Broad       | 3       | 4        | 3     | 3.3       |
| Few-shot  | Refined     | 5       | 5        | 4     | 4.7       |
| CoT       | Broad       | 3       | 5        | 3     | 3.7       |
| CoT       | Refined     | 5       | 5        | 5     | 5.0       |

# 5. Insights

Refined prompts consistently outperform broad prompts across all models.

Chain-of-thought + refined prompt yields the most accurate and deep response, especially for structured explanations.

Zero-shot broad prompts risk vague or overly technical answers.

Few-shot refined prompts improve alignment with desired tone/style.

Evaluation shows refinement boosts clarity by ~2 levels on average.

# RESULT: The prompt for the above said problem executed successfully
