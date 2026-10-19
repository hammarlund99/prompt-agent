# Quick Reference Guide

## The Prompt Agent Command

Start every task with:
```
@prompt-agent: [your task description]
```

## 5-Step Framework (CCCSV)

1. **CAPTURE** - What's the real objective?
2. **CLARIFY** - Remove all ambiguity
3. **CONTEXTUALIZE** - Add necessary information
4. **STRUCTURE** - Organize logically
5. **VALIDATE** - Check for completeness

## Essential Questions

### Before any task, ask yourself:

- [ ] What's the core objective?
- [ ] What does success look like?
- [ ] Who is the audience?
- [ ] What format is needed?
- [ ] What constraints exist?
- [ ] Are there any ambiguous terms?
- [ ] What background context is needed?
- [ ] Are there edge cases to consider?

## Red Flags 🚨

Your prompt needs work if:
- ❌ "Tell me about X" (too vague)
- ❌ No success criteria defined
- ❌ Conflicting requirements
- ❌ Undefined jargon
- ❌ Missing context
- ❌ No specified format
- ❌ Unrealistic expectations

## Prompt Types by Task

| Task | Type | Key Element |
|------|------|-------------|
| Write/Create | **Structured Output** | Format + tone + examples |
| Analyze/Evaluate | **Chain of Thought** | Criteria + perspective |
| Code | **Technical Specs** | Language + requirements + tests |
| Learn/Explain | **Few-Shot** | Examples + current knowledge |
| Plan/Strategy | **Step-by-Step** | Timeline + dependencies |
| Brainstorm | **Constraint-Based** | Rules + evaluation criteria |

## The Anti-Pattern Trap

**❌ Vague:** "Write a blog post"
**✅ Better:** "Write a 800-word technical blog post about React hooks for junior developers. Tone: educational and friendly. Include 2 code examples. Add conclusion with 3 key takeaways."

## Scoring Your Prompt

Rate 1-10:
- Clarity: ___
- Specificity: ___
- Context completeness: ___
- Success criteria definition: ___
- Format specification: ___

**Score 45+/50** = Ready to execute
**Score 35-44/50** = Needs refinement
**Score <35/50** = Start over

## Examples in This Repo

- **FRAMEWORK.md** - The complete 5-step methodology
- **TEMPLATES.md** - Ready-to-use templates
- **SYSTEM-RULES.md** - How the agent works
- **METRICS.md** - How to measure success

## Pro Tips

1. **Invest in the prompt** - Better prompt = better results
2. **Be specific** - Vague requests get vague answers
3. **Include examples** - "Like this" beats abstract descriptions
4. **State constraints** - What you DON'T want matters
5. **Define success** - What does done look like?
6. **Save winners** - Build your prompt library
7. **Iterate intelligently** - Track what works
8. **Think like an AI** - What would you need to understand this?

## Quick Refinement Checklist

Before hitting submit:

- [ ] **Objective clear?** Someone else could understand it
- [ ] **Success defined?** What does "good" look like?
- [ ] **Format specified?** JSON/markdown/list/paragraph/etc.
- [ ] **Context provided?** Background/constraints/examples
- [ ] **Assumptions stated?** No hidden expectations
- [ ] **Length/scope?** Short/medium/comprehensive?
- [ ] **Jargon defined?** All terms crystal clear
- [ ] **Edge cases?** Acknowledged and addressed

## Your Prompt Improvement Over Time

Track these metrics:

| Metric | Week 1 | Week 4 | Week 12 |
|--------|--------|--------|---------|
| First-attempt success % | ___% | ___% | ___% |
| Avg iterations needed | ___ | ___ | ___ |
| Time spent refining | ___ | ___ | ___ |
| Confidence in results | ___% | ___% | ___% |

**Goal: 90%+ first-attempt success by week 12**

---

**Remember:** Every great result starts with a great prompt. Invest in the refinement, and you'll become unstoppable.
