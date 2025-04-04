## Installation

VS Code
Install Roo Code plugin
go to Prompts tab, then Modes. Click on {} Edit Modes Configuration. Copy and paste the json found in this repo. 
Click Done.
The new Design Review Mode should appear below the Roo main prompt input box. If not, restart.




# Roo Code design-review mode


I'll create a UX/UI design assessment mode that can evaluate designs for best practices, accessibility, and visual harmony. This mode will focus on analyzing design elements like colors, spacing, typography, and WCAG compliance.

I've created a comprehensive "Design Assessor" mode for evaluating UI/UX design elements. Here's what this mode offers:

### 🎨 Design Assessor Mode

This specialized mode analyzes designs across five key dimensions:

1. **Accessibility**
   - WCAG compliance checking
   - Color contrast ratio verification
   - Keyboard navigation assessment
   - Screen reader compatibility
   - Alternative text evaluation

2. **Visual Design**
   - Color harmony and palette consistency
   - Typography hierarchy and readability
   - Spacing system consistency
   - Visual rhythm and component states
   - Dark/light mode adaptability

3. **Layout & Composition**
   - Responsive breakpoints
   - Content hierarchy
   - Whitespace usage
   - Grid implementation
   - Visual weight distribution

4. **Interaction Design**
   - Affordance clarity
   - Feedback mechanisms
   - Error handling patterns
   - Loading states
   - Touch interface compatibility

5. **Brand Alignment**
   - Brand guideline consistency
   - UX copy voice and tone
   - Visual identity reinforcement

The mode integrates with other SPARC components by allowing delegation to coding, testing, and documentation agents. It provides objective measurements (like contrast ratios) alongside prioritized recommendations that balance aesthetic considerations with functional improvements.

Would you like me to expand on any particular aspect of this design assessment mode or modify any of its capabilities?

## Enhanced

1. **Refined Annotation Approach**: Changed from "Screenshot reviews with annotation overlays" to "Detailed descriptions of issues with specific locations in screenshots" and "Reference points and coordinates for design elements needing improvement"

2. **Expanded Usability Heuristics**: Added a dedicated section for usability frameworks including:
   - Nielsen's 10 Usability Heuristics
   - Shneiderman's "Eight Golden Rules"
   - Gestalt principles application
   - Cognitive walkthrough methodology
   - System Usability Scale (SUS) scoring

3. **Performance Perception**: Added two entries related to performance:
   - "Animation impact on perceived performance" under Visual Design
   - "Perceived performance of transitions and animations" under Interaction Design
   - Additional checkpoints at the end for evaluating animation complexity and cognitive load

4. **TDD Role Clarification**: Expanded the description for the TDD collaboration to specifically mention "visual regression testing, component appearance testing, and accessibility automation"

