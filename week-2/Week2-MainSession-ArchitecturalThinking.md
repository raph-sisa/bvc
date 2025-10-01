# Week 2 Main Session: Architectural Thinking
## Duration: 60 minutes | Structure: 15-20 min teaching → 20-30 min activity → 10 min Q&A/reflection

### Learning Objectives (from LearningOutcomes.md)
**Cognitive:**
- **Understand:** Explain what software architecture means for AI-assisted projects
- **Analyze:** Break down a feature into components and their relationships
- **Compare:** Prototype vs. production approaches for the same project

**Practical:**
- **Apply:** Use AI to brainstorm and structure requirements for a feature
- **Create:** Write user stories with acceptance criteria for a small feature
- **Evaluate:** Assess whether a project calls for prototype or production approach

---

## Part 1: Teaching Presentation (15-20 minutes)

### Slide 1: Welcome Back & Week 1 Bridge (2 minutes)
**Time:** 2 minutes
**Key Points:**
- Welcome back! How did the app deconstruction assignment go?
- Today we're taking your analysis skills to the next level
- We're moving from understanding existing systems to designing new ones
- Structure: Learn → Practice → Reflect

**Quick Check-in:** Ask participants to share one insight from their app deconstruction that surprised them.

### Slide 2: What is Architectural Thinking? (4 minutes)
**Time:** 4 minutes
**Key Points:**
- **Architectural thinking = Systems thinking for technology projects**
- It's about understanding how pieces fit together before you start building
- **Non-developers can think architecturally too** - it's about planning and structure

**The Architect's Mindset:**
- **Think in components:** What are the main pieces?
- **Consider relationships:** How do pieces connect and interact?
- **Plan for scale:** What happens when this grows?
- **Anticipate problems:** What could go wrong?

**Real-World Analogy:**
- **Building a house:** You don't start with walls, you start with a blueprint
- **Planning a trip:** You don't just pack, you plan routes, accommodations, activities
- **Organizing an event:** You don't just send invites, you plan logistics, timing, resources

**Why This Matters for AI Projects:**
- AI tools can help with implementation, but you still need to think about structure
- Good architecture makes AI tools more effective
- Poor planning leads to AI-generated messes that are hard to fix

### Slide 3: The Three Pillars of Architectural Thinking (5 minutes)
**Time:** 5 minutes
**Key Points:**

**Pillar 1: Requirements Gathering**
- **Functional Requirements:** What should the system do?
- **Technical Requirements:** How should it perform?
- **User Requirements:** Who will use it and how?

**Pillar 2: Component Design**
- **Break down into pieces:** What are the main features/components?
- **Define interfaces:** How do pieces communicate?
- **Plan dependencies:** What needs to be built first?

**Pillar 3: Quality Considerations**
- **Performance:** How fast does it need to be?
- **Reliability:** How often can it fail?
- **Maintainability:** How easy is it to update?
- **Scalability:** How much can it grow?

**AI-Assisted Architectural Thinking:**
- Use AI to brainstorm requirements
- Ask AI to break down complex features
- Get AI to help identify edge cases
- Use AI to explore alternative approaches

### Slide 4: Prototype vs. Production Thinking (4 minutes)
**Time:** 4 minutes
**Key Points:**

**Prototype Approach:**
- **Goal:** Learn quickly, test assumptions, explore possibilities
- **Quality:** "Good enough" to answer key questions
- **Timeline:** Fast iteration, quick feedback
- **Tools:** AI-first, minimal setup, rapid development

**Production Approach:**
- **Goal:** Reliable, scalable, maintainable solution
- **Quality:** High standards, thorough testing, robust architecture
- **Timeline:** Careful planning, extensive testing
- **Tools:** Professional development practices, comprehensive setup

**The Decision Framework:**
**Ask these questions:**
1. **What's the risk if this fails?** (High risk → Production)
2. **How long will this be used?** (Long-term → Production)
3. **How many users will this have?** (Many users → Production)
4. **How often will this change?** (Frequent changes → Production)
5. **What's your timeline?** (Rush → Prototype, Time → Production)

**Real Examples:**
- **Prototype:** Internal tool for data analysis, proof-of-concept feature
- **Production:** Customer-facing feature, business-critical process
- **Hybrid:** Start with prototype, evolve to production

### Slide 5: AI as Your Architectural Partner (3 minutes)
**Time:** 3 minutes
**Key Points:**

**How AI Helps with Architectural Thinking:**
- **Requirement Brainstorming:** "What features might a project management tool need?"
- **Component Breakdown:** "How would you break down a user authentication system?"
- **Edge Case Identification:** "What could go wrong with this feature?"
- **Alternative Exploration:** "What are different ways to approach this problem?"

