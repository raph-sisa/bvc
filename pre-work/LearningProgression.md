# Learning Progression Map
## Beyond Vibe Coding Workshop for Product Professionals

## Overview

This document maps the learning progression across the 5-week workshop, showing how concepts build from foundational to advanced, with clear dependencies and scaffolding strategies to support diverse experience levels.

## Knowledge Dependency Map

```
WEEK 1: FOUNDATION
├─ Transformer Architecture Basics
├─ Context Windows & Limitations
├─ Context Engineering Principles
├─ Security Considerations
├─ Augmentation vs. Automation Framework
└─ GitHub Basics (forking, committing, pushing)
    │
    ↓
WEEK 2: ARCHITECTURAL THINKING
├─ Requirement Gathering (depends on: Context Engineering)
├─ Software Architecture Principles (depends on: LLM Basics)
├─ Tool Selection Framework (depends on: Augmentation vs. Automation)
└─ Prototype vs. Production Mindset (depends on: Architectural Thinking)
    │
    ↓
WEEK 3: HUMAN-CENTERED DESIGN
├─ Design Thinking for AI (depends on: Requirement Gathering)
├─ Ethical Considerations (depends on: Augmentation vs. Automation)
├─ User Agency in AI Features (depends on: Design Thinking)
└─ Cross-Disciplinary Collaboration (depends on: GitHub Basics, Tool Selection)
    │
    ↓
WEEK 4: PRACTICAL IMPLEMENTATION
├─ Advanced Tool Usage (depends on: Tool Selection, Context Engineering)
├─ Code Review & Quality (depends on: GitHub Basics, Architectural Thinking)
├─ Optimization Strategies (depends on: Context Engineering, Design Thinking)
└─ Collaborative Coding (depends on: GitHub Basics, Cross-Disciplinary Collaboration)
    │
    ↓
WEEK 5: INTEGRATION & SYNTHESIS
├─ Capstone Project (depends on: ALL previous concepts)
├─ Continued Learning Pathways (depends on: Self-awareness of skill gaps)
└─ Community Building (depends on: Collaborative Coding, Peer Feedback)
```

## Concept Definitions by Level

### Foundational Concepts (Week 1)

#### 1. Transformer Architecture Basics
**Definition:** Understanding how Large Language Models (LLMs) work at a high level, including the transformer architecture that enables them to process and generate text.

**Key Learning Points:**
- LLMs are prediction machines, not knowledge databases
- They work by predicting the most likely next token based on patterns
- Training data influences outputs but doesn't mean they "know" facts
- No real-time internet access (unless explicitly integrated)

**Why It's Foundational:** 
Understanding how LLMs work helps participants set realistic expectations, recognize limitations, and debug issues when outputs are unexpected.

**Success Indicator:** 
Participant can explain why an LLM might hallucinate or give inconsistent answers.

---

#### 2. Context Windows & Limitations
**Definition:** The finite amount of text an LLM can "remember" or process in a single conversation, measured in tokens.

**Key Learning Points:**
- Context windows have size limits (e.g., 128k tokens for Claude, varies by model)
- Earlier conversation content may be "forgotten" as window fills
- Tokens ≠ words (roughly 1 token = 3-4 characters)
- Larger contexts = slower responses and higher costs

**Why It's Foundational:** 
Participants need to understand why providing too much or too little context affects output quality.

**Success Indicator:** 
Participant can explain when to start a new conversation vs. continue an existing one.

---

#### 3. Context Engineering Principles
**Definition:** The practice of structuring prompts and providing relevant information to get optimal outputs from AI tools.

**Key Learning Points:**
- Be specific about desired format, tone, and constraints
- Provide examples when possible (few-shot prompting)
- Break complex tasks into smaller steps
- Iterate and refine based on outputs

**Why It's Foundational:** 
This is the core skill for effective AI collaboration—knowing how to communicate with AI tools.

**Success Indicator:** 
Participant can take a vague prompt and rewrite it with better context to get improved results.

---

#### 4. Security Considerations
**Definition:** Understanding risks and best practices when working with AI tools, especially regarding sensitive data.

