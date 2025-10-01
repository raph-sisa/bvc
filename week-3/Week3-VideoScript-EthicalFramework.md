# Week 3 Follow-up Video: Ethical Considerations Framework
## Duration: 10-15 minutes | Format: Recorded video with visual aids

### Learning Objectives (from LearningOutcomes.md)
**Cognitive:**
- **Understand:** Describe common ethical pitfalls in AI implementations
- **Analyze:** Distinguish between AI that enhances vs. replaces human agency
- **Compare:** Evaluate good vs. problematic AI implementations

**Practical:**
- **Apply:** Use ethical considerations framework to evaluate AI features
- **Evaluate:** Assess whether AI features respect user agency
- **Create:** Determine if transparency and consent are appropriately handled

---

## Video Script

### Opening (30 seconds)
**[Visual: Workshop logo, friendly instructor on screen]**

"Hi everyone! I'm [Name], and welcome to your Week 3 follow-up video. In our main session, we explored design thinking and user agency. Now we're going to dive deeper into a practical ethical framework you can use to evaluate and improve any AI feature you're building or using."

**[Visual: Title slide - "Ethical AI: A Practical Framework for Non-Developers"]**

---

### Why Ethics Matters (Not Just Philosophy) (1.5 minutes)

**[Visual: Examples of AI gone wrong]**

"Let's start with why this matters. When I say 'ethics,' I'm not talking about abstract philosophy. I'm talking about real consequences that affect real people.

**[Visual: Three real-world examples with visuals]**

**Example 1: The Hiring Algorithm**
An AI hiring tool was trained on historical data and learned to discriminate against certain groups because the historical data reflected past discrimination. Result: Qualified candidates were rejected unfairly.

**Example 2: The Content Recommendation System**
A social media platform's recommendation algorithm prioritized engagement over wellbeing, leading to the spread of harmful content and negative mental health outcomes. Result: User harm at scale.

**Example 3: The Healthcare Chatbot**
An AI chatbot provided medical advice without clearly indicating it wasn't a replacement for professional medical care. Result: Users made dangerous health decisions.

**[Visual: Key insight highlighted]**

**Here's the key insight:** When you use AI to build or automate something, you're making ethical decisions whether you realize it or not. This framework helps you make those decisions thoughtfully and intentionally."

---

### The Five-Pillar Ethical Framework (6 minutes)

**[Visual: Framework overview with five pillars]**

"I've created a five-pillar ethical framework specifically for non-developers building with AI. Let's walk through each pillar:

**[Visual: Pillar 1 - Bias and Fairness]**

**Pillar 1: Bias and Fairness**

AI systems learn from data, and data reflects the world - including its biases and inequalities.

**Key Questions:**
1. **Whose perspectives are represented** in the training data?
2. **Who might be excluded or disadvantaged** by this AI feature?
3. **What assumptions** am I making about users?
4. **How will I test** for unfair outcomes?

**Practical Actions:**
- Test with diverse user groups
- Ask: "Would this work equally well for everyone?"
- Check outputs for patterns of discrimination
- Have multiple people review AI-generated content

**Red Flags:**
- ❌ AI trained only on data from one demographic group
- ❌ Assuming all users have the same needs or context
- ❌ Not testing with diverse users
- ❌ Treating AI outputs as neutral or objective

**Green Flags:**
- ✅ Testing with diverse user groups before launch
- ✅ Regular audits for biased outcomes
- ✅ Multiple perspectives in design decisions
- ✅ Clear process for reporting and addressing bias

**[Visual: Pillar 2 - Privacy and Data Protection]**

**Pillar 2: Privacy and Data Protection**

AI often requires data to function, but users have a right to privacy and control over their information.

**Key Questions:**
1. **What data** does this AI feature collect?
2. **Why do you need** that specific data?
3. **How will you protect** user data?
4. **Who has access** to the data?

