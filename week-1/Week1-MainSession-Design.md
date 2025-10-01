# Week 1 Main Session: Foundation Building
## Duration: 60 minutes | Structure: 15-20 min teaching → 20-30 min activity → 10 min Q&A/reflection

### Learning Objectives (from LearningOutcomes.md)
**Cognitive:**
- **Remember:** Define LLMs, tokens, context windows, context engineering
- **Understand:** Explain why LLMs hallucinate, how context windows affect outputs
- **Analyze:** Compare LLM outputs, determine when to use different AI tools

**Practical:**
- **Apply:** Improve prompts using context engineering principles
- **Create:** Write effective prompts for different work scenarios

---

## Part 1: Teaching Presentation (15-20 minutes)

### Slide 1: Welcome & Workshop Overview
**Time:** 2 minutes
**Key Points:**
- Welcome to Beyond Vibe Coding for Product Professionals
- 5-week journey: Foundation → Architecture → Design → Implementation → Integration
- Today: Understanding the basics so you can use AI tools effectively
- Structure: Learn → Practice → Reflect

### Slide 2: What Are We Really Working With?
**Time:** 3 minutes
**Key Points:**
- **LLMs are prediction machines, not knowledge databases**
- They predict the next most likely word based on training data
- This is why they can "hallucinate" - they're making predictions, not accessing facts
- Think of them as incredibly sophisticated autocomplete

**Interactive Element:** Ask participants to share one time they've seen an AI give incorrect information. Validate that this is normal and expected.

### Slide 3: Understanding Tokens & Context Windows
**Time:** 4 minutes
**Key Points:**
- **Tokens:** How AI "sees" text (roughly 4 characters = 1 token for English)
- **Context Window:** The AI's "working memory" - finite and measured in tokens
- **Why this matters:** When context window fills up, AI "forgets" earlier parts
- **Common limits:** ChatGPT (128K tokens), Claude (200K tokens), etc.

**Visual Aid:** Show a simple diagram of context window filling up over conversation length

**Real Example:** 
- Short prompt: "Write a product requirements document"
- Better: "You are a senior product manager at a tech startup. Write a PRD for a new mobile app feature that helps users track their daily habits. Include sections for: problem statement, user stories, acceptance criteria, and success metrics. The app's target audience is working professionals aged 25-40."

### Slide 4: The Art of Context Engineering
**Time:** 5 minutes
**Key Points:**
- **Context engineering = giving AI the right context to succeed**
- **Role definition:** Who should the AI act as?
- **Task specificity:** What exactly do you want?
- **Format specification:** How should the output be structured?
- **Examples & constraints:** What should it include or avoid?

**Framework:** R-R-F-E (Role-Request-Format-Examples)

**Quick Demo:** Show before/after prompts for same task

### Slide 5: Security & Privacy Considerations
**Time:** 3 minutes
**Key Points:**
- **Public AI tools:** Don't share sensitive company data, customer info, or personal details
- **Private tools:** Better for sensitive work (Claude Pro, ChatGPT Team, etc.)
- **General rule:** If you wouldn't post it on social media, don't put it in a public AI tool
- **Alternatives:** Use dummy data, anonymize examples, or use private tools

**Quick Decision Tree:** 
- Contains company secrets? → Use private tool or dummy data
- Contains customer info? → Use private tool or anonymize
- Contains personal details? → Use private tool or remove details
- None of the above? → Public tool is fine

### Slide 6: What We'll Practice Today
**Time:** 2 minutes
**Key Points:**
- Hands-on context engineering with real work scenarios
- We'll practice with prompts relevant to your roles (PM, designer, project manager)
- Focus on getting better outputs, not perfect outputs
- This is about learning the principles, not memorizing templates

---

## Part 2: Hands-On Context Engineering Activity (20-30 minutes)

### Activity Setup (2 minutes)
**Instructions:**
- We'll work in breakout rooms of 3-4 people
- Each person will pick one scenario from their role
- Practice writing prompts using the R-R-F-E framework
- Share and get feedback from your group
- We'll reconvene to share insights

### Scenarios by Role

#### For Product Managers:
1. **Generate user stories** for a new feature in your product
2. **Write a competitive analysis** of a tool your team is considering
3. **Create a product roadmap** for the next quarter
4. **Draft customer interview questions** for user research

#### For Designers:
1. **Generate design concepts** for a mobile app interface
2. **Create user personas** for a new target audience
3. **Write design system documentation** for your team
4. **Develop accessibility guidelines** for a web application