**Key Learning Points:**
- Don't input proprietary code, passwords, or PII into public AI tools
- Understand data retention policies of different tools
- Be aware of training data usage policies
- Consider on-premise or enterprise versions for sensitive work

**Why It's Foundational:** 
Prevents costly mistakes and builds trust with teams/employers about responsible AI usage.

**Success Indicator:** 
Participant can identify when NOT to use a public AI tool for a given task.

---

#### 5. Augmentation vs. Automation Framework
**Definition:** A decision-making framework for determining when to let AI handle tasks fully vs. when to maintain human oversight.

**Key Learning Points:**
- Automation: Repeatable, low-risk, easily verifiable tasks
- Augmentation: Creative, high-stakes, novel problems requiring judgment
- The spectrum between these extremes
- How to set up appropriate guardrails for each approach

**Why It's Foundational:** 
Helps participants make informed decisions about when to trust AI and when to intervene.

**Success Indicator:** 
Participant can categorize their own work tasks on the augmentation-automation spectrum.

---

#### 6. GitHub Basics
**Definition:** Fundamental version control concepts and operations needed for collaborative coding.

**Key Learning Points:**
- What Git and GitHub are and why they matter
- Forking repositories to create your own copy
- Committing changes to save progress
- Pushing changes to share with others
- Basic navigation of GitHub interface

**Why It's Foundational:** 
GitHub is the standard for code collaboration; participants need this for workshop exercises and future AI-assisted development.

**Success Indicator:** 
Participant can fork a repo, make a change, commit it, and push successfully.

---

### Intermediate Concepts (Week 2)

#### 1. Architectural Thinking
**Definition:** The ability to think about software systems holistically, considering structure, components, and how they interact.

**Dependencies:** LLM Basics, Context Engineering

**Key Learning Points:**
- Asking "architect-level" questions to AI (How should this be structured?)
- Understanding component separation and dependencies
- Thinking about data flow and state management
- Considering scalability and maintainability

**Why It's Intermediate:** 
Requires understanding of how AI can help with technical decisions, building on context engineering skills.

**Success Indicator:** 
Participant can prompt an AI to generate a system architecture diagram with appropriate components.

---

#### 2. Requirement Gathering Techniques
**Definition:** Methods for collecting, documenting, and refining what needs to be built before writing code.

**Dependencies:** Context Engineering, Augmentation vs. Automation

**Key Learning Points:**
- User stories and acceptance criteria
- Edge case identification
- Technical vs. functional requirements
- Using AI to help brainstorm and refine requirements

**Why It's Intermediate:** 
Builds on context engineering by applying it to a specific workflow (pre-development planning).

**Success Indicator:** 
Participant can work with AI to generate comprehensive requirements for a feature.

---

#### 3. Tool Selection Framework
**Definition:** A structured approach to choosing the right AI tool for different use cases.

**Dependencies:** Augmentation vs. Automation Framework, LLM Basics

**Key Learning Points:**
- Chat tools (ChatGPT, Claude) for ideation and drafting
- No-code platforms (Lovable, Bolt, Replit) for rapid prototyping
- IDE tools (Cursor, Windsurf) for more control and integration
- CLI tools (Aider, Claude Code) for advanced workflows
- When to use each type of tool

**Why It's Intermediate:** 
Requires understanding of multiple tools' capabilities and how they map to different work scenarios.

**Success Indicator:** 
Participant can recommend appropriate tools for 3 different project scenarios.

---

#### 4. Prototype vs. Production Considerations
**Definition:** Understanding the trade-offs between building quickly for validation vs. building for long-term sustainability.

**Dependencies:** Architectural Thinking, Tool Selection

**Key Learning Points:**
- When "good enough" is appropriate (prototypes)
- When to invest in quality, testing, and documentation (production)
- How AI-generated code fits into each context
- Technical debt implications

**Why It's Intermediate:** 
Requires judgment about project goals and the appropriate level of polish for different stages.

**Success Indicator:** 
Participant can explain when to accept AI-generated code as-is vs. when to refactor it.

---

### Advanced Concepts (Weeks 3-4)

