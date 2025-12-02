# ClearText: Making the Web Understandable for Everyone

**Course:** IS 308 – Releasing Inclusive Technology 

**Instructor:** Travis Wagner  
**Date:** October 30, 2025  

**Contributors**  
- Ellis Lee  
- Sahana Rajagopalan  

---

## 1. Project Purpose

ClearText is a browser-based tool concept that rewrites complex web content into plainer language while preserving meaning and tone. Much of the internet is written at reading levels that exclude:

- ESL and multilingual users  
- People with learning or cognitive disabilities  
- Users with lower literacy or limited familiarity with technical or medical language  

Plain language is widely recognized as an accessibility strategy that benefits people with cognitive disabilities, low literacy, and those reading in a non-native language (Harvard University Information Technology, n.d.; Pulrang, 2020; University of Michigan Accessibility, n.d.). When online resources—especially health, legal, and government information—are written in dense, technical language, users may not understand essential information even when they can physically access the page (Ayre et al., 2024; Kauchak & Leroy, 2016).

**ClearText aims to:**

- Automatically simplify online text into clearer, more direct language  
- Preserve key meaning, tone, and critical details  
- Support users who experience cognitive, linguistic, or accessibility barriers  
- Promote digital equity by making web content more understandable  

The project aligns with W3C’s guidance on cognitive and learning accessibility (W3C WAI, 2021) and with WCAG 2.2’s requirement that text content be readable and understandable (W3C, 2023).

---

## 2. Prototype Overview

Our current prototype is a **Figma mockup** that demonstrates how ClearText would appear as a browser plugin. The design is shown on a complex health-information page (“What is Leukemia?”) to highlight real-world stakes.

### 2.1 Plugin Panel

The ClearText panel appears as an overlay on the right side of the browser and includes:

- **Simplify Page toggle**  
  Turns simplification on or off for the current page.

- **Reading Level selector**  
  Radio buttons for **Basic**, **Intermediate**, and **Advanced** levels.  
  These reflect different degrees of simplification (sentence length, vocabulary, and density).

- **Show Side-by-Side Preview button**  
  Opens a view where users can compare the **original** and **simplified** versions of the text. This supports user autonomy and helps users check that meaning has been preserved.

- **Report Issue section**  
  A control labeled “Process rewrite issue” that lets users indicate that something about the simplification is wrong or harmful (for example, if meaning changed or tone feels disrespectful).

- **Privacy Mode toggle**  
  A control labeled “Privacy mode,” with a note explaining that turning it off may involve cloud processing. This makes data practices explicit and keeps users informed.

The interface design is informed by previous work on content simplification tools for people with cognitive impairments, such as the Easier Web system (Moreno et al., 2024).

---

## 3. Target Users

ClearText is designed primarily for:

- **ESL and multilingual users**  
  Research on English learners’ online reading shows that authentic web texts are often difficult to comprehend and that support tools can improve understanding (Huang et al., 2009).

- **Users with learning disabilities or cognitive barriers**  
  Plain language and well-structured content are key to making information usable for people with cognitive and learning disabilities (Harvard University Information Technology, n.d.; W3C WAI, 2021).

- **Educators, disability services, and accessibility professionals**  
  These stakeholders can use ClearText to review materials and ensure that students and community members can understand critical information (Ayre et al., 2024).

- **Web developers and content teams**  
  ClearText provides a practical way to move toward WCAG 2.2 “Understandable” criteria by foregrounding language complexity, not just visual or technical compliance (W3C, 2023).

---

## 4. Design Principles

ClearText is guided by equitable and inclusive design principles supported by current research and accessibility standards.

1. **Preserve meaning while reducing complexity**  
   Text simplification should make content easier to read without erasing nuance or critical information (Ayre et al., 2024; Cripwell et al., 2024).

2. **Support cognitive accessibility**  
   W3C’s “Making Content Usable for People with Cognitive and Learning Disabilities” highlights the need for clear, predictable, and forgiving interfaces (W3C WAI, 2021). ClearText’s controls are labeled plainly and kept in a single, coherent panel.

3. **Align with WCAG 2.2 (Understandable / Readable)**  
   The plugin’s focus on plain language, consistent controls, and clear feedback supports WCAG principles that content and user interfaces must be understandable (W3C, 2023).

4. **Go beyond readability formulas**  
   Readability scores alone often fail to predict actual comprehension and may mislead designers (Kauchak & Leroy, 2016). ClearText treats readability as one signal among many and emphasizes user feedback and real-world testing.

5. **Center user feedback and iteration**  
   Document-level simplification research shows that simplicity and meaning preservation must be evaluated together (Cripwell et al., 2024). ClearText’s “Report Issue” feature is designed to surface instances where simplification fails users.

6. **Respect cultural and linguistic context**  
   For ESL users, understanding depends on language level, background knowledge, and reading strategies (Huang et al., 2009). The side-by-side view lets users choose when to rely on the original text and when to rely on the simplified version.

---

## 5. Development Process

### 5.1 Methods

- **Literature Review**  
  We reviewed work on plain language, health-literacy interventions, readability metrics, and cognitive accessibility (Ayre et al., 2024; Kauchak & Leroy, 2016; Moreno et al., 2024; W3C, 2023; W3C WAI, 2021; Pulrang, 2020).

- **User and Stakeholder Mapping**  
  We identified and mapped key stakeholders, including ESL learners, disabled students, educators, and web developers. This helped us clarify whose barriers we are prioritizing and where ClearText fits into broader accessibility ecosystems.

- **Comparative Tool Analysis**  
  We examined existing readability and “simplify this page” tools, noting issues such as over-reliance on grade-level scores, lack of transparency, and limited support for user feedback.

