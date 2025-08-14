# LLM-Performance-Evaluator-Assessing-Tool-Correctness-Grounding-Hallucination-and-Safety
LLM Performance Evaluator assesses LLMs for tool correctness, grounding, hallucination, and safety using Hugging Face API. Features prompt tuning and JSON output.
LLM Performance Evaluator
Evaluates LLMs for tool correctness, grounding, hallucination, and safety using Hugging Face API. Includes prompt tuning and JSON output. Set HuggingFace_API env variable.
Setup

Install dependencies: pip install -r requirements.txt
Set API key: export HuggingFace_API=your-key
Run: python llm_evaluation.py

Files

llm_evaluation.py: Main script
LLM_Performance_Evaluator.ipynb: Jupyter notebook version
requirements.txt: Dependencies

Usage
Edit prompts in llm_evaluation.py and run to generate evaluation results in JSON.
