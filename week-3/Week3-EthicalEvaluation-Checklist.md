# Ethical Evaluation Checklist for AI Features
## A Practical Framework for Non-Developers

### Instructions
Use this checklist to evaluate any AI feature you're building or using. Complete all sections to get a comprehensive ethical assessment of your project.

---

## Project Information

**Project Name:** ________________________________

**Feature Being Evaluated:** ________________________________

**Evaluation Date:** ________________________________

**Evaluated By:** ________________________________

---

## Pillar 1: Bias and Fairness

### Assessment Questions:
- [ ] **1.1** Have you tested this feature with diverse user groups? (Different demographics, backgrounds, abilities)
- [ ] **1.2** Have you checked outputs for discriminatory patterns or unfair outcomes?
- [ ] **1.3** Have multiple people from different perspectives reviewed the design and implementation?
- [ ] **1.4** Is there a clear process for users to report bias or fairness issues?
- [ ] **1.5** Have you considered who might be excluded or disadvantaged by this feature?
- [ ] **1.6** Are you aware of potential biases in the training data or AI model?

### Evidence/Notes:
________________________________
________________________________
________________________________

### Action Items:
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Risk Level:
- [ ] Low - Strong practices in place
- [ ] Medium - Some concerns, needs attention
- [ ] High - Significant gaps, immediate action needed

---

## Pillar 2: Privacy and Data Protection

### Assessment Questions:
- [ ] **2.1** Have you clearly documented what data this feature collects?
- [ ] **2.2** Do you collect only the minimum data necessary for the feature to function?
- [ ] **2.3** Are you transparent with users about what data is collected and why?
- [ ] **2.4** Is user data stored and transmitted securely?
- [ ] **2.5** Can users easily access, download, and delete their data?
- [ ] **2.6** Do you have a clear privacy policy written in simple language?
- [ ] **2.7** Is data collection opt-in (not opt-out) wherever possible?

### Evidence/Notes:
________________________________
________________________________
________________________________

### Data Collection Inventory:
| Data Type | Why Needed | How Protected | User Control |
|-----------|------------|---------------|--------------|
| ________________________________ |
| ________________________________ |
| ________________________________ |

### Action Items:
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Risk Level:
- [ ] Low - Strong privacy protections
- [ ] Medium - Some concerns, needs improvement
- [ ] High - Significant privacy risks

---

## Pillar 3: Transparency and Explainability

### Assessment Questions:
- [ ] **3.1** Do users know when AI is involved in generating or influencing content?
- [ ] **3.2** Can you explain in simple terms how the AI makes decisions?
- [ ] **3.3** Are the limitations of the AI clearly communicated to users?
- [ ] **3.4** Can users get explanations for specific AI actions or recommendations?
- [ ] **3.5** Have you avoided misleading users about AI capabilities?
- [ ] **3.6** Is there clear labeling when content is AI-generated?

### Evidence/Notes:
________________________________
________________________________
________________________________

### Transparency Assessment:
**How users know AI is involved:**
________________________________

**How AI decisions are explained:**
________________________________

**What users can and can't understand:**
________________________________

### Action Items:
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Risk Level:
- [ ] Low - Excellent transparency
- [ ] Medium - Some opacity, needs clarity
- [ ] High - Major transparency issues

---

## Pillar 4: Accessibility and Inclusion

### Assessment Questions:
- [ ] **4.1** Does this feature work with screen readers and assistive technologies?
- [ ] **4.2** Have you tested with users who have visual, hearing, motor, or cognitive disabilities?
- [ ] **4.3** Does this work in different languages and cultural contexts?
- [ ] **4.4** Can people with limited technology access (older devices, slow internet) still use this?
- [ ] **4.5** Are there alternatives to AI-powered features for users who can't or don't want to use them?
- [ ] **4.6** Is text large enough, contrast sufficient, and navigation keyboard-accessible?

### Evidence/Notes:
________________________________
________________________________
________________________________

### Accessibility Testing:
| Accessibility Need | Tested? | Works? | Notes |
|-------------------|---------|--------|-------|
| Screen readers | [ ] | [ ] | ________________________________ |
| Keyboard navigation | [ ] | [ ] | ________________________________ |
| High contrast mode | [ ] | [ ] | ________________________________ |
| Mobile accessibility | [ ] | [ ] | ________________________________ |
| Slow internet | [ ] | [ ] | ________________________________ |