**The Right Questions to Ask AI:**
- **Instead of:** "Build me a website"
- **Ask:** "What are the main components of a small business website and how should they connect?"

- **Instead of:** "Create a mobile app"
- **Ask:** "How would you structure a habit-tracking mobile app? What are the key user journeys and technical components?"

**Context Engineering for Architecture:**
- **Role:** "You are a senior software architect with 10+ years experience"
- **Request:** Specific architectural questions about structure and components
- **Format:** Clear breakdown with sections for components, relationships, and considerations
- **Examples:** Similar systems or architectural patterns

### Slide 6: What We'll Practice Today (2 minutes)
**Time:** 2 minutes
**Key Points:**
- We'll practice architectural thinking with real project scenarios
- You'll use AI to help break down complex features
- We'll explore prototype vs. production decisions
- Focus on thinking like an architect, not coding like a developer

**Success Criteria:**
- You can break down a complex feature into components
- You can ask AI the right architectural questions
- You can make informed prototype vs. production decisions
- You feel confident planning technology projects

---

## Part 2: Hands-On Architectural Thinking Activity (20-30 minutes)

### Activity Setup (3 minutes)
**Instructions:**
- We'll work in breakout rooms of 3-4 people
- Each group will pick one project scenario
- Practice architectural thinking using AI assistance
- Share insights and get feedback from your group
- We'll reconvene to share discoveries

### Project Scenarios by Role

#### For Product Managers:
1. **Team Communication Tool:** Design a tool for remote team collaboration with messaging, file sharing, and project tracking
2. **Customer Feedback System:** Create a system for collecting, analyzing, and acting on customer feedback
3. **Content Management Platform:** Build a platform for creating, organizing, and publishing marketing content
4. **Analytics Dashboard:** Design a dashboard for tracking product metrics and user behavior

#### For Designers:
1. **Design System Tool:** Create a tool for managing and sharing design components across teams
2. **User Research Platform:** Build a platform for conducting user interviews, surveys, and usability testing
3. **Prototype Collaboration Tool:** Design a tool for sharing and collaborating on design prototypes
4. **Brand Asset Manager:** Create a system for organizing and distributing brand assets

#### For Project Managers:
1. **Project Portfolio Tracker:** Build a system for tracking multiple projects, resources, and timelines
2. **Risk Management Tool:** Create a tool for identifying, tracking, and mitigating project risks
3. **Team Performance Dashboard:** Design a dashboard for monitoring team productivity and project health
4. **Stakeholder Communication Hub:** Build a platform for managing stakeholder updates and communications

### Activity Process (17-25 minutes)

#### Step 1: Project Selection & Initial Analysis (5 minutes)
**Individual Work:**
- Pick one scenario relevant to your role
- Use AI to conduct initial architectural analysis
- Focus on understanding the problem and identifying main components

**AI Prompt Framework:**
```
You are a senior software architect with 10+ years of experience. Help me think through the architecture of [PROJECT NAME].

Please analyze:
1. **Core User Journeys:** What are the main ways users will interact with this system?
2. **Key Components:** What are the major features/components that need to be built?
3. **Data Requirements:** What data needs to be stored, processed, and displayed?
4. **Integration Points:** What external systems or services might this connect to?
5. **Technical Considerations:** What are the main technical challenges or requirements?

Structure your response with clear sections and provide specific examples for each area.
```

#### Step 2: Deep Dive Component Analysis (8 minutes)
**Individual Work:**
- Pick one component from your initial analysis
- Use AI to explore that component in detail
- Consider prototype vs. production approaches

**AI Prompt Framework:**
```
Focus specifically on the [COMPONENT NAME] from the [PROJECT NAME] system.

Provide detailed analysis including:
1. **User Interaction Flow:** Step-by-step how users interact with this component
2. **Technical Architecture:** What technical pieces are needed to build this?
3. **Data Flow:** How does data move through this component?
4. **Dependencies:** What other components or systems does this depend on?
5. **Prototype vs. Production:** How would you approach this differently for a prototype vs. production system?
6. **Potential Challenges:** What could go wrong or be difficult to implement?

Include specific examples and reasoning for your recommendations.
```

#### Step 3: Group Discussion & Peer Review (7-10 minutes)
**Group Work:**
- Share your architectural analysis with your group
- Get feedback on your component breakdown
- Discuss prototype vs. production decisions
- Help each other refine architectural thinking

