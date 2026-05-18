EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

Evaluation of Prompting Techniques Across LLM Platforms for Text Summarization
1. INTRODUCTION
Text summarization is a core NLP task involving condensing large text into shorter,
meaningful content. With the rise of large language models (LLMs), prompt engineering has
become a key determinant of output quality.
This report evaluates how different prompting strategies affect summarization performance
across:
ChatGPT (OpenAI)
Gemini (Google)
Claude (Anthropic)
Copilot (Microsoft)
2. BACKGROUND: LLMs & SUMMARIZATION
LLMs perform summarization using:
Abstractive summarization (generate new sentences)
Extractive summarization (select key sentences)
Performance depends heavily on:
Prompt clarity
Context provided
Model architecture
Studies show closed-source models (GPT, Claude, Gemini) outperform others in
summarization tasks, especially when using structured prompting like CoT �.
Springer
3. PROMPTING TECHNIQUES OVERVIEW
3.1 Zero-Shot Prompting
No examples
Direct instruction
Example:
“Summarize this article in 100 words.”
3.2 Few-Shot Prompting
Includes examples
Teaches pattern recognition
3.3 Chain-of-Thought (CoT)
Encourages reasoning steps
Example: “Think step by step before summarizing”
3.4 Role-Based Prompting
Assigns persona
Example: “You are a news editor…”
4. RESEARCH METHODOLOGY
Experimental Setup
Same dataset across models
Same text inputs
Different prompt styles
Tasks
News summarization
Academic summarization
Conversational summarization
Controls
Temperature = low (for consistency)
Same token limits
5. EVALUATION METRICS
Quantitative Metrics
ROUGE score
BLEU score
Compression ratio
Qualitative Metrics
Coherence
Relevance
Faithfulness (hallucination rate)
Readability
6. PLATFORM OVERVIEW
Platform
Strength
ChatGPT
Strong reasoning & structure
Claude
High coherence & human-like tone
Gemini
Strong contextual learning
Copilot
Good for simple tasks
7. ZERO-SHOT PROMPTING ANALYSIS
Key Findings
Works well for simple summarization
Performance drops in complex texts
Research shows:
GPT models perform strongly in zero-shot tasks
Copilot excels in basic understanding tasks �
ScienceDirect
Strengths
Fast
No setup required
Weaknesses
Less control
Inconsistent quality
8. FEW-SHOT PROMPTING ANALYSIS
Key Findings
Improves structure and accuracy
Helps maintain tone
Studies show:
Few-shot improves accuracy across tasks (e.g., +12% improvement observed) �
arXiv
Gemini benefits significantly from few-shot examples �
Medium
Strengths
Better formatting
More predictable outputs
Weaknesses
Requires manual examples
Token cost increases
9. CHAIN-OF-THOUGHT (CoT) PROMPTING
Key Findings
Improves reasoning and coherence
Best for complex summarization
Research highlights:
CoT improves performance by 5–15% in NLP tasks �
Springer
Strongest method in advanced tasks (score ~87 vs 70 zero-shot) �
MDPI
Strengths
Better logical flow
Reduced hallucinations
Weaknesses
Longer outputs
Not always needed for simple summaries
10. ROLE-BASED PROMPTING
Key Findings
Improves tone and audience alignment
Works best when combined with clear instructions
Community experiments show:
Role prompts alone are weak, but powerful when combined with task constraints �
Reddit
Strengths
Customizable tone
Better audience targeting
Weaknesses
Can be inconsistent alone
11. COMPARATIVE RESULTS
Overall Effectiveness Ranking (Summarization)
Technique
Effectiveness
Chain-of-Thought
⭐⭐⭐⭐⭐
Few-Shot
⭐⭐⭐⭐⭐
Role-Based
⭐⭐⭐⭐
Zero-Shot
⭐⭐⭐
12. CROSS-PLATFORM OBSERVATIONS
ChatGPT
Best with zero-shot + CoT
Strong analytical summaries
Claude
Best with CoT prompting
Produces most natural summaries
Gemini
Best with few-shot prompting
Learns patterns well
Copilot
Strong in simple zero-shot tasks
Weak in complex summarization
Research confirms:
Prompt effectiveness is model-specific �
arXiv
13. STRENGTHS & WEAKNESSES
Strengths Across Models
High scalability
Adaptable to domains
Weaknesses
Sensitive to prompt wording
Risk of hallucination
14. HYBRID PROMPTING STRATEGIES
Best performance comes from combining techniques:
Example Hybrid Prompt:
“Act as a journalist. Here are examples. Think step by step and summarize…”
Benefits:
Combines structure + reasoning + tone
Studies show hybrid approaches outperform single techniques �
Medium
15. PRACTICAL RECOMMENDATIONS
For Simple Tasks
→ Use Zero-shot
For Structured Output
→ Use Few-shot
For Complex Summaries
→ Use Chain-of-Thought
For Audience-Specific Output
→ Use Role-based
Best Overall Strategy
→ Combine all four techniques
16. CONCLUSION
Key Takeaways
Prompting technique significantly affects summarization quality
No universal best method—depends on:
Task complexity
Model used.


[Prompt.ex-2 (2).pdf](https://github.com/user-attachments/files/27970226/Prompt.ex-2.2.pdf)


RESULT:
 Thus, the given article is summarized based on the different prompt technique and different AI tools.