### Action Items:
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Risk Level:
- [ ] Low - Highly accessible
- [ ] Medium - Some barriers, needs work
- [ ] High - Major accessibility issues

---

## Pillar 5: Environmental Impact

### Assessment Questions:
- [ ] **5.1** Have you justified why AI is necessary for this feature?
- [ ] **5.2** Could simpler, less resource-intensive solutions work instead?
- [ ] **5.3** Have you optimized AI usage to reduce unnecessary calls?
- [ ] **5.4** Are you using an appropriately-sized model (not over-powered for the task)?
- [ ] **5.5** Do you cache results when possible to reduce repeated AI calls?
- [ ] **5.6** Do you regularly review whether AI is still necessary?

### Evidence/Notes:
________________________________
________________________________
________________________________

### AI Usage Analysis:
**Why AI is necessary:**
________________________________

**Optimization strategies in place:**
________________________________

**Estimated AI calls per day/month:**
________________________________

### Action Items:
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Risk Level:
- [ ] Low - Efficient, justified AI usage
- [ ] Medium - Some optimization possible
- [ ] High - Wasteful or unnecessary AI usage

---

## User Agency Assessment

### Agency Questions:
- [ ] **UA1** Do users know AI is involved in this feature?
- [ ] **UA2** Can users override or disagree with AI decisions?
- [ ] **UA3** Do users understand what the AI is doing?
- [ ] **UA4** Can AI actions be easily undone or reversed?
- [ ] **UA5** Is the level of AI automation appropriate for the stakes involved?
- [ ] **UA6** Do users give meaningful consent to AI involvement?

### Evidence/Notes:
________________________________
________________________________
________________________________

### User Agency Spectrum:
**Where does this feature fall?**
```
FULL AGENCY ←—————————————————————————————————→ NO AGENCY
User decides     AI suggests    AI decides    AI decides    User has no
everything       options        with review   automatically  control
                                               
                [Mark your feature's position with X]
```

### Justification for Agency Level:
________________________________
________________________________

### Action Items:
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Risk Level:
- [ ] Low - Appropriate user agency
- [ ] Medium - Some agency concerns
- [ ] High - Inappropriate removal of agency

---

## Overall Ethical Assessment

### Total Checklist Score:
**Items Checked:** _____ / 36

### Scoring Interpretation:
- **30-36:** ✅ Excellent - Strong ethical foundation
- **24-29:** ✅ Good - Solid with some areas for improvement
- **18-23:** ⚠️ Needs Work - Significant gaps to address
- **12-17:** ⚠️ High Risk - Major ethical concerns
- **Below 12:** ❌ Critical - Fundamental ethical issues

### Risk Summary by Pillar:
| Pillar | Risk Level | Priority Actions |
|--------|------------|------------------|
| Bias & Fairness | Low/Med/High | ________________________________ |
| Privacy & Data | Low/Med/High | ________________________________ |
| Transparency | Low/Med/High | ________________________________ |
| Accessibility | Low/Med/High | ________________________________ |
| Environmental | Low/Med/High | ________________________________ |
| User Agency | Low/Med/High | ________________________________ |

### Top 3 Ethical Strengths:
1. ________________________________
2. ________________________________
3. ________________________________

### Top 3 Ethical Concerns:
1. ________________________________
2. ________________________________
3. ________________________________

---

## Action Plan

### Immediate Actions (Do This Week):
**Priority:** High
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Short-term Actions (Do This Month):
**Priority:** Medium
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

### Long-term Actions (Ongoing):
**Priority:** Monitor and Improve
- [ ] ________________________________
- [ ] ________________________________
- [ ] ________________________________

---

## Case Study Examples

### Example 1: Email Writing Assistant

**Project:** AI tool that helps users write professional emails

**Ethical Assessment:**

**Bias & Fairness (5/6):**
- ✅ Tested with diverse writing styles
- ✅ Multiple perspectives in design
- ✅ Bias reporting process
- ❌ Limited testing with non-native English speakers
- **Action:** Add multilingual testing

**Privacy & Data (6/7):**
- ✅ Only collects email text for processing
- ✅ No storage of email content
- ✅ Clear privacy policy
- ✅ User control over data
- **Strength:** Strong privacy protections

**Transparency (6/6):**
- ✅ Clear AI involvement labels
- ✅ Shows what AI changed
- ✅ Explains suggestions
- **Strength:** Excellent transparency