**Practical Actions:**
- Collect only the data you actually need
- Be transparent about what data you're collecting and why
- Use secure storage and transmission
- Give users control over their data

**The Minimization Principle:**
**Ask: "Could this work with less data or no personal data?"**

**Red Flags:**
- ❌ Collecting data "just in case it's useful later"
- ❌ Not explaining data collection clearly
- ❌ Sharing user data with third parties without explicit consent
- ❌ Storing sensitive data without strong security

**Green Flags:**
- ✅ Clear privacy policy in simple language
- ✅ Opt-in (not opt-out) for data collection
- ✅ Easy way for users to access/delete their data
- ✅ Regular security audits

**[Visual: Pillar 3 - Transparency and Explainability]**

**Pillar 3: Transparency and Explainability**

Users have a right to understand when and how AI is involved in decisions that affect them.

**Key Questions:**
1. **Do users know** AI is involved?
2. **Can you explain** how the AI makes decisions?
3. **Are the limitations** of the AI clear?
4. **Can users get explanations** for specific AI actions?

**Practical Actions:**
- Clearly indicate when AI is generating or influencing content
- Provide explanations for AI recommendations or decisions
- Be honest about what the AI can and can't do
- Give users a way to ask "why?"

**The Transparency Spectrum:**
```
None → Some → Good → Excellent
No mention of AI → "AI-powered" label → Brief explanation → Detailed explanation + source info
```

**Red Flags:**
- ❌ Hiding that AI is involved
- ❌ Using vague language like "algorithm" without explanation
- ❌ No way for users to understand why AI made a decision
- ❌ Treating AI as infallible or objective

**Green Flags:**
- ✅ Clear labels when AI is generating content
- ✅ Simple explanations of how AI works
- ✅ Acknowledgment of AI limitations
- ✅ Option to see more details about AI reasoning

**[Visual: Pillar 4 - Accessibility and Inclusion]**

**Pillar 4: Accessibility and Inclusion**

AI features should work for everyone, including people with disabilities and those from different backgrounds.

**Key Questions:**
1. **Does this work for people** with visual, hearing, motor, or cognitive disabilities?
2. **Does this work** in different languages and cultural contexts?
3. **Can people with limited** technology access still use this?
4. **What alternatives** exist for people who can't or don't want to use AI?

**Practical Actions:**
- Test with screen readers and other assistive technologies
- Provide text alternatives to visual content
- Don't require latest technology or high bandwidth
- Offer non-AI alternatives for key functions

**The Universal Design Principle:**
**Design for the edges, and you improve the experience for everyone**

**Red Flags:**
- ❌ Assuming all users have perfect vision, hearing, and motor skills
- ❌ Only testing with latest devices and fast internet
- ❌ No alternatives to AI-powered features
- ❌ Text too small, contrast too low, etc.

**Green Flags:**
- ✅ Works with assistive technologies
- ✅ Multiple ways to accomplish key tasks
- ✅ Tested with diverse abilities and contexts
- ✅ Clear, simple language (not just for AI, for everyone)

**[Visual: Pillar 5 - Environmental Impact]**

**Pillar 5: Environmental Impact**

AI training and usage consumes significant energy and has real environmental costs.

**Key Questions:**
1. **Is AI necessary** for this feature, or would simpler solutions work?
2. **How often** will this AI be called?
3. **Can you optimize** to reduce AI usage?
4. **What's the right balance** between capability and cost?

**Practical Actions:**
- Use AI only when it adds clear value
- Cache results when possible
- Choose efficient models over powerful-but-wasteful ones
- Monitor and optimize AI usage

**The Necessity Test:**
**Ask: "What would this look like without AI? Is AI worth the cost?"**

**Red Flags:**
- ❌ Using AI because it's trendy, not because it's necessary
- ❌ Calling AI APIs unnecessarily frequently
- ❌ Using the largest model when a smaller one would work
- ❌ Not monitoring or optimizing usage

