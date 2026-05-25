

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


# OUTPUT

1. Basic Prompt (Unstructured)

Prompt:

Look at this review and tell me what it is:
“This phone is okay. Battery lasts long but camera is not good.”

Typical Model Response:
Neutral / Mixed / Okay

Observation:

Too vague instruction
No format guidance
Different models may give inconsistent labels
2. Zero-Shot Prompt (Refined but no examples)

Prompt:

Classify the following product review as Positive, Negative, or Neutral.
Respond with only one label.
Review: “This phone is okay. Battery lasts long but camera is not good.”

Expected Response:
Neutral

Observation:

Clear task definition
Constrained output format
Better consistency across models
3. Few-Shot Prompt (With Examples)

Prompt:

Classify product reviews as Positive, Negative, or Neutral.

Examples:
Review: "The phone is amazing and works very fast." → Positive
Review: "Worst battery life ever, very disappointing." → Negative
Review: "It is okay, nothing special." → Neutral

Now classify:
Review: "This phone is okay. Battery lasts long but camera is not good."

Expected Response:
Neutral

Observation:

Model learns pattern from examples
Improves accuracy on mixed sentiment cases
Reduces ambiguity in interpretation
4. Chain-of-Thought Prompt (Step-by-step reasoning)

Prompt:

Classify the following review as Positive, Negative, or Neutral.
First, analyze the sentiment of each part of the sentence step by step, then give the final label.
Respond only with the final label.

Review: “This phone is okay. Battery lasts long but camera is not good.”

Typical Model Response (internal reasoning style):

“Okay” → neutral sentiment
“Battery lasts long” → positive sentiment
“Camera is not good” → negative sentiment
Mixed sentiments balance each other → overall neutral
Final Answer: Neutral

Observation:

Better handling of mixed sentiment
Encourages structured reasoning
Improves reliability for complex inputs
However, more verbose and slower
Evaluation Method Used: Rubric-Based Evaluation

We evaluate responses across 3 criteria (scale: 1–5):

| Prompt Type      | Clarity | Accuracy | Depth of Understanding | Overall Score |
| ---------------- | ------- | -------- | ---------------------- | ------------- |
| Basic Prompt     | 2       | 2        | 1                      | 1.7           |
| Zero-Shot Prompt | 4       | 4        | 2                      | 3.3           |
| Few-Shot Prompt  | 5       | 5        | 3                      | 4.3           |
| Chain-of-Thought | 5       | 5        | 5                      | 5.0           |

Key Findings
Basic prompts are too vague → inconsistent outputs
Zero-shot prompts improve structure but lack guidance for edge cases
Few-shot prompts significantly improve pattern recognition and accuracy
Chain-of-thought prompts provide the deepest understanding, especially for mixed or complex inputs
Final Insight

As prompts become more structured (basic → zero-shot → few-shot → CoT), model performance improves in:

Accuracy
Consistency
Reasoning quality

But they also trade off:

Speed (CoT is slower)
Simplicity (few-shot requires design effort)

# RESULT: The prompt for the above said problem executed successfully