**Accessibility (4/6):**
- ✅ Screen reader compatible
- ✅ Keyboard navigation
- ❌ Complex interface for cognitive disabilities
- ❌ No simplified mode
- **Action:** Add simplified mode

**Environmental (4/6):**
- ✅ Caches common suggestions
- ✅ Right-sized model
- ⚠️ Could reduce API calls further
- **Action:** Optimize caching

**User Agency (6/6):**
- ✅ Users review all suggestions
- ✅ Easy to accept/reject
- ✅ Can edit AI text
- **Strength:** Full user control

**Total Score: 31/37 - Excellent**

---

### Example 2: Content Recommendation System

**Project:** AI that recommends articles to users

**Ethical Assessment:**

**Bias & Fairness (3/6):**
- ✅ Some diversity testing
- ❌ No bias monitoring
- ❌ Limited perspectives in design
- ❌ No bias reporting process
- **Action:** Implement bias monitoring and reporting

**Privacy & Data (4/7):**
- ✅ Clear about data collection
- ⚠️ Collects more data than necessary
- ❌ Opt-out (not opt-in)
- ❌ Difficult to delete data
- **Action:** Minimize data collection, add easy deletion

**Transparency (2/6):**
- ⚠️ Vague "algorithm" language
- ❌ No explanation of recommendations
- ❌ Limitations not communicated
- **Action:** Add clear explanations and labels

**Accessibility (5/6):**
- ✅ Works with assistive tech
- ✅ Good keyboard navigation
- ✅ Mobile accessible
- **Strength:** Good accessibility

**Environmental (3/6):**
- ⚠️ Frequent unnecessary recalculations
- ⚠️ Large model when smaller would work
- **Action:** Optimize model size and caching

**User Agency (2/6):**
- ❌ No way to opt out of recommendations
- ❌ Can't explain why recommended
- ❌ Limited user control
- **Action:** Add controls and transparency

**Total Score: 19/37 - Needs Work**

---

## Reflection Questions

### Before Evaluation:
1. What ethical considerations are you most concerned about?
________________________________

2. What do you think are the strengths of your design?
________________________________

3. What areas might need improvement?
________________________________

### After Evaluation:
1. What surprised you about the evaluation results?
________________________________

2. Which pillar had the lowest score? Why?
________________________________

3. What's the most important action you can take this week?
________________________________

4. How has this evaluation changed your approach?
________________________________

### For Cohort Discussion:
1. What ethical consideration was most challenging to address?
________________________________

2. What techniques did you use to improve user agency?
________________________________

3. How can you help others with their ethical evaluations?
________________________________

---

## Resources for Improvement

### Bias and Fairness:
- Test with diverse user groups (different ages, backgrounds, abilities)
- Use AI to help identify potential biases in outputs
- Implement feedback mechanisms for users to report issues
- Regular audits of outcomes across different user groups

### Privacy and Data Protection:
- Follow "privacy by design" principles
- Use encryption for data storage and transmission
- Implement data minimization practices
- Provide clear, simple privacy controls

### Transparency and Explainability:
- Add clear labels when AI is involved
- Provide "Why?" buttons for AI decisions
- Create simple explanations of how AI works
- Be honest about limitations and uncertainties

### Accessibility and Inclusion:
- Test with screen readers (NVDA, JAWS, VoiceOver)
- Follow WCAG accessibility guidelines
- Provide text alternatives for visual content
- Test with keyboard-only navigation

### Environmental Impact:
- Cache results when possible
- Use appropriately-sized models
- Batch AI requests when feasible
- Regular review of AI necessity

### User Agency:
- Default to user control
- Provide clear override mechanisms
- Make AI involvement transparent
- Match automation level to stakes

---

## Next Steps

**After Completing This Checklist:**
1. Share your evaluation in cohort discussion
2. Prioritize action items based on risk levels
3. Get feedback from peers on your assessment
4. Implement immediate actions this week
5. Schedule regular re-evaluations (monthly)

**Remember:**
- Ethics is not a one-time checklist - it's an ongoing practice
- Perfect scores are rare - the goal is continuous improvement
- Getting feedback from diverse perspectives is crucial
- Building ethical AI is a learning journey for everyone

This checklist provides a comprehensive framework for evaluating and improving the ethical foundation of your AI projects.
