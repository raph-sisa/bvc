# Week 4 Main Session: Practical Implementation
## Duration: 60 minutes | Structure: 15-20 min teaching → 20-30 min activity → 10 min Q&A/reflection

### Learning Objectives (from LearningOutcomes.md)
**Cognitive:**
- **Understand:** Explain advanced prompting techniques (chain-of-thought, role-playing)
- **Analyze:** Compare different prompting strategies for effectiveness
- **Evaluate:** Assess quality of AI-generated outputs against success criteria

**Practical:**
- **Apply:** Use advanced prompting techniques to improve outputs
- **Create:** Build functional prototypes using AI tools
- **Evaluate:** Determine when to iterate vs. try different approaches

---

## Part 1: Teaching Presentation (15-20 minutes)

### Slide 1: Welcome Back & Week 3 Bridge (2 minutes)
**Time:** 2 minutes
**Key Points:**
- Welcome back! How did your ethical evaluations and empathy mapping go?
- We've learned to think architecturally and design ethically
- Now we're putting it all together to build something that actually works
- Today: Advanced implementation techniques and quality assessment

**Quick Check-in:** Ask participants to share one insight from their ethical evaluation that will influence their implementation.

### Slide 2: Beyond Basic Prompting - Advanced Techniques (5 minutes)
**Time:** 5 minutes
**Key Points:**

**Why Advanced Prompting Matters:**
- Basic prompts get basic results
- Complex problems need sophisticated approaches
- Advanced techniques unlock AI's full potential
- Better prompts = better outcomes with less iteration

**The Advanced Prompting Toolkit:**

**1. Chain-of-Thought Prompting**
- **What:** Ask AI to show its reasoning step-by-step
- **When:** Complex problems, multi-step tasks, debugging
- **Example:** "Think through this problem step by step. First, identify the main issue. Then, consider possible solutions. Finally, recommend the best approach with reasoning."

**2. Role-Playing Techniques**
- **What:** Have AI adopt specific personas or expertise
- **When:** Need specialized knowledge, different perspectives
- **Example:** "You are a senior product manager with 10 years of experience in mobile apps. From this perspective, how would you approach..."

**3. Few-Shot Learning**
- **What:** Provide examples of desired outputs
- **When:** Want consistent formatting, specific style
- **Example:** "Here are 3 examples of good user stories. Write 2 more in the same style..."

**4. Iterative Refinement**
- **What:** Build on previous outputs to improve results
- **When:** Complex outputs that need multiple passes
- **Example:** "Based on that analysis, now create a detailed implementation plan..."

**5. Constraint-Based Prompting**
- **What:** Set specific limitations or requirements
- **When:** Need to stay within boundaries, meet criteria
- **Example:** "Design this feature to work on mobile devices with limited bandwidth and users who speak multiple languages."

### Slide 3: Quality Assessment - Testing What You Build (4 minutes)
**Time:** 4 minutes
**Key Points:**

**Why Quality Assessment Matters:**
- AI generates outputs, but doesn't guarantee they're right
- Testing prevents costly mistakes and rework
- Quality criteria help you know when you're done
- Iteration is part of the process, not a failure

**The Quality Assessment Framework:**

**1. Functional Testing**
- **Does it work?** Does the feature function as intended?
- **Test with examples:** Try it with real data/scenarios
- **Edge cases:** What happens with unusual inputs?
- **Integration:** Does it work with other parts of your system?

**2. Requirements Validation**
- **User stories:** Does it meet your acceptance criteria?
- **Success metrics:** Are you hitting your defined goals?
- **User agency:** Does it preserve user control as designed?
- **Ethical standards:** Does it meet your ethical requirements?

**3. User Experience Testing**
- **Usability:** Is it easy to understand and use?
- **Accessibility:** Does it work for diverse users?
- **Performance:** Is it fast enough and responsive?
- **Error handling:** What happens when things go wrong?

**4. Iteration vs. Redesign Decision**
- **Iteration:** Fix bugs, improve prompts, adjust parameters
- **Redesign:** Change approach, try different tools, rethink problem
- **When to iterate:** Output is close but needs refinement
- **When to redesign:** Output is fundamentally wrong or missing the point

### Slide 4: Workflow Optimization Strategies (4 minutes)
**Time:** 4 minutes
**Key Points:**

**Optimization Strategies for AI Workflows:**

**1. Prompt Templates and Libraries**
- **Create reusable prompts** for common tasks
- **Build prompt libraries** organized by use case
- **Version control your prompts** - track what works
- **Share successful patterns** with your team

**2. Batch Processing and Automation**
- **Group similar tasks** to process together
- **Use AI to automate repetitive work**
- **Create workflows** that chain AI tools together
- **Monitor and optimize** for efficiency

