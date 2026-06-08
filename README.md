

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
Task Chosen

Task: Sentiment Analysis of a Product Review

Review:
"The phone has an excellent camera and battery life, but the software is slow and crashes frequently."

1. Basic Prompt
Prompt

Analyze the sentiment of the following review:

"The phone has an excellent camera and battery life, but the software is slow and crashes frequently."

Response

The review expresses mixed sentiment.

Positive points:

Excellent camera
Good battery life

Negative points:

Slow software
Frequent crashes

Overall sentiment: Mixed, with both positive and negative opinions.

2. Zero-Shot Prompt
Prompt

You are a sentiment analysis assistant.

Determine whether the following review is Positive, Negative, or Mixed. Provide a brief explanation.

Review:
"The phone has an excellent camera and battery life, but the software is slow and crashes frequently."

Response

Sentiment: Mixed

Explanation:
The review contains both positive and negative opinions. The camera and battery life are praised, while the software performance is criticized for being slow and unstable.

3. Few-Shot Prompt
Prompt

Example 1:

Review: "The laptop is fast, reliable, and easy to use."

Sentiment: Positive

Reason: The review contains only positive comments.

Example 2:

Review: "The printer breaks often and customer support is poor."

Sentiment: Negative

Reason: The review contains only negative comments.

Now analyze:

Review: "The phone has an excellent camera and battery life, but the software is slow and crashes frequently."

Response

Sentiment: Mixed

Reason:
The review includes positive feedback about the camera and battery life, but negative feedback about software performance and stability.

4. Chain-of-Thought Prompt
Prompt

Analyze the following review step by step.

Review:
"The phone has an excellent camera and battery life, but the software is slow and crashes frequently."

Steps:

Identify positive aspects.
Identify negative aspects.
Evaluate the impact of each aspect.
Determine the overall sentiment.
Provide the final conclusion.
Response

Step 1: Positive Aspects

Excellent camera
Long battery life

Step 2: Negative Aspects

Slow software
Frequent crashes

Step 3: Impact Analysis

Camera quality improves user experience.
Battery life increases usability.
Slow software reduces efficiency.
Crashes create frustration and reliability issues.

Step 4: Overall Evaluation
The review contains both positive and negative opinions.

Step 5: Final Conclusion
Sentiment: Mixed

The user appreciates the hardware features but is dissatisfied with the software performance.

Evaluation of Responses
Evaluation Method: Quality, Accuracy, and Depth Analysis
Prompt Type	Quality	Accuracy	Depth	Remarks
Basic Prompt	Good	High	Low	Gives direct answer with limited details.
Zero-Shot Prompt	Good	High	Medium	Clear classification and brief explanation.
Few-Shot Prompt	Very Good	High	Medium	Examples help the model follow the desired format consistently.
Chain-of-Thought Prompt	Excellent	High	High	Provides detailed reasoning and better transparency.
Comparison Summary
Technique	Advantages	Limitations
Basic Prompt	Simple and fast	Less detailed
Zero-Shot Prompt	No examples required	May vary in response quality
Few-Shot Prompt	Improves consistency using examples	Requires additional prompt space
Chain-of-Thought Prompt	Produces detailed reasoning and deeper understanding	Longer response time and output

# RESULT: The prompt for the above said problem executed successfully
