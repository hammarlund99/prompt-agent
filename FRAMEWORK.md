# Prompt Engineering Framework

## The Prompt Agent System

Your prompt agent uses this 5-step framework to transform any task into an optimized prompt:

### 1. **CAPTURE** - Understanding Your Intention
- What is the core objective?
- What problem are you trying to solve?
- What would success look like?

**Questions to ask:**
- Why are you asking this?
- What's the business/personal goal?
- Who is the audience for this result?

### 2. **CLARIFY** - Removing Ambiguity
- Identify vague terms and replace with specifics
- Define jargon and technical terms
- State assumptions explicitly

**Questions to ask:**
- What does "good" mean for this task?
- Are there multiple interpretations?
- What constraints exist?

### 3. **CONTEXTUALIZE** - Providing Relevant Information
- Add background information
- Specify the format/structure needed
- Include examples if relevant
- Define the target audience/user

**Questions to ask:**
- What background is needed?
- What format should the output be?
- What constraints or rules apply?

### 4. **STRUCTURE** - Organizing Logically
- Use numbered steps or bullet points
- Break complex tasks into subtasks
- Create a clear hierarchy
- Add role-playing or persona if helpful

**Questions to ask:**
- How should this be organized?
- Are there logical dependencies?
- Should a specific format be used?

### 5. **VALIDATE** - Testing and Refinement
- Review for completeness
- Check for contradictions
- Ensure all variables are defined
- Test with a sample query if possible

**Questions to ask:**
- Would this prompt reliably produce the desired output?
- Are there edge cases?
- Is anything missing or contradictory?

---

## Prompt Template Categories

### For Analysis Tasks
- Start with "Analyze [subject] in terms of [dimension]"
- Specify what good analysis looks like
- Request structured output (bullet points, tables, etc.)

### For Creative Tasks
- Define the creative constraints
- Provide examples of tone/style
- Specify format and length

### For Technical Tasks
- Include code examples if relevant
- Specify language/framework versions
- Request explanations alongside code

### For Writing Tasks
- Define tone, audience, and purpose
- Specify structure and length
- Provide examples of desired style

### For Planning Tasks
- Define scope and constraints
- Specify decision criteria
- Request prioritization approach

---

## Anti-Patterns to Avoid

❌ **Too vague**: "Tell me about marketing"
✅ **Better**: "Create 3 marketing strategies for a SaaS product targeting small businesses, focusing on cost-effective channels"

❌ **Missing context**: "Write a poem"
✅ **Better**: "Write a 16-line poem in iambic pentameter about overcoming failure, suitable for a motivational speech"

❌ **Conflicting requirements**: "Be creative but follow these 20 strict rules"
✅ **Better**: "Be creative within these constraints: [list constraints]"

❌ **Undefined success**: "Improve this code"
✅ **Better**: "Improve this code for readability and performance while maintaining backward compatibility"
