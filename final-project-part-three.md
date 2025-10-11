| [home page](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/) | [Visualizing Government Debt](dataviz-examples) | [Critique and redesign (MakeoverMonday)](protein-viz) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Final Project — Part III  

## *Bridges Beneath the Paint: Predicting the Hidden Decay*  

---

**Links:**
- [View Final Shorthand Story](https://app.shorthand.com/organisations/JSrgFWI7zn/stories/yvXnS0rSHU)  
- [View GitHub Repository](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/)

---

## 1. Project Summary  

This project tells the story of **protective coatings on steel bridges** and their inevitable deterioration over time. By combining National Bridge Inventory data with predictive analytics and compelling visualizations, the final data story demonstrates how **data-driven decision-making** can transform infrastructure maintenance planning. The completed narrative, titled *"The Silent Armor of Bridges: How Coating Protects Both Steel and Stories of Love"* bridges the gap between complex engineering data and accessible public storytelling, making the invisible process of corrosion visible and actionable for diverse stakeholders.

---

## 2. Identifying the Target Audience  

From the outset, this project faced a fundamental challenge: **how to speak to both technical experts and non-technical decision-makers simultaneously**. The user research conducted in Part II revealed that my audience naturally divided into two distinct groups with very different needs:

**Primary Audience: Bridge Owners and Policymakers**  
These stakeholders—including state Department of Transportation officials, county infrastructure planners, and budget administrators—need to understand *what* the data reveals and *why* it matters for resource allocation. They care about budget implications, safety risks, and the ability to justify maintenance decisions to taxpayers. During interviews, my CMU advisor (representing this perspective) emphasized the need to "emphasize the broader impact on budgets and safety more clearly, not just the technical part."

**Secondary Audience: Engineers and Industry Professionals**  
Inspectors, bridge engineers, and protective coating contractors require deeper technical detail. They want to understand the *how* behind predictions—the modeling methodology, uncertainty measures, and validation approaches. The KTA industry professional I interviewed appreciated technical depth and wanted "actionable takeaways" that connect directly to maintenance scheduling decisions.

This dual-audience challenge shaped every design decision that followed. Rather than simplifying for the lowest common denominator or overwhelming readers with technical jargon, I chose a **layered approach** that allows each reader to engage at their preferred level of detail.

---

## 3. Evolution from Part II: Key Changes and Refinements  

The journey from Part II to the final deliverable involved substantial iteration based on user feedback. The three interviews I conducted—with a classmate representing general audiences, a CMU advisor representing policy perspectives, and a KTA industry professional—revealed consistent patterns that demanded specific adjustments.

**Visualization Clarity and Hierarchy**  
The most striking finding from user research was universal: the **interactive Pennsylvania map** was the easiest visualization to understand across all audience types. This insight led me to restructure the entire Shorthand narrative around the map as the central anchoring visualization. I simplified the color scheme to a clear condition state gradient (CS1 to CS4) and added hierarchical filtering by county, making regional patterns immediately visible to policymakers while still providing bridge-level detail for engineers.

Conversely, the **prediction versus observation comparison chart**—which I considered a technical highlight—confused my classmate interview participant, who noted "I wasn't sure what the axes meant at first." This feedback prompted me to add explicit axis labels, color-coded annotations for outliers, and a plain-language caption explaining what "over-performing" and "under-performing" bridges mean in practical terms. For the industry professional who found this chart most valuable, I maintained the technical depth but made it more approachable for general readers.

**Strengthening the Narrative Arc**  
My CMU advisor's feedback that "the conclusion should tie back more explicitly to the original problem statement" fundamentally reshaped the story structure. In Part II, the narrative felt more like a technical report—data presented, analysis shown, findings discussed. The final version instead follows a **human-centered arc**: we begin with the emotional resonance of bridges as connectors (using the love-lock metaphor), introduce the hidden problem of deterioration, reveal the data-driven solution, and conclude with a call to civic action. This transformation from report to story made the technical content more memorable and emotionally engaging.

**Balancing Technical Depth with Accessibility**  
Perhaps the most challenging feedback to implement was the conflicting advice about technical detail. My classmate and advisor wanted simplification; the industry professional wanted more depth. My solution was to create **two reading paths** within the same Shorthand story:

- An **executive layer** with visual summaries, bold key findings, and policy implications upfront  
- A **technical layer** accessed through expandable sections and supplemental annotations for readers who want modeling details, uncertainty quantification, and validation metrics  

This approach meant designing each visualization twice: once as a standalone graphic that communicates the core message at a glance, and again with detailed annotations and technical notes for deeper exploration.

---

## 4. Design Decisions and Visual Strategy  

**Color as Metaphor**  
The color palette was perhaps the most intentional design decision. I chose a **rust-inspired gradient** progressing from cool grays (good condition) through amber yellows (moderate deterioration) to deep rust reds (severe corrosion). This wasn't merely decorative—the colors literally represent what happens to unprotected steel. When users see the Pennsylvania map with clusters of red markers, they're seeing corrosion hotspots in a viscerally understandable way. I tested this palette against colorblind-friendly standards to ensure accessibility, confirming that the progression remained distinguishable even in grayscale.

**Typography and Information Architecture**  
Shorthand's scrolling format demanded careful attention to pacing and visual rhythm. I used **bold, large-format titles** to segment the narrative into digestible chapters, allowing readers to scan for sections of interest. Within each section, I limited text blocks to 3-4 lines maximum before introducing a visual element or white space.

**AI-Generated Imagery as Narrative Device**  
One of the most distinctive elements of the final story is the sequence of four AI-generated bridge images showing the transformation from decay to renewal. I experimented with stock photography initially, but found it too generic and disconnected from the data. By generating custom 16:9 images that visually paralleled the condition state progression in the data (CS4 → CS3 → CS2 → CS1), I created a **visual throughline** that reinforced the narrative arc.

**Interactive Elements and User Agency**  
Rather than presenting static conclusions, I embedded **fully interactive Website** that invite exploration. Users can hover over individual bridges to see their specific condition ratings, to focus on their region, or compare predicted versus observed deterioration patterns. This interactivity transforms passive readers into active investigators, which was particularly important for my engineer audience who want to verify findings against their own knowledge.

**The Love-Lock Metaphor**  
The opening and closing imagery featuring love locks on bridges was suggested by a colleague during informal feedback. Initially, I dismissed it as too sentimental for a technical project. But reconsidering it through the lens of my dual audience, I realized the metaphor perfectly captured what policymakers needed to hear: **bridges are about connection, not just steel and coatings**. The locks represent promises, relationships, and community—all of which depend on the hidden infrastructure beneath them.

---

## 5. Personal Reflection: What This Project Taught Me  

Working through this three-part project fundamentally changed how I think about the relationship between data analysis and storytelling. Several specific moments stand out as transformative learning experiences.

**The Gap Between Understanding and Communication**  
I spent weeks building predictive models for coating deterioration, developing features for traffic exposure and environmental conditions, and validating predictions against observed data. I understood the problem deeply from a technical standpoint. But when my classmate interview participant looked confused at my prediction chart—data I thought was self-evident—I realized that "expertise creates blind spots". What seems obvious when you've lived with data for weeks is utterly opaque to a fresh viewer. This forced me to develop empathy as a design skill, constantly asking "what would I need to know if I were seeing this for the first time?"

**User Research is Humbling**  
I expected my interviews to generate minor tweaks to caption wording or color choices. Instead, they revealed fundamental structural problems with my narrative. The industry professional's comment that I needed "actionable takeaways" made me realize I'd been so focused on demonstrating analytical sophistication that I'd forgotten to answer the core question: *so what?* This led to adding the entire "Protect What Connects Us" call-to-action section, which reframes the analysis as a civic responsibility rather than just a technical exercise.

**Design Decisions Are Arguments**  
Every visual choice—color, typography, layout, image selection—is an implicit argument about what matters and how the audience should feel. Choosing rust colors argues that deterioration is serious and visceral. Choosing interactive maps argues that location and regional variation matter. Choosing AI-generated bridge transformations argues that renewal is possible. These aren't neutral aesthetic choices; they're rhetorical moves that shape how readers interpret data. Recognizing this turned design from decoration into a strategic communication tool.

**The Power of Constraint**  
Shorthand's scrolling format initially felt limiting compared to traditional academic papers or slide presentations. But the constraint forced clarity. Every visualization had to justify its inclusion. Every paragraph had to advance the narrative. The inability to hide complexity in appendices or footnotes meant I had to either make technical content accessible or cut it entirely. This ruthless editing improved the final product immeasurably—not despite the constraints, but because of them.

**Iteration Never Really Ends**  
Even after submitting Part III, I find myself mentally redesigning elements. Should the prediction chart have used a different axis scale? Could the county-level aggregation have been more sophisticated? Would video instead of static images have been more compelling? This reflects a crucial lesson: **data storytelling is a craft, not a formula**. There's always another way to visualize, another angle to explore, another audience to consider. The goal isn't perfection but continuous improvement in translating insight into impact.

---

## 6. Final Deliverables and Links  

The complete project is accessible through multiple platforms to serve different audiences and use cases:

**Primary Deliverable: Shorthand Data Story**  
[Bridges Beneath the Paint: Predicting the Hidden Decay](https://app.shorthand.com/organisations/JSrgFWI7zn/stories/yvXnS0rSHU)  
This is the main public-facing narrative that integrates all visualizations, imagery, and written content into an interactive scrolling experience. The story is published and publicly accessible for stakeholders, educators, and the general public.

**Supporting Repository: GitHub Portfolio**  
[GitHub Repository](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/)  
The GitHub portfolio hosts all three parts of the project (Part I, Part II, and Part III), embedded Tableau visualizations, and supplemental files. This serves as the permanent archive and allows technical audiences to explore the project development process.

**Additional Materials:**

- **Part I**: Project outline, initial sketches, and data foundation  
- **Part II**: User research, interview findings, and wireframes  
- **Part III**: This reflection document and final deliverable links  
- **Embedded Visualizations**: Interactive Tableau dashboards (Pennsylvania bridge map, prediction vs. observation chart)  
- **Word Document**: Full text of Shorthand story submitted separately for Turnitin originality review

---

## 7. References and Attribution  

**Data Sources:**

- Federal Highway Administration. (2025). *National Bridge Inventory (NBI).* Retrieved from <https://www.fhwa.dot.gov/bridge/nbi.cfm>  
- Federal Highway Administration. (2025). *InfoBridge: National Bridge Inventory Element-Level Data.* Retrieved from <https://infobridge.fhwa.dot.gov>  
- Pennsylvania Department of Transportation. (2025). *PA Bridge Site 2025 Dataset.* [GitHub Repository](https://github.com/Aspdelus/Aspdelus-dataviz-portfolio)

**Technical Standards:**

- American Association of State Highway and Transportation Officials (AASHTO). *Manual for Bridge Element Inspection: Specifications for the National Bridge Inventory Elements.* Second Edition.  
- Federal Highway Administration. *Recording and Coding Guide for the Structure Inventory and Appraisal of the Nation's Bridges.* Report No. FHWA-PD-96-001.

**Visualization and Storytelling Framework:**

- Berinato, S. (2016). *Good Charts: The HBR Guide to Making Smarter, More Persuasive Data Visualizations.* Harvard Business Review Press.  
- Knaflic, C. N. (2015). *Storytelling with Data: A Data Visualization Guide for Business Professionals.* John Wiley & Sons.

**User Research:**

- Interview Participants (anonymized for confidentiality):  
  - Participant A: CMU MISM classmate (general audience perspective)  
  - Participant B: CMU academic advisor (policy and institutional perspective)  
  - Participant C: KTA industry professional (technical and practitioner perspective)

**Visual Assets:**

- AI-generated imagery: Created by author using generative AI tools for narrative illustration  
- Supplemental bridge photography: Licensed under Creative Commons from AlphaCoders and Pexels  
- Love-lock imagery: Public domain and Creative Commons licensed photographs

---

## 8. Conclusion  

This project represents more than an analysis of bridge coating deterioration—it's an exploration of how data visualization can transform complex technical challenges into compelling public narratives. By moving from initial data exploration (Part I) through user-centered research (Part II) to final storytelling execution (Part III), the project demonstrates that **effective data communication requires both analytical rigor and empathetic design**.

The completed story serves bridge owners, policymakers, engineers, and the public, making invisible infrastructure decay visible and actionable. Most importantly, it proves that when we combine data science with human-centered storytelling, we can turn abstract datasets into tools for better decision-making and civic engagement.

---

**Navigation:**  
[← Part II: User Research & Storyboard](final-project-part-two) | [← Part I: Project Outline](final-project-part-one) | [↑ Portfolio Home](https://aspdelus.github.io/Aspdelus-dataviz-portfolio/)