#### 1. Design Thinking for AI
**Definition:** Applying human-centered design principles when building with AI tools.

**Dependencies:** Requirement Gathering, Architectural Thinking

**Key Learning Points:**
- Empathy mapping for AI-enhanced features
- Designing for user agency (not replacing user decision-making)
- Transparency about AI involvement
- Iterative prototyping and testing with real users

**Why It's Advanced:** 
Requires synthesizing technical knowledge with human-centered design philosophy.

**Success Indicator:** 
Participant can critique an AI feature for its user-centeredness and suggest improvements.

---

#### 2. Ethical AI Usage
**Definition:** Considering moral implications, bias, fairness, and societal impact when building with AI.

**Dependencies:** Augmentation vs. Automation, Design Thinking

**Key Learning Points:**
- Identifying potential bias in AI outputs
- Considering accessibility and inclusion
- Transparency and user consent
- Environmental impact of AI usage
- Real-world case studies of ethical challenges

**Why It's Advanced:** 
Requires critical thinking and awareness of broader implications beyond immediate functionality.

**Success Indicator:** 
Participant can identify 3 ethical considerations for a given AI implementation.

---

#### 3. Advanced GitHub Collaboration
**Definition:** More sophisticated version control practices for team-based development.

**Dependencies:** GitHub Basics, Cross-Disciplinary Collaboration

**Key Learning Points:**
- Branching strategies for collaborative work
- Pull requests and code review workflows
- Merge conflict resolution
- GitHub Issues for project management
- Documentation best practices

**Why It's Advanced:** 
Builds on basic Git knowledge with team coordination and conflict resolution skills.

**Success Indicator:** 
Participant can create a branch, open a pull request, and incorporate feedback.

---

#### 4. Quality Assessment & Testing
**Definition:** Evaluating AI-generated outputs to ensure they work as intended and meet requirements, without needing to understand code line-by-line.

**Dependencies:** Architectural Thinking, Requirement Gathering, Security Considerations

**Key Learning Points:**
- Testing outputs against requirements (does it do what I asked?)
- Identifying when something doesn't work as expected
- Asking AI to explain what the code does (understanding at a functional level)
- When to trust AI outputs vs. when to verify extensively
- Using AI to help improve AI-generated outputs (iterative refinement)
- Recognizing security red flags (even without coding knowledge)

**Why It's Advanced:** 
Requires judgment about quality, synthesis of requirements and testing, and knowing when "good enough" is actually good enough.

**Success Indicator:** 
Participant can test an AI-generated feature, identify that something isn't working right, and work with AI to fix it.

---

#### 5. Optimization Strategies
**Definition:** Techniques for improving AI tool effectiveness, code quality, and workflow efficiency.

**Dependencies:** Context Engineering, Tool Selection, Architectural Thinking

**Key Learning Points:**
- Advanced prompting techniques (chain-of-thought, role-playing)
- Workflow automation with AI tools
- Performance optimization for AI-generated code
- Iterative refinement strategies

**Why It's Advanced:** 
Requires mastery of foundational concepts plus experimental mindset to discover what works best.

**Success Indicator:** 
Participant can demonstrate 2-3 optimization techniques they've discovered through practice.

---

## Scaffolding Strategy: Building Complexity Gradually

### Week 1: Confidence Building Through Familiarity
**Approach:** Start with what participants already know (chat tools) and build foundational understanding.

**Scaffolding Activities:**
1. **Guided Demos:** Instructor demonstrates concepts live with participant input
2. **Paired Exploration:** Participants work in pairs to reduce intimidation
3. **Low-Stakes Experimentation:** No "wrong answers" in initial exercises
4. **Vocabulary Building:** Introduce technical terms with plain language explanations

**Complexity Level:** ★☆☆☆☆
- Single-step tasks
- Clear right/wrong answers
- Instructor-led with heavy guidance

---

### Week 2: Applying Frameworks to Familiar Domains
**Approach:** Use participants' existing domain knowledge (product/design/project work) as the context for learning technical concepts.

