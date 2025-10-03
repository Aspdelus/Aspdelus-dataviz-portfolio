| [home page](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/) | [Visualizing Government Debt](dataviz-examples) | [Critique and redesign (MakeoverMonday)](protein-viz) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards

Building on the initial sketches from Part I, I developed wireframes and storyboards for the bridge coating deterioration prediction story. Below is the Shorthand Link:
| [Shorthand](https://preview.shorthand.com/Nn0M5l73Tah4OHjV)


The two key visualizations from Part I serve as anchor points:
- **Interactive Pennsylvania Map**: Shows current bridge coating conditions with hierarchical filtering
- **Prediction vs. Observation Chart**: Compares model predictions against actual deterioration patterns

These wireframes will be implemented in Shorthand with embedded Tableau visualizations to create an engaging, interactive story for stakeholders ranging from policymakers to technical professionals.

# User research 

## Target audience

The project targets stakeholders who influence bridge maintenance and protective coating decisions:  
- **Policymakers** (government transportation agencies)  
- **Government officials** (infrastructure and budget planning)  
- **Bridge owners/operators** (state DOTs, municipal agencies)  
- **Inspectors/recorders** (engineers conducting NBI assessments)  
- **Manufacturers/contractors** (protective coating suppliers, maintenance providers)

For the user research study, I recruited interview participants representing different perspectives:
- **Participant A** – A classmate (simulating a bridge owner/decision maker perspective)
- **Participant B** – CMU advisor/Capstone Project Advisor (representing policy/academic advisor perspective)
- **Participant C** – KTA staff (industry professional with technical expertise)

This selection ensures feedback from both **non-technical (general)** and **professional (technical)** audiences, providing insights into how different stakeholder groups interpret and use the visualizations.

## Interview script

The interview protocol was designed to evaluate the clarity, effectiveness, and usability of the bridge coating deterioration story and visualizations across different audience types.

| Goal | Questions to Ask |
|------|------------------|
| **Overall Understanding** | Was the project's purpose (predicting coating deterioration and supporting maintenance planning) clear to you? |
| **Clarity of Visualizations** | Which chart or map was the easiest to understand? Was there any visualization that confused you or felt too complex? |
| **Storytelling & Flow** | Did the order of the story make sense? |
| **Suggestions & Improvements** | Any advice on the visuals or story? |

The script was structured to move from broad comprehension to specific feedback, allowing participants to provide both general impressions and detailed suggestions for improvement.

## Interview findings

The interviews revealed consistent patterns in how different audiences interpreted the visualizations, with some interesting variations based on technical expertise.

| Questions | Interview 1 (Classmate - General Audience) | Interview 2 (CMU Advisor - Policy/Academic) | Interview 3 (KTA Staff - Industry Professional) |
|-----------|---------------------------------------------|---------------------------------------------|--------------------------------------------------|
| **Project Purpose Clear?** | Yes, the purpose was fairly clear. From the storyboard, I understood that the project is about using data to estimate how long protective coatings on bridges will last and helping decide when to repaint. | Yes, the main idea was clear. You want to use bridge inventory data to predict when coatings will deteriorate and help plan repainting. However, I think you should emphasize the broader impact on budgets and safety more clearly, not just the technical part. | Yes, very clear. This is directly aligned with what we deal with, trying to anticipate when coatings fail and making better maintenance plans. |
| **Easiest/Most Confusing Visual** | The Pennsylvania map with color-coded bridge conditions was the easiest. While the prediction vs. observation chart was harder; I wasn't sure what the axes meant at first. | The state-level map was very intuitive. Policymakers or non-technical readers can immediately see regional differences. | The prediction vs. observation comparison was the most useful for me, since it connects modeling to practical outcomes. |
| **Story Flow Make Sense?** | Yes, it flowed logically from background to problem to data to insights. | Yes, mostly. It followed a logical path. But I'd suggest making the conclusion tie back more explicitly to the original problem statement—why this matters for decision makers. | Yes. |
| **Advice on Visuals/Story** | Add short captions or explanations next to complex charts, especially to clarify axes. | Try to simplify technical graphics or add plain-language summaries. | I'd suggest highlighting actionable takeaways more strongly. |


# Identified changes for Part III

Based on the interview findings, several clear patterns emerged that will guide improvements for the final presentation:

## Key Research Insights

**Consistent Feedback:**
- The **map visualization** is the most intuitive and accessible across all audience types
- Some **charts are confusing or too technical** for non-expert audiences
- The **story flow** was logical and clear to all participants

**Conflicting Feedback:**
- **Prediction vs. Observation Chart**: Classmate found it confusing, while KTA staff found it most useful
- **Level of technical detail**: Classmate and Advisor prefer simplification, while KTA staff wants more technical detail

| Research Synthesis | Anticipated Changes for Part III |
|------------------------------------------|---------------------------------------------------------------------------------|
| Map visualizations are universally clear and effective | Maintain and enhance the interactive Pennsylvania map as a central storytelling element |
| Technical charts confuse non-expert audiences | Add captions, annotations, and plain-language summaries to complex visualizations |
| Need balance between technical depth and accessibility | Create two layers of explanation: executive summaries for policymakers alongside detailed technical notes |
| Story conclusion needs stronger connection to practical impact | Emphasize budget impact, safety implications, and maintenance planning benefits more clearly |
| Prediction vs. observation chart valuable but complex | Improve axes labels, add explanatory text, and provide context for interpretation |
| Industry professionals want actionable recommendations | Clearly state which bridges need maintenance soon and connect model outputs to specific decisions |
| Technical audiences appreciate modeling details | Include uncertainty measures and model validation information for professional users |

## Implementation Strategy for Part III

The final presentation will use a **layered approach** to serve multiple audiences:
1. **Executive Layer**: Clear maps, simple summaries, and policy implications upfront
2. **Technical Layer**: Detailed modeling results, uncertainty measures, and validation for professionals
3. **Interactive Elements**: Allow users to drill down from high-level insights to detailed analysis
4. **Actionable Recommendations**: Specific bridge maintenance priorities and timeline suggestions

This approach addresses the conflicting feedback by giving all audiences the level of detail they need while maintaining narrative coherence.

## References
- National Bridge Inventory, Federal Highway Administration
- AASHTO, *Specifications for the National Bridge Inventory Elements*
- Interview participants: CMU classmate, CMU advisor, and KTA industry professional (anonymized)