- **Prototype Design in Figma**  
  We created a Figma prototype of the ClearText panel over a real medical webpage. The prototype demonstrates the main workflow: toggling simplification, selecting a reading level, opening side-by-side preview, reporting issues, and enabling privacy mode.

### 5.2 Current Deliverables

For the IS 308 project, ClearText is delivered as:

- A **Figma prototype** illustrating:
  - ClearText plugin panel  
  - Side-by-side preview interaction  
  - Issue reporting control  
  - Privacy mode toggle  

- This **README**, which documents the project’s purpose, contributors, design rationale, and feedback process.

---

## 6. How to View and Use the Prototype

1. Open the Figma file titled **“ClearText Prototype”**.  
2. Start at the frame showing the “What is Leukemia?” page with the ClearText panel on the right.  
3. Use Figma’s **Present** mode to click through the interactive elements:
   - Toggle **Simplify Page** on/off.  
   - Change the **Reading Level** between Basic, Intermediate, and Advanced.  
   - Click **Show Side-by-Side Preview** to see how users would compare original and simplified text.  
   - Toggle **Report Issue** and **Privacy mode** to understand how feedback and data-handling preferences appear in the UI.  

If needed for grading, screenshots of each key state (default, preview, issue reporting, privacy mode) can be included in the submission package.

---

## 7. Contributors and Roles

- **Ellis Lee**  
  - Drafted and structured the README  
  - Led the project framing and issue statement  
  - Conducted the core literature review on plain language, readability, and cognitive accessibility  
  - Articulated ethical, privacy, and equity considerations  

- **Sahana Rajagopalan**  
  - Designed and built the Figma prototype  
  - Led the visual and interaction design of the ClearText panel  
  - Refined the layout of controls (reading level, issue reporting, privacy mode)  
  - Contributed feedback to the written rationale and design principles  

All core design decisions were made collaboratively.

---

## 8. Feedback and Future Changes

Because ClearText is meant to serve communities that often face exclusion, feedback from those users is central to its evolution.

### 8.1 How Users Would Suggest Feedback

In a fully implemented version, users would be able to:

- Click **“Report Issue”** in the plugin panel to:
  - Flag that meaning changed or important information was lost  
  - Indicate when tone feels wrong, patronizing, or culturally insensitive  
  - Describe any confusion caused by the rewrite  

- Complete an optional short survey linked from the plugin that asks:
  - Who they are (e.g., ESL learner, educator, disabled user; all optional)  
  - What kind of page they were reading (health, financial, academic, etc.)  
  - What worked well and what did not  

### 8.2 How Feedback Would Be Used

- Give priority to feedback from:
  - Disabled users  
  - ESL and multilingual readers  
  - People with lived experience of low literacy or cognitive barriers  

- Maintain a public **changelog** that explains:
  - What changed in the simplification rules or interface  
  - Which feedback motivated the change  
  - Any known limitations that remain  

This process aligns with recommendations to involve people with cognitive and learning disabilities in ongoing design and evaluation (W3C WAI, 2021; Moreno et al., 2024).

---

## 9. Ethical and Accessibility Considerations

- **Meaning and Risk**  
  ClearText does not replace legal, medical, or professional advice. Users should treat the simplified version as a support tool and refer back to the original text for official meaning, especially in high-risk domains such as health or law (Ayre et al., 2024).

- **User Autonomy**  
  Users can turn ClearText off at any time, switch between reading levels, and view the original and simplified text side by side. The goal is to add options, not remove control.

- **Privacy**  
  The Privacy mode toggle foregrounds data handling and gives users a clear indication of when text may leave their device for processing. In a full implementation, the default would be local processing whenever technically feasible, with strong safeguards for any cloud-based processing.

- **Scope and Limitations**  
  Some genres—such as poetry, legal contracts, or culturally dense texts—may lose important nuance during simplification. ClearText’s design emphasizes transparency so users can always see and return to the original.

---

## 10. References

Ayre, J., Bonner, C., Muscat, D. M., McCaffery, K. J., Cvejic, E., Maher, L., Irwin, A., & Jansen, J. (2024). Online text editor to improve the quality of health information: Randomized clinical trial. *JAMA Network Open, 7*(10), e2437955.

Cripwell, L., Legrand, J., & Gardent, C. (2024). Evaluating document simplification: On the importance of separately assessing simplicity and meaning preservation. In *Proceedings of the 3rd Workshop on Tools and Resources for People with Reading Difficulties (READI)*.

Harvard University Information Technology. (n.d.). *Use plain language*. https://accessibility.huit.harvard.edu

Huang, H.-C., Chern, C.-L., & Lin, C.-C. (2009). EFL learners’ use of online reading strategies and comprehension of texts: An exploratory study. *Computers & Education, 52*(1), 13–26.

Kauchak, D., & Leroy, G. (2016). Moving beyond readability metrics for health-related text simplification. *IT Professional, 18*(3), 43–51.

Moreno, L., Martínez, P., Alarcón, R., & Petrie, H. (2024). Designing user interfaces for content simplification aimed at people with cognitive impairments: The Easier Web system. *Universal Access in the Information Society*. Advance online publication.

Pulrang, A. (2020, October 22). Plain language writing—An essential part of accessibility. *Forbes*. https://www.forbes.com

University of Michigan Accessibility. (n.d.). *Writing in plain language*. https://accessibility.umich.edu

W3C. (2023). *Web Content Accessibility Guidelines (WCAG) 2.2*. World Wide Web Consortium. https://www.w3.org/TR/WCAG22

W3C Web Accessibility Initiative (WAI). (2021). *Making content usable for people with cognitive and learning disabilities*. World Wide Web Consortium. https://www.w3.org/WAI/coga