**Scaffolding Activities:**
1. **Role-Specific Examples:** PMs see requirement gathering, designers see user stories
2. **Templates & Frameworks:** Provide structures to fill in rather than starting from scratch
3. **Peer Feedback:** Participants review each other's work with guiding questions
4. **Instructor Modeling:** Show thought process, not just final outputs

**Complexity Level:** ★★★☆☆
- Multi-step tasks with clear milestones
- Some ambiguity, multiple valid approaches
- Supported independence with available help

---

### Week 3: Synthesis and Critical Thinking
**Approach:** Combine technical skills with design and ethical thinking; introduce judgment calls.

**Scaffolding Activities:**
1. **Case Study Analysis:** Examine real-world examples of AI implementations
2. **Debate & Discussion:** No single "right answer," explore trade-offs
3. **Reflection Prompts:** Participants consider implications for their own work
4. **Cross-Role Collaboration:** Different perspectives on the same problem

**Complexity Level:** ★★★★☆
- Open-ended problems with multiple solutions
- Requires synthesis of multiple concepts
- Judgment and critique skills needed

---

### Week 4: Practical Application with Support
**Approach:** Hands-on building with AI tools and implementation with significant participant agency.

**Scaffolding Activities:**
1. **Starter Templates:** Pre-configured environments to reduce setup friction
2. **Troubleshooting Office Hours:** Real-time support for stuck participants
3. **Peer Feedback:** Learn from each other's approaches and tool choices
4. **Incremental Challenges:** Start simple, add complexity as confidence grows
5. **Testing Frameworks:** Simple ways to verify "does this work?"

**Complexity Level:** ★★★★★
- Real-world messy problems
- Troubleshooting and iteration required
- High autonomy with available support
- Focus on outcomes, not understanding every line of code

---

### Week 5: Independent Application
**Approach:** Participants work on self-directed projects that apply all concepts.

**Scaffolding Activities:**
1. **Capstone Project Choice:** Participants select projects relevant to their work
2. **Peer Accountability:** Share progress and blockers with peers
3. **Just-in-Time Support:** Office hours for specific questions
4. **Celebration & Reflection:** Recognize achievements and learning journey

**Complexity Level:** ★★★★★
- Self-directed work on real problems
- Minimal scaffolding, participant-driven
- Focus on continued learning habits

---

## Knowledge Checkpoints

### Week 1 → Week 2 Checkpoint
**Gate Question:** "Can you explain how context windows affect the quality of AI responses, and demonstrate better context engineering?"

**Assessment Methods:**
- Self-reflection in discussion space
- Optional worksheet completion shows understanding
- GitHub setup completion (for those new to it)

**Support for Those Not Ready:**
- Recorded video review
- Office hours catch-up session
- Peer study groups

---

### Week 2 → Week 3 Checkpoint
**Gate Question:** "Can you gather requirements for a small feature and select appropriate tools to build it?"

**Assessment Methods:**
- Requirement gathering assignment submission
- Participation in discussion about tool selection
- Peer feedback on requirements docs

**Support for Those Not Ready:**
- Template review sessions
- One-on-one office hours
- Simplified example walkthroughs

---

### Week 3 → Week 4 Checkpoint
**Gate Question:** "Can you identify ethical considerations in an AI implementation and explain how human-centered design applies?"

**Assessment Methods:**
- Case study analysis completion
- Discussion participation on ethical scenarios
- Design thinking framework application

**Support for Those Not Ready:**
- Additional case study resources
- Small group discussions
- Extended office hours support

---

### Week 4 → Week 5 Checkpoint
**Gate Question:** "Can you use AI tools to build something functional, test that it works, and iterate to improve it?"

**Assessment Methods:**
- Demonstration of a working prototype or feature (any scale)
- Explanation of how they tested and verified it works
- Evidence of iterative refinement (showing before/after prompts)
- Peer feedback on project approach and tool selection

**Support for Those Not Ready:**
- Extended office hours for hands-on tool support
- Simplified capstone project options (smaller scope)
- Paired collaboration with more experienced participants
- Focus on one tool they're most comfortable with

---