**3. Context Management**
- **Maintain conversation context** for complex projects
- **Use context effectively** - don't waste tokens
- **Save important context** for future reference
- **Clear context windows** when starting new topics

**4. Output Quality Control**
- **Set quality standards** before you start
- **Use checklists** to validate outputs
- **Test incrementally** rather than all at once
- **Document what works** for future reference

**5. Cost and Resource Optimization**
- **Monitor AI usage** to control costs
- **Choose appropriate models** for each task
- **Cache results** when possible
- **Optimize prompts** to reduce token usage

### Slide 5: Troubleshooting Common Implementation Issues (3 minutes)
**Time:** 3 minutes
**Key Points:**

**Common Problems and Solutions:**

**Problem 1: "AI Output Isn't What I Expected"**
- **Solution:** Check your prompt clarity and specificity
- **Try:** Breaking down complex requests into smaller parts
- **Use:** Examples and constraints to guide AI

**Problem 2: "Outputs Are Inconsistent"**
- **Solution:** Use few-shot learning with consistent examples
- **Try:** Setting more specific constraints and requirements
- **Use:** Templates to standardize output format

**Problem 3: "AI Doesn't Understand My Domain"**
- **Solution:** Provide domain-specific context and terminology
- **Try:** Role-playing with expert personas
- **Use:** Examples from your specific field

**Problem 4: "Outputs Are Too Generic"**
- **Solution:** Add specific requirements and constraints
- **Try:** Iterative refinement to build on initial outputs
- **Use:** Context about your specific users and needs

**Problem 5: "It's Not Working With My Tools"**
- **Solution:** Check integration requirements and APIs
- **Try:** Testing with simpler examples first
- **Use:** Documentation and troubleshooting guides

### Slide 6: What We'll Practice Today (2 minutes)
**Time:** 2 minutes
**Key Points:**
- We'll practice advanced prompting techniques on real problems
- You'll build something functional using your chosen tools
- We'll test outputs and iterate based on results
- Focus on practical implementation, not perfection

**Success Criteria:**
- You can use at least 2 advanced prompting techniques
- You've built something functional with AI assistance
- You can test outputs against requirements
- You know when to iterate vs. try different approaches

---

## Part 2: Hands-On Advanced Implementation Activity (20-30 minutes)

### Activity Setup (3 minutes)
**Instructions:**
- We'll work in breakout rooms of 3-4 people
- Each person will work on their capstone project
- Practice advanced prompting techniques
- Test outputs and iterate based on results
- We'll reconvene to share what we built

### Activity Part 1: Advanced Prompting Practice (10 minutes)

#### Individual Work - Choose Your Technique:
**Option A: Chain-of-Thought Prompting**
- Pick a complex aspect of your capstone project
- Use chain-of-thought to break it down step-by-step
- Example: "Think through the user authentication flow step by step. What are the main components? What could go wrong? How should we handle edge cases?"

**Option B: Role-Playing Technique**
- Choose a specific role relevant to your project
- Have AI approach your problem from that perspective
- Example: "You are a UX designer specializing in accessibility. How would you design the user interface for my project to ensure it works for users with disabilities?"

**Option C: Few-Shot Learning**
- Create 2-3 examples of what you want
- Use AI to generate more content in the same style
- Example: "Here are 3 user stories for my project. Write 2 more user stories in the same format..."

#### Prompting Practice Process:
1. **Choose your technique** based on your project needs
2. **Craft your advanced prompt** using the techniques we discussed
3. **Test the prompt** with your chosen AI tool
4. **Evaluate the output** against your requirements
5. **Iterate or try different approach** based on results

### Activity Part 2: Build Something Functional (12 minutes)

#### Implementation Challenge:
**Build a functional component of your capstone project using AI assistance.**

#### Implementation Process:

**Step 1: Define Success Criteria (2 minutes)**
- What specifically will you build?
- How will you know it's working?
- What are your acceptance criteria?

**Step 2: Use Advanced Prompting (5 minutes)**
- Apply the prompting technique you practiced
- Generate the functional component
- Use iterative refinement if needed

**Step 3: Test and Validate (3 minutes)**
- Test your output against success criteria
- Try it with example data or scenarios
- Identify what works and what doesn't

**Step 4: Iterate or Redesign (2 minutes)**
- If close: Iterate to improve
- If far off: Try different approach
- Document what you learned

#### Implementation Examples by Role:

**For Product Managers:**
- Generate a product requirements document
- Create user acceptance criteria
- Build a feature prioritization framework

**For Designers:**
- Generate wireframes or mockups
- Create user journey maps
- Build design system components

