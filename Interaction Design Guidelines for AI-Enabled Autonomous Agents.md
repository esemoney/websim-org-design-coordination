
source: https://websim.ai/c/bYlTUcmufPVFPIcz4

- [4.601 Media, Culture and AI Course Home](https://mcoai.dplmi.mit.edu/course-4.601/)
- [Overview of Case Studies](https://mcoai.dplmi.mit.edu/course-4.601/case-studies-detailed-analysis-reports/c2-interaction-design-guidelines-with-mini-case-studies-diagrams-altdescriptions/?overview)
- C2 Interaction Design Guidelines with Case Studies

# Interaction Design Guidelines for AI-Enabled Autonomous Agents

As artificial intelligences and autonomous systems become increasingly sophisticated and prevalent across domains, it is critical that designers and developers follow robust interaction design principles to ensure these agents are usable, understandable, and beneficial to the humans who engage with them. This detailed report presents key guidelines for crafting effective interfaces and interaction patterns for AI-enabled agents, illustrated with mini case studies and instructive diagrams.

## 1. Clearly Communicate Agent Capabilities and Limitations

Autonomous agents should provide transparency about what they can and cannot do to help users develop accurate mental models. Avoid ambiguous representations that may lead users to over-attribute intelligence.

![](https://mcoai.dplmi.mit.edu/course-4.601/case-studies-detailed-analysis-reports/clear-capabilities-diagram.svg)

Diagram illustrating how an AI assistant could list its specific skills and limitations upfront to calibrate user expectations.

### Case Study: Personal Finance AI Coach

A financial guidance app with an AI component allows users to verbally describe their goals and spending habits. The AI analyzes this input to provide customized advice, but begins each session by explaining the specific areas it can advise on (budgeting, saving, investing) while specifying that it cannot make decisions on the user's behalf or access their private accounts without permission.

## 2. Provide Seamless Corrections and Graceful Failure Modes

Even advanced AIs will sometimes make mistakes or encounter edge cases they cannot handle. The interface should make it easy for users to correct errors, provide feedback, and exit gracefully when the AI reaches the limits of its abilities.

![](https://mcoai.dplmi.mit.edu/course-4.601/case-studies-detailed-analysis-reports/error-correction-flow.svg)

Flow diagram showing how an AI chat interface could provide an obvious "thumbs down" button on each response, allowing the user to indicate an error and prompt the AI to try again or connect them to a human representative if the issue persists.

### Case Study: AI-Powered Tech Support Agent

An AI customer support chat bot attempts to diagnose issues and walk users through troubleshooting steps. When the bot suggests an irrelevant resolution, the user can click "That didn't help" to have the AI try a different approach. After 2-3 failed attempts, the bot automatically routes the conversation to a human agent, passing along the interaction history to avoid repetition.

## 3. Maintain Consistency Across Interaction Contexts

As AI agents are embedded into more interfaces and devices, prioritize consistency in their functionality, language, and persona traits. This reduces cognitive overhead and allows users to apply their knowledge across contexts.

![](https://mcoai.dplmi.mit.edu/course-4.601/case-studies-detailed-analysis-reports/cross-platform-consistency.png)

Diagram showing how an AI agent named AVA manifests with the same essential capabilities and personality attributes whether the user is interacting via a mobile app, smart speaker, or automobile infotainment system.

### Case Study: Multi-Modal Smart Home Assistant

A smart home AI assistant is accessible through a mobile app, voice-controlled speaker, and the screens on various appliances like the refrigerator or oven. While each modality is uniquely suited to specific tasks, the core functionality (playing music, setting timers, answering questions) and the friendly, congenial tone remains the same across all touchpoints.

## 4. Adapt to User Knowledge and Provide Progressive Disclosure

Agents should tailor their communication style and degree of hand-holding to each user's familiarity with the system. Provide upfront tutorials for novices, but allow expert users to access advanced functions and skip explanations.

![](https://mcoai.dplmi.mit.edu/course-4.601/case-studies-detailed-analysis-reports/progressive-disclosure-ui.png)

Wireframe of an AI photo editing tool showing how tips and feature call-outs are prominent in the new user experience but can be hidden as the user develops proficiency.

### Case Study: AI-Assisted Drawing and Drafting Tool

A diagramming app leverages AI to predict and auto-complete the user's sketches. First-time users are greeted with a guided tour pointing out the AI assistance features. As they manipulate the AI suggestions, tooltips explain how to lock, reject or customize the AI output. Over time, the system notices which features they use often and adapts the UI to make these functions more prominent while hiding the intro-level guidance. Power users can access an advanced mode that exposes more granular AI controls.

## 5. Preserve User Autonomy and Provide Opt-Out Mechanisms

While AI can add convenience and power, users should ultimately remain in control. Provide clear affordances for adjusting AI involvement, automating frequent tasks, or turning off proactive suggestions as desired.

![](https://mcoai.dplmi.mit.edu/course-4.601/case-studies-detailed-analysis-reports/ai-control-panel.svg)

An AI writing assistant displays a prominent control panel allowing the user to determine how aggressively it makes autocomplete suggestions and whether its grammar and phrasing recommendations are applied automatically or require manual approval.

### Case Study: AI Email Composer and Assistant

An AI-powered email client helps the user compose messages by suggesting wording, predicting responses, and proactively surfacing relevant files to attach or appointments to reference. While this functionality is on by default, an ever-present "AI assistance" toggle in the compose window allows the user to quickly disable these features if they would prefer to author the content entirely on their own. Over time, the system learns their preferences (e.g. allowing AI to autocomplete scheduling requests but not sensitive or personal messages) and adapts its default behavior accordingly.

## Conclusion

As this report demonstrates, deliberate and human-centered interaction design is essential for AI-enabled autonomous agents to reach their potential and deliver genuine value to users. By following the guidelines distilled here and learning from both exemplary and cautionary case studies, designers and product teams can craft agent experiences that are ethical, empowering and cognitively sustainable. While much work remains to be done in this burgeoning field, a focus on transparency, consistency, adaptivity, and user control provides a solid foundation to build upon.

## Further Reading and References

- Amershi, S., Weld, D., Vorvoreanu, M., Fourney, A., Nushi, B., Collisson, P., ... & Teevan, J. (2019, May). Guidelines for human-AI interaction. In Proceedings of the 2019 CHI Conference on Human Factors in Computing Systems (pp. 1-13).
- Horvitz, E. (1999, May). Principles of mixed-initiative user interfaces. In Proceedings of the SIGCHI conference on Human Factors in Computing Systems (pp. 159-166).
- Khadpe, P., Krishna, R., Fei-Fei, L., Hancock, J. T., & Bernstein, M. S. (2020). Conceptual metaphors impact perceptions of human-AI collaboration. Proceedings of the ACM on Human-Computer Interaction, 4(CSCW2), 1-26.
- Yang, Q., Steinfeld, A., Rosé, C., & Zimmerman, J. (2020, April). Re-examining Whether, Why, and How Human-AI Interaction Is Uniquely Difficult to Design. In Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems (pp. 1-13).

---

## About the Author

Fei Ren is a researcher at the [MIT Media Lab](https://www.media.mit.edu/) investigating human-computer interaction (HCI) challenges and opportunities around artificial intelligence. Her work focuses on designing empowering interaction paradigms that allow non-expert users to understand and wield increasingly advanced AI systems while preserving their autonomy and privacy. She holds undergraduate and graduate degrees in Human Factors Engineering from Tsinghua University and a Master's of Science from the MIT Media Lab.

Copyright ©2023 MIT Dept. of Play Media & Imagination Lab (DPLMI). For more course materials, visit [DPLMI 4.601 Home](https://mcoai.dplmi.mit.edu/).