### Week 5 Completion Checkpoint
**Gate Question:** "Can you independently plan and execute an AI-assisted project from concept to implementation?"

**Assessment Methods:**
- Capstone project completion (at any scale)
- Reflection on learning journey
- Articulation of next learning steps

**Success Metrics:**
- Demonstrates understanding of all foundational concepts
- Can apply at least 3 intermediate concepts to real work
- Shows awareness of advanced considerations (ethics, quality, collaboration)

---

## Differentiation for Experience Levels

### For Beginners (30% of participants)
**Characteristics:** Primarily chat tool users, limited technical background

**Scaffolding Approach:**
- Extra foundational materials before Week 1
- Paired with intermediate participants for peer support
- Optional "GitHub 101" pre-session
- Focus on one tool in depth rather than many tools broadly

**Success Criteria:**
- Comfortable with chat tools and basic context engineering
- Completed GitHub basics (forked repo, made a commit)
- Can apply augmentation vs. automation framework to their work
- Successfully built something small using an AI tool (any scale - even a simple prototype)

---

### For Intermediate Participants (50% of participants)
**Characteristics:** Some exposure to multiple tools, looking to deepen understanding

**Scaffolding Approach:**
- Standard progression through all weeks
- Opportunities to experiment with new tools
- Encouraged to support beginners (teaching reinforces learning)
- Focus on workflow optimization and tool selection

**Success Criteria:**
- Confident with 2-3 different AI tool types
- Applied architectural thinking to a project
- Can test and verify AI-generated outputs work as expected
- Active in peer collaboration and feedback

---

### For Advanced Participants (20% of participants)
**Characteristics:** Experienced with multiple tools, seeking optimization and advanced techniques

**Scaffolding Approach:**
- Optional advanced extensions for each week
- Peer teaching opportunities (office hours support)
- Focus on optimization, ethics, and edge cases
- Encouraged to experiment beyond workshop materials

**Success Criteria:**
- Demonstrated advanced prompting techniques
- Led or supported peer learning
- Tackled complex capstone project
- Articulated continued learning plan beyond workshop

---

## Integration Across Weeks

### Horizontal Integration (Within Each Week)
Each week integrates three formats:
1. **Main Session:** Introduce concepts with demonstrations
2. **Recorded Video:** Provide frameworks and decision tools
3. **Office Hours:** Hands-on practice and troubleshooting

**Integration Strategy:**
- Main session concepts are referenced in recorded video
- Recorded video tools are practiced in office hours
- Office hours surface questions that inform next week's main session

---

### Vertical Integration (Across Weeks)
Each week explicitly builds on previous weeks:

**Week 1 → Week 2:**
- Context engineering principles apply to requirement gathering
- Augmentation vs. automation informs tool selection decisions

**Week 2 → Week 3:**
- Requirement gathering feeds into design thinking
- Architectural thinking considers ethical implications

**Week 3 → Week 4:**
- Design principles guide implementation decisions
- Ethical considerations inform code review criteria

**Week 4 → Week 5:**
- All practical skills combine in capstone project
- Reflection on learning journey identifies next steps

---

## Continuous Learning Mindset

Throughout all weeks, the workshop emphasizes:

1. **Experimentation:** AI tools are rapidly evolving; participants should try new approaches
2. **Iteration:** First attempts won't be perfect; refinement is expected
3. **Community:** Peer learning and support accelerates progress
4. **Reflection:** Regular check-ins on what's working and what needs adjustment
5. **Application:** Immediate workplace application reinforces learning

**Key Message:** This workshop provides a foundation, but mastery comes from continued practice and exploration beyond the 5 weeks.

---

## Conclusion

This learning progression map ensures that:
- ✅ Concepts build logically from foundational to advanced
- ✅ Dependencies are clear and prerequisites are met before new concepts
- ✅ Scaffolding supports diverse experience levels
- ✅ Knowledge checkpoints prevent participants from falling behind
- ✅ Integration across weeks creates coherent learning journey
- ✅ The workshop cultivates continued learning habits beyond its conclusion

The progression balances structure with flexibility, ensuring all participants can succeed while providing opportunities for advanced learners to dive deeper.

