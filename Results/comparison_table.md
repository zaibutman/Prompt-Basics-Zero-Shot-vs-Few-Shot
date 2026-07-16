# Prompt Engineering Comparison

## Zero-Shot vs Few-Shot Prompting

| AI Model | Zero-Shot Accuracy | Few-Shot Accuracy | Improvement |
|----------|-------------------:|------------------:|------------:|
| ChatGPT | 09/10 (90%) | 10/10 (100%) | +10% |
| Claude | 10/10 (100%) | 10/10 (100%) | No Change  |
| Gemini | 9/10 (90%) | 10/10 (100%) | +10% |

---

## Overall Comparison

| Evaluation Metric | Zero-Shot Prompting | Few-Shot Prompting |
|-------------------|---------------------|--------------------|
| Ease of Setup | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐☆ |
| Context Provided | ⭐⭐☆☆☆ | ⭐⭐⭐⭐⭐ |
| Consistency | ⭐⭐⭐☆☆ | ⭐⭐⭐⭐⭐ |
| Classification Accuracy | Good | Excellent |
| Reliability | Moderate | High |

---

## Key Findings

- Zero-Shot Prompting performed well for straightforward classification tasks but occasionally misclassified messages with subtle intent.
- Few-Shot Prompting improved consistency by providing representative examples for each category.
- Example-driven prompts reduced ambiguity and helped the models better understand the expected output.
- Among the evaluated models, ChatGPT achieved perfect accuracy with both prompting techniques, while Claude and Gemini showed measurable improvements when examples were included.

---

## Conclusion

This experiment demonstrates that **Few-Shot Prompting** generally produces more reliable and consistent results than **Zero-Shot Prompting**. By supplying a small number of labeled examples, Large Language Models better understand the intended classification criteria, leading to improved accuracy and more dependable outputs across different AI platforms.

> **Note:** Replace these sample accuracy values with your actual results after testing the prompts in ChatGPT, Claude, and Gemini.