**Discussion Prompts:**
- What components did you identify? Are there any we missed?
- How did you decide between prototype and production approaches?
- What questions did you ask AI that were most helpful?
- What challenges did you encounter in the architectural thinking process?

#### Step 4: Requirements Documentation (2 minutes)
**Individual Work:**
- Write 2-3 user stories for your chosen component
- Include acceptance criteria
- Consider both functional and non-functional requirements

**User Story Template:**
```
As a [user type], I want [functionality] so that [benefit].

Acceptance Criteria:
- [ ] [Specific, testable requirement]
- [ ] [Another specific requirement]
- [ ] [Performance or quality requirement]

Technical Considerations:
- [Architectural consideration]
- [Integration consideration]
```

### Facilitator Support During Activity
- Circulate through breakout rooms
- Help groups who are stuck on architectural concepts
- Point out good examples of architectural thinking
- Encourage participants to ask AI follow-up questions
- Help with prototype vs. production decision-making

---

## Part 3: Q&A and Reflection (10 minutes)

### Quick Share-Out (3 minutes)
**Ask each group:** What was one insight about architectural thinking that surprised you?

### Q&A Session (5 minutes)
**Common questions to be prepared for:**
- "How detailed should my architectural thinking be?"
- "When is it okay to skip architectural planning?"
- "How do I know if I'm over-engineering or under-engineering?"
- "What's the difference between architectural thinking and project planning?"
- "How can AI help with architectural decisions I don't understand?"

### Reflection Questions (2 minutes)
**Ask participants to think about:**
1. How does architectural thinking change how you approach technology projects?
2. What's one architectural question you want to explore further?
3. How might you apply this thinking to your current work projects?

### Closing & Next Steps
**Time:** 1 minute
**Key Points:**
- Great work today! You're now thinking like architects
- This week's video will cover tool selection frameworks
- Office hours will help you practice requirement gathering
- Your assignment is to apply architectural thinking to a real project

---

## Materials Needed

### For Facilitators:
- [ ] Presentation slides (6 slides, ~15-20 minutes)
- [ ] Activity instructions printed/available
- [ ] Timer for breakout rooms
- [ ] Backup project scenarios in case groups finish early
- [ ] Examples of good architectural questions for AI

### For Participants:
- [ ] Access to AI tools (ChatGPT, Claude, etc.)
- [ ] Note-taking materials
- [ ] Breakout room assignments (if virtual)
- [ ] Project scenario list

### Visual Aids:
- [ ] Three pillars of architectural thinking diagram
- [ ] Prototype vs. production decision tree
- [ ] Component breakdown examples
- [ ] User story template

---

## Success Indicators

### During the Session:
- Participants are asking sophisticated architectural questions of AI
- Groups are discussing component relationships and dependencies
- People are thinking about prototype vs. production trade-offs
- No one is completely lost or overwhelmed

### After the Session:
- Participants can explain what architectural thinking means
- They can break down a complex feature into components
- They understand the prototype vs. production decision framework
- They're excited to apply architectural thinking to their work

---

## Backup Plans

### If Technology Fails:
- Have architectural thinking exercises ready for offline work
- Use chat to share examples instead of breakout rooms
- Focus on conceptual understanding rather than AI interaction

### If Time Runs Short:
- Skip the deep dive component analysis
- Reduce group discussion time
- Focus on one architectural concept per group

### If Participants Are Struggling:
- Provide more specific architectural question examples
- Have a "starter" architectural analysis ready
- Pair up people who are struggling with those who are succeeding

---

## Connection to Other Week 2 Components

### Links to Recorded Video:
- This session covers the "what" and "why" of architectural thinking
- The video will cover the "how" of tool selection for different approaches
- Participants will be ready to choose appropriate tools after this session

### Links to Office Hours:
- Participants who need help with architectural concepts can get support
- Hands-on practice with requirement gathering templates
- Individual questions about prototype vs. production decisions

### Links to Assignment:
- Participants will have concrete architectural thinking skills to apply
- They'll understand how to break down complex projects
- They'll be ready to document requirements for their capstone projects

---

## Assessment Integration

### Formative Assessment:
- **Exit tickets:** What did you learn? What's still confusing? What will you try?
- **Observation:** Are participants asking good architectural questions?
- **Peer feedback:** Are they helping each other think through components?

### Connection to Learning Outcomes:
- **Understand:** Can they explain architectural thinking concepts?
- **Analyze:** Can they break down features into components?
- **Apply:** Can they use AI to help with architectural questions?
- **Evaluate:** Can they make prototype vs. production decisions?

This session transforms participants from AI tool users into AI-assisted system architects, preparing them for the practical implementation work in subsequent weeks.
