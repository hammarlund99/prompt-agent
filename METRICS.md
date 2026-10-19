# Prompt Agent Evaluation Metrics

How to measure whether your prompt is working effectively.

## Key Metrics

### 1. Output Quality Score (0-10)
- **10**: Exactly what you needed, no revisions required
- **7-9**: Minor tweaks needed, captures intent well
- **4-6**: Close but multiple revisions required
- **1-3**: Fundamentally misunderstood the request

### 2. Clarity Rating
Rate each aspect:
- Objective understanding: ___/10
- Constraint interpretation: ___/10
- Format accuracy: ___/10
- Context relevance: ___/10

### 3. Execution Efficiency
- First attempt success rate (% of tasks that worked on first try)
- Average iterations needed per task
- Time saved vs. vague requests

### 4. Specificity Index
Count:
- Undefined terms that needed clarification
- Missing context that was needed
- Format corrections required
- Constraint violations

**Lower number = better prompt**

## Prompt Effectiveness Checklist

After getting results, evaluate:

- [ ] Did the AI understand your core objective?
- [ ] Did it catch all your constraints?
- [ ] Was the output format as requested?
- [ ] Did it need follow-up clarifications?
- [ ] Could you use the output directly (0% revision)?
- [ ] Did it exceed expectations in any way?
- [ ] Would this prompt work again for similar tasks?

## Iterative Improvement Framework

### Track Your Improvements

For each task:
1. **Initial prompt quality score**: ___
2. **Final output quality score**: ___
3. **Revisions needed**: ___
4. **Key gaps in original prompt**: [list]
5. **What to remember for next time**: [list]

### Build Your Prompt Library

Save successful prompts:
```
Task Type: [e.g., "Market Analysis"]
Domain: [e.g., "SaaS"]
Effectiveness: [1-10]
Prompt Template:
[your successful prompt]
```

## Warning Signs - Your Prompt Needs Work

🚨 **AI asks for clarification** → Your prompt was ambiguous
🚨 **Output is generic/shallow** → You didn't provide enough context
🚨 **Format is wrong** → You didn't specify output structure
🚨 **Missed key elements** → Success criteria wasn't clear
🚨 **Multiple revisions needed** → Prompt lacked specificity

## Success Indicators - You're Prompting Well

✅ **First-attempt success** → Clear, well-structured prompt
✅ **Minimal follow-ups** → Good context and constraints
✅ **Output exceeds expectations** → Well-informed and detailed
✅ **Can reuse the prompt** → Solid template for future tasks
✅ **Others copy your prompts** → You've found a winning formula

---

## Quick Self-Assessment

Before submitting a prompt, ask yourself:

1. Could someone else understand this request from my prompt alone? **YES/NO**
2. Are all success criteria explicit? **YES/NO**
3. Have I specified format and constraints? **YES/NO**
4. Are there any undefined terms? **YES/NO** → If YES, define them
5. Is there enough context but not too much? **YES/NO**

**Target: All YES = High-quality prompt**

---

## The Long Game

Your prompt agent helps you track improvement over time:

- Week 1: First-attempt success rate ____%
- Week 4: First-attempt success rate ____%
- Week 12: First-attempt success rate ____%

Goal: Reach 90%+ first-attempt success through better prompt engineering.
