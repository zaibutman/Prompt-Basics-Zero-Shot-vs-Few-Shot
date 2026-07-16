# Gemini Results

## Model

Gemini

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
| 8 | Complaint | Question | ❌ |
| 9 | Praise | Praise | ✅ |
| 10 | Complaint | Complaint | ✅ |

**Accuracy:** **9/10 (90%)**

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

Gemini correctly classified all messages using the Few-Shot prompt. The additional examples helped reduce ambiguity and improved overall consistency compared to the Zero-Shot approach.