#### For Project Managers:
1. **Create a project timeline** for a new initiative
2. **Write status update templates** for stakeholder communication
3. **Generate risk assessment questions** for project planning
4. **Develop meeting agenda templates** for different meeting types

### Activity Process (18-25 minutes)
**Individual Work (8 minutes):**
- Pick one scenario relevant to your role
- Write your prompt using R-R-F-E framework
- Test it with your chosen AI tool
- Note what works well and what doesn't

**Group Discussion (10-15 minutes):**
- Share your prompt and results with your group
- Get feedback: What's clear? What could be improved?
- Help each other refine prompts
- Identify common patterns that work well

**Group Sharing (2 minutes):**
- Each group shares one "before" and "after" prompt example
- Highlight what made the difference

### Facilitator Support During Activity
- Circulate through breakout rooms
- Help groups who are stuck
- Point out good examples of context engineering
- Remind people to test their prompts, not just write them

---

## Part 3: Q&A and Reflection (10 minutes)

### Quick Share-Out (3 minutes)
**Ask each group:** What was one insight about writing better prompts?

### Q&A Session (5 minutes)
**Common questions to be prepared for:**
- "How do I know if my prompt is good enough?"
- "What if the AI doesn't understand my industry/company context?"
- "How often should I start a new conversation vs. continuing an old one?"
- "What's the difference between different AI tools?"

### Reflection Questions (2 minutes)
**Ask participants to think about:**
1. What's one thing you learned about AI that surprised you?
2. What's one prompt you want to try with your actual work this week?
3. What questions do you still have about using AI tools?

### Closing & Next Steps
**Time:** 1 minute
**Key Points:**
- Great work today! You've learned the foundational concepts
- This week's video will cover the Augmentation vs. Automation framework
- Office hours will help with GitHub setup for those who need it
- Your assignment is to try one prompt from today in your real work

---

## Materials Needed

### For Facilitators:
- [ ] Presentation slides (6 slides, ~15-20 minutes)
- [ ] Activity instructions printed/available
- [ ] Timer for breakout rooms
- [ ] Backup scenarios in case groups finish early
- [ ] List of common AI tools participants might use

### For Participants:
- [ ] Access to at least one AI tool (ChatGPT, Claude, etc.)
- [ ] Note-taking materials
- [ ] Breakout room assignments (if virtual)

### Visual Aids:
- [ ] Context window diagram
- [ ] R-R-F-E framework visual
- [ ] Before/after prompt examples
- [ ] Security decision tree

---

## Success Indicators

### During the Session:
- Participants are actively testing prompts, not just writing them
- Groups are helping each other improve their prompts
- People are asking specific questions about their work scenarios
- No one is completely lost or overwhelmed

### After the Session:
- Participants can explain why LLMs hallucinate
- They understand the concept of context windows
- They can write a prompt using the R-R-F-E framework
- They're excited to try AI tools with their actual work

---

## Backup Plans

### If Technology Fails:
- Have screen sharing ready with demo prompts
- Use chat to share examples instead of breakout rooms
- Focus on group discussion rather than individual testing

### If Time Runs Short:
- Skip the group sharing and go straight to Q&A
- Reduce individual work time to 5 minutes
- Focus on one role's scenarios if needed

### If Participants Are Struggling:
- Provide more specific examples
- Have a "prompt starter" template ready
- Pair up people who are struggling with those who are succeeding

---

## Connection to Other Week 1 Components

### Links to Recorded Video:
- This session covers the "what" of AI tools
- The video will cover the "when" (augmentation vs. automation decisions)
- Participants will be ready to apply the decision framework after this session

### Links to Office Hours:
- Participants who struggle with basic concepts can get help
- GitHub setup support for those who need it
- Individual questions about AI tool selection

### Links to Assignment:
- Participants will have concrete prompts to try in their work
- They'll understand the basics needed for the decision framework
- They'll be ready to share learnings with the cohort

---

## Assessment Integration

### Formative Assessment:
- **Exit tickets:** What did you learn? What's still confusing? What will you try?
- **Observation:** Are participants actively engaged in prompt testing?
- **Peer feedback:** Are they helping each other improve prompts?

### Connection to Learning Outcomes:
- **Remember:** Can they define key terms?
- **Understand:** Can they explain why context matters?
- **Apply:** Can they write better prompts than they started with?
- **Analyze:** Can they compare different prompt approaches?

This session sets the foundation for the entire workshop by ensuring everyone understands how AI tools actually work and how to use them effectively in their professional roles.
