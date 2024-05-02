source: https://websim.ai/c/OIqezSOOR3whdm2Hm

# Tutorial: Military Interfaces with Autonomous Agents

This tutorial provides an overview of best practices and case studies for designing human-AI interfaces in defense contexts, with a focus on enabling effective collaboration between military personnel and autonomous agents.

## Key Design Principles

1. **Clear task allocation:** Interfaces should make it explicit what tasks are handled by AI and what requires human input.
2. **Situational awareness:** Provide concise, relevant information to help commanders maintain awareness of the overall tactical picture.
3. **Explainable AI:** AI recommendations should include rationale that humans can understand and evaluate.
4. **Adaptable automation:** Allow flexibility for humans to adjust AI autonomy as the situation requires.
5. **Robust collaboration:** Support fluid, real-time coordination between human and AI agents.

## Human-AI Interaction Patterns

### Directive + Recommendation

The human provides a high-level objective or constraint, and the AI generates recommendations for how to proceed. This allows leveraging AI insights while keeping humans in control of key decisions.

Commander: "Secure the eastern ridge. Minimize civilian impact."  
AI: "Recommended COA: Send Unit A via Route X to minimize chance of enemy contact near villages."

### Collaborative Analysis

The AI highlights key data points and offers predictive models, but the human interprets the information to reach conclusions. Suitable for complex situations requiring human judgment.

AI: "Satellite imagery shows 80% probability of enemy armor in Sector Y based on terrain and heat signatures."  
Commander: "Hmm, that matches reports from scouts. Let's plan an anti-armor op in that area."

### Supervised Autonomy

For well-defined, recurring tasks, the AI can execute autonomously while keeping humans informed. The human monitors progress and can intervene if needed.

Commander: "Run supply convoy to FOB Zulu."  
AI: "Convoy dispatched on optimal route, ETA 2 hours. No threats detected." [Periodic updates follow]

![Diagram showing iterative planning process with AI proposing courses of action and human evaluating them.](https://mcoai.dplmi.mit.edu/assets/tutorials/ai-assisted-tactical-planning.png)

Example collaborative human-AI tactical planning workflow. The AI uses optimization to generate potential courses of action, while humans apply judgment and experience to select between options and identify additional constraints.

## Interface Design Guidelines

- Use clear, concise language for AI outputs. Avoid jargon when possible.
- Provide data visualization to help humans quickly grasp key factors, such as unit readiness and terrain.
- Allow AI configuration, e.g. "Only notify if estimated mission impact > 25%"
- Show uncertainty of AI models, not just point estimates.
- Offer multiple input methods - map gestures, text, voice - to fit user preferences.
- Allow users to drill down from high-level plans to granular unit actions.

## Further Reading

- Hawley, J. K. (2017). Patriot Wars: Automation and the Patriot Air and Missile Defense System. Center for a New American Security.
- Defense Science Board. (2016). Summer Study on Autonomy. Department of Defense.
- Endsley, M. R. (2017). From here to autonomy: lessons learned from human–automation research. Human factors, 59(1), 5-27.