**Green Flags:**
- ✅ Clear rationale for why AI is needed
- ✅ Efficient implementation with caching
- ✅ Right-sized model for the task
- ✅ Regular review of AI necessity and usage"

---

### The User Agency Decision Tree (2 minutes)

**[Visual: Decision tree flowchart]**

"Now let's look at how to apply these principles to user agency decisions:

**[Visual: Decision tree with clear pathways]**

**Start Here: Should AI be involved in this decision?**

**↓**

**Question 1: What are the stakes?**
- High stakes (affects people's lives, money, opportunities) → Require human decision
- Medium stakes (convenience, preferences) → AI can suggest, human decides
- Low stakes (formatting, routine tasks) → AI can decide with easy override

**↓**

**Question 2: Can you explain the decision?**
- Can't explain → Don't use AI for important decisions
- Can explain generally → AI can assist
- Can explain specifically → AI can have more autonomy

**↓**

**Question 3: Can the user override or undo?**
- Can't undo → Require human approval before action
- Can undo with effort → AI can act with notification
- Easy to undo → AI can act automatically

**↓**

**Question 4: Does the user understand what's happening?**
- Doesn't understand → Add transparency and education
- Somewhat understands → Provide clear explanations
- Fully understands → User can make informed choices

**[Visual: User agency best practices]**

**Best Practices for User Agency:**
1. **Default to transparency** - Make AI involvement obvious
2. **Provide controls** - Give users meaningful choices
3. **Enable override** - Let users disagree with AI
4. **Explain decisions** - Help users understand why
5. **Learn preferences** - Adapt to individual user needs"

---

### Practical Application: The Ethical Evaluation Checklist (2.5 minutes)

**[Visual: Evaluation checklist template]**

"I've created a practical checklist you can use to evaluate any AI feature you're building or using:

**[Visual: Checklist being filled out]**

**Ethical Evaluation Checklist:**

**Bias and Fairness:**
- [ ] Tested with diverse user groups
- [ ] Checked for discriminatory outcomes
- [ ] Multiple perspectives included in design
- [ ] Process for reporting bias issues

**Privacy and Data Protection:**
- [ ] Clear about what data is collected and why
- [ ] Collect only necessary data
- [ ] Secure storage and transmission
- [ ] Users can access/delete their data

**Transparency and Explainability:**
- [ ] Clear when AI is involved
- [ ] Can explain how AI makes decisions
- [ ] Honest about limitations
- [ ] Users can ask "why?"

**Accessibility and Inclusion:**
- [ ] Works with assistive technologies
- [ ] Multiple ways to accomplish tasks
- [ ] Tested with diverse abilities
- [ ] Clear, simple language

**Environmental Impact:**
- [ ] Clear rationale for AI use
- [ ] Optimized to reduce unnecessary usage
- [ ] Right-sized model for the task
- [ ] Regular usage review

**User Agency:**
- [ ] Users know AI is involved
- [ ] Users can override AI decisions
- [ ] Users understand what AI is doing
- [ ] Easy to undo AI actions
- [ ] Appropriate level of automation for stakes

**[Visual: Scoring guidance]**

**How to Use This Checklist:**
- **20-24 checks:** Excellent - Strong ethical foundation
- **15-19 checks:** Good - Some areas for improvement
- **10-14 checks:** Needs work - Significant gaps to address
- **Below 10:** High risk - Major ethical concerns"

---

### Common Ethical Pitfalls (1.5 minutes)

**[Visual: Warning signs]**

"Before we close, let me share the most common ethical pitfalls I see:

**[Visual: Pitfall 1]**

**Pitfall 1: "Move Fast and Break Things"**
Don't launch AI features without thinking through consequences. Speed isn't worth harm.

**[Visual: Pitfall 2]**

**Pitfall 2: "The Data Made Me Do It"**
AI trained on biased data will produce biased results. You're responsible for the outcomes.

**[Visual: Pitfall 3]**

**Pitfall 3: "Users Don't Care About Privacy"**
Users do care - they just haven't been given good options. Respect privacy by default.

**[Visual: Pitfall 4]**

**Pitfall 4: "It's Just a Prototype"**
Prototypes become production systems. Build ethical practices in from the start.

**[Visual: Success indicators]**

**Signs You're on the Right Track:**
- You're asking "should we?" not just "can we?"
- You're testing with diverse users
- You're transparent about limitations
- You're giving users control and agency
- You're thinking about long-term consequences"

---

### Closing & Next Steps (1 minute)

**[Visual: Summary slide with key takeaways]**

"Let's recap what we've covered:
1. Ethics isn't philosophy - it's about real consequences for real people
2. Five-pillar framework: Bias, Privacy, Transparency, Accessibility, Environmental Impact
3. User agency decision tree for appropriate AI involvement
4. Practical evaluation checklist you can use right now
5. Common pitfalls to avoid

**[Visual: Next steps]**

**This week:**
- Use the evaluation checklist on your capstone project
- Identify one way to improve user agency in your design
- Share your ethical evaluation in cohort discussion
- Join office hours for design thinking practice

**Next week:** We'll move into practical implementation - advanced prompting techniques, quality assessment, and building your projects with everything we've learned.

**[Visual: Workshop logo]**

Thanks for watching, and I'll see you in our cohort discussion and office hours!"

---

## Visual Aids Needed

### Required Visuals:
- [ ] Workshop logo and branding
- [ ] Title slide: "Ethical AI: A Practical Framework for Non-Developers"
- [ ] Three real-world examples of AI ethics failures
- [ ] Five-pillar framework overview
- [ ] Detailed visual for each pillar with examples
- [ ] User agency decision tree flowchart
- [ ] Ethical evaluation checklist template
- [ ] Example checklist (partially filled)
- [ ] Common pitfalls warning signs
- [ ] Success indicators
- [ ] Summary slide with key takeaways

### Interactive Elements:
- [ ] Interactive decision tree
- [ ] Downloadable checklist
- [ ] Case study examples with evaluations

---

## Supporting Materials

### Ethical Evaluation Checklist
**File:** `Week3-EthicalEvaluation-Checklist.md`

**Sections:**
1. Five-pillar evaluation checklist
2. User agency assessment
3. Scoring guidance and interpretation
4. Action plan for improvements
5. Case studies with example evaluations

### User Agency Decision Guide
**File:** `Week3-UserAgency-DecisionGuide.md`

**Content:**
- Complete decision tree with examples
- Spectrum of AI involvement levels
- Role-specific user agency considerations
- Before/after redesign examples

---

## Assessment Integration

### Learning Outcome Alignment:
- **Understand:** Can participants explain ethical pitfalls?
- **Analyze:** Can they distinguish ethical from problematic AI?
- **Apply:** Can they use the evaluation framework?
- **Evaluate:** Can they assess user agency appropriately?

### Formative Assessment:
- **Checklist completion:** Shows understanding of framework
- **Cohort discussion:** Demonstrates application to projects
- **Office hours questions:** Reveals areas needing clarification

### Connection to Main Session:
- Builds on design thinking and user agency concepts
- Provides practical tools for ethical evaluation
- Prepares participants for implementing ethical AI features

---

## Success Metrics

### Immediate (End of Week 3):
- Participants complete ethical evaluation for their projects
- At least 80% can identify ethical considerations in examples
- Active participation in cohort discussion

### Medium-term (Week 4):
- Participants apply ethical framework to implementation decisions
- They understand how to preserve user agency
- They're making thoughtful ethical choices

### Long-term (End of Workshop):
- Participants have developed ethical AI mindset
- They can mentor others on ethical considerations
- They're building AI features that respect users

This video provides the practical ethical framework that ensures participants build AI features that serve users well and avoid common pitfalls.