**For Project Managers:**
- Create project timelines
- Generate risk assessment frameworks
- Build status reporting templates

### Activity Part 3: Peer Review and Feedback (5 minutes)

#### Group Sharing Process:
- Each person shares what they built (1 minute)
- Group provides feedback on approach and results
- Discuss what worked and what didn't
- Share prompting techniques that were effective

#### Feedback Framework:
**What worked well:**
- Prompting techniques that were effective
- Output quality and relevance
- Testing and validation approach

**What could be improved:**
- Prompting strategies to try
- Testing approaches to consider
- Alternative implementations to explore

### Facilitator Support During Activity
- Circulate through breakout rooms
- Help with advanced prompting techniques
- Assist with troubleshooting implementation issues
- Point out good examples of quality assessment
- Help groups evaluate when to iterate vs. redesign

---

## Part 3: Q&A and Reflection (10 minutes)

### Quick Share-Out (3 minutes)
**Ask each group:** What was one thing you built today that you're excited about?

### Q&A Session (5 minutes)
**Common questions to be prepared for:**
- "How do I know when my AI output is good enough?"
- "What's the best way to test complex AI-generated features?"
- "How can I optimize my prompts for better results?"
- "When should I stop iterating and try a completely different approach?"
- "How do I handle AI outputs that are close but not quite right?"

**Thoughtful Responses:**
- **Good enough:** When it meets your defined criteria and serves users well
- **Testing:** Start simple, test incrementally, use real examples
- **Optimization:** Track what works, build templates, share patterns
- **Stop iterating:** When you're not making progress or outputs are fundamentally wrong
- **Close outputs:** Try iterative refinement or constraint adjustments

### Reflection Questions (2 minutes)
**Ask participants to think about:**
1. What advanced prompting technique was most effective for your project?
2. How did testing your outputs change your approach?
3. What will you build next with these new techniques?

### Closing & Next Steps
**Time:** 1 minute
**Key Points:**
- Great work today! You're now building functional AI-assisted projects
- This week's video will cover optimization strategies
- Office hours will help you build more complex features
- Your assignment is to create a working prototype using advanced techniques

---

## Materials Needed

### For Facilitators:
- [ ] Presentation slides (6 slides, ~15-20 minutes)
- [ ] Activity instructions printed/available
- [ ] Timer for breakout rooms
- [ ] Examples of advanced prompting techniques
- [ ] Quality assessment checklists

### For Participants:
- [ ] Access to their chosen AI tools
- [ ] Capstone project materials
- [ ] Note-taking materials
- [ ] Testing scenarios or example data

### Visual Aids:
- [ ] Advanced prompting techniques overview
- [ ] Quality assessment framework diagram
- [ ] Workflow optimization strategies
- [ ] Troubleshooting decision tree
- [ ] Before/after prompt examples

---

## Success Indicators

### During the Session:
- Participants are using advanced prompting techniques effectively
- They're building functional components of their projects
- Groups are testing outputs and iterating based on results
- No one is stuck on basic implementation issues

### After the Session:
- Participants can explain advanced prompting techniques
- They've built something functional with AI assistance
- They understand how to assess output quality
- They know when to iterate vs. try different approaches

---

## Backup Plans

### If Technology Fails:
- Have offline advanced prompting examples ready
- Use printed templates for quality assessment
- Focus on conceptual understanding and planning

### If Time Runs Short:
- Skip the peer review and focus on building
- Reduce individual work time
- Provide implementation templates as homework

### If Participants Are Struggling:
- Provide more specific implementation examples
- Have starter prompts ready for common scenarios
- Pair up people who are struggling with those who are succeeding

---

## Connection to Other Week 4 Components

### Links to Recorded Video:
- This session introduces advanced techniques
- The video will cover optimization strategies
- Participants will understand implementation before optimization

### Links to Office Hours:
- Participants can get help with complex implementations
- Hands-on building support for advanced features
- Individual troubleshooting for specific issues

### Links to Assignment:
- Participants will have advanced techniques to apply
- They'll understand how to test and validate outputs
- They'll be ready to build working prototypes

---

## Assessment Integration

### Formative Assessment:
- **Exit tickets:** What did you build? What technique worked best? What will you try next?
- **Observation:** Are participants using advanced techniques effectively?
- **Group discussions:** Are they testing outputs and iterating appropriately?

### Connection to Learning Outcomes:
- **Understand:** Can they explain advanced prompting techniques?
- **Apply:** Can they use these techniques effectively?
- **Create:** Did they build something functional?
- **Evaluate:** Can they assess output quality and decide when to iterate?

This session transforms participants from AI experimenters into practical AI builders, giving them the skills to create functional, tested implementations of their ideas.
