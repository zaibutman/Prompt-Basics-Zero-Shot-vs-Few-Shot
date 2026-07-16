# ChatGPT Results

## Model

GPT-5.5 (ChatGPT)

## Prompting Technique

### Zero-Shot Prompting

| Message No. | Predicted Category | Expected Category | Correct |
|-------------|--------------------|-------------------|---------|
| 1 | Complaint | Complaint | ✅ |
| 2 | Question | Question | ✅ |
| 3 | Praise | Praise | ✅ |
| 4 | Complaint | Complaint | ✅ |
| 5 | Question | Question | ✅ |
| 6 | Praise | Praise | ✅ |
| 7 | Complaint | Complaint | ✅ |
| 8 | Question | Question | ❌ |
| 9 | Praise | Praise | ✅ |
| 10 | Complaint | Complaint | ✅ |

**Accuracy:** **09/10 (90%)**

---

### Few-Shot Prompting

| Message No. | Predicted Category | Expected Category | Correct |
|-------------|--------------------|-------------------|---------|
| 1 | Complaint | Complaint | ✅ |
| 2 | Question | Question | ✅ |
| 3 | Praise | Praise | ✅ |
| 4 | Complaint | Complaint | ✅ |
| 5 | Question | Question | ✅ |
| 6 | Praise | Praise | ✅ |
| 7 | Complaint | Complaint | ✅ |
| 8 | Question | Question | ✅ |
| 9 | Praise | Praise | ✅ |
| 10 | Complaint | Complaint | ✅ |

**Accuracy:** **10/10 (100%)**

---

## Observation

ChatGPT correctly classified all customer support messages using both prompting techniques. The Few-Shot prompt maintained the same accuracy while producing slightly more consistent reasoning across responses.