# ClearText: Making the Web Understandable for Everyone

**Course:** IS 308 – Releasing Inclusive Technology  
**Instructor:** Travis Wagner  
**Date:** October 30, 2025  

**Contributors:**  
- Ellis Lee (ellee33@illinois.edu)  
- Sahana Rajagopalan (sahana-email@illinois.edu)  

---

## 1. Project Purpose

ClearText is a browser-based tool concept that rewrites complex web content into plainer language while preserving meaning and tone. Much of the internet is written at reading levels that exclude:

- ESL and multilingual users  
- People with learning or cognitive disabilities  
- Users with lower literacy levels or limited familiarity with technical language  

Plain language is widely recognized as an accessibility strategy that benefits people with cognitive disabilities, low literacy, and those reading in a non-native language.:contentReference[oaicite:0]{index=0} It makes content more understandable and supports inclusive access to essential information such as healthcare, education, and public services.:contentReference[oaicite:1]{index=1}

**ClearText aims to:**

- Automatically simplify online text into clearer language  
- Preserve key meaning, tone, and critical details  
- Support users who experience cognitive, linguistic, or accessibility barriers  
- Promote digital equity by making web content more understandable

This prototype aligns with W3C’s guidance on cognitive accessibility:contentReference[oaicite:2]{index=2} and the WCAG 2.2 “Understandable / Readable” principle that text content should be readable and understandable.:contentReference[oaicite:3]{index=3}

---

## 2. Core Features (Prototype Scope)

The ClearText prototype focuses on the key interactions a browser plugin would provide.

### 2.1 Toolbar Interface

- **Toggle:** “Simplify this page” (On/Off)  
- **Reading Level Selector:** Basic, Intermediate, Advanced  
- **Preview Button:** Opens a side-by-side view of original vs simplified text  

These controls are inspired by prior work on content simplification tools such as the Easier Web system, which uses UI patterns tailored to people with cognitive impairments.:contentReference[oaicite:4]{index=4}

### 2.2 Side-by-Side Preview

- Left panel: Original text  
- Right panel: Simplified text  
- Optional indicators of approximate reading level (with clear disclaimers that readability scores are estimates and not a guarantee of comprehension)  

Research has shown that readability formulas alone do not ensure understanding and can mislead designers if used in isolation.:contentReference[oaicite:5]{index=5} ClearText therefore treats readability metrics as one signal among many, not the primary measure of success.

### 2.3 Feedback & Issue Reporting

- **“Report a rewrite issue”** button beneath the simplified text  
- Quick options to flag:
  - “Meaning changed or lost”  
  - “Tone feels wrong or disrespectful”  
  - “Important details removed”  
  - Open text field for other issues  

Document-level text simplification research emphasizes that simplicity and meaning preservation must be evaluated separately and balanced carefully.:contentReference[oaicite:6]{index=6} The feedback workflow is designed to surface cases where simplification goes too far or not far enough.

### 2.4 Settings & Privacy

- **Processing Mode**
  - Prefer local processing when technically feasible  
  - Clear explanation of any cloud processing if used  
- **Data Retention**
  - Option to delete processed text after the session  
- **Accessibility Options**
  - Larger plugin text  
  - High-contrast mode  
  - Language preference  

These decisions are informed by cognitive accessibility guidance that calls for clear feedback, predictable interfaces, and transparency about how content is processed.:contentReference[oaicite:7]{index=7}

---

## 3. Target Users

ClearText is designed primarily for:

- **ESL and multilingual users**  
  - Research on EFL learners shows that online reading of authentic texts is challenging, and strategy support improves comprehension.:contentReference[oaicite:8]{index=8}  
- **Users with learning disabilities or cognitive barriers**  
  - Plain language and well-structured content improve access for people with cognitive, intellectual, and developmental disabilities.:contentReference[oaicite:9]{index=9}  
- **Educators, disability services, and accessibility professionals**  
  - ClearText can support the creation and review of accessible materials.:contentReference[oaicite:10]{index=10}  
- **Web developers and content teams**  
  - The plugin concept supports WCAG 2.2’s Understandable/Readable criteria, encouraging teams to consider cognitive and language accessibility, not just visual or technical compliance.:contentReference[oaicite:11]{index=11}  

---

## 4. Design Principles

ClearText is guided by equitable and inclusive design principles grounded in current research and standards.

1. **Preserve Meaning, Reduce Complexity**  
   Text simplification should make content easier to read without erasing nuance or critical information.:contentReference[oaicite:12]{index=12}  

2. **Support Cognitive Accessibility**  
   W3C’s “Making Content Usable for People with Cognitive and Learning Disabilities” highlights the importance of user-centered design, clear structure, and direct language for cognitive access.:contentReference[oaicite:13]{index=13}  

3. **Align with WCAG 2.2 (Understandable / Readable)**  
   ClearText’s focus on plain language, predictable controls, and clear error feedback supports WCAG principles that interfaces and content must be understandable.:contentReference[oaicite:14]{index=14}  

4. **Go Beyond Readability Formulas**  
   Kauchak and Leroy argue that readability formulas are limited and should be supplemented by evidence-based simplification strategies and user testing.:contentReference[oaicite:15]{index=15}  

5. **Center User Testing & Feedback**  
   COGA guidance and text simplification research both emphasize including users with cognitive and reading difficulties in iterative testing and evaluation.:contentReference[oaicite:16]{index=16}  

6. **Respect Cultural and Linguistic Contexts**  
   For ESL learners, comprehension depends on language level, background knowledge, and strategies used when reading online.:contentReference[oaicite:17]{index=17} ClearText is designed to show both original and simplified text so users can decide what best fits their needs.

---

## 5. Development Process

### 5.1 Methods

- **Literature Review**  
  We reviewed work on plain language, cognitive accessibility, and text simplification tools, including W3C COGA guidance, WCAG 2.2, and research on automated simplification and evaluation.:contentReference[oaicite:18]{index=18}  

- **User & Expert Input (Planned/Conceptual)**  
  - Interviews or discussions with ESL learners  
  - Conversations with students with disabilities and campus accessibility staff  
  - Feedback from educators and web/content designers  

- **Comparative Tool Analysis**  
  We examined how existing readability and “simplify” tools work, noting limitations such as over-reliance on grade-level metrics and lack of transparency.:contentReference[oaicite:19]{index=19}  

- **Prototype Design**  
  Using accessible design patterns from cognitive accessibility research and UI work on the Easier Web system, we developed wireframes for the toolbar, preview, feedback, and settings screens.:contentReference[oaicite:20]{index=20}  

### 5.2 Current Prototype Form

For the IS 308 “Releasing Inclusive Technology” project, ClearText is delivered as:

- **Interface wireframes / mockups** illustrating:
  - Main plugin popup  
  - Side-by-side preview  
  - Feedback reporting modal  
  - Settings / privacy panel  

(If applicable, include: “A simple HTML/JS demo page that mimics pasting text, selecting a level, and viewing a sample simplified version.”)

---

## 6. How to View or Use the Prototype

1. Open the design prototype (e.g., Figma link or attached PDF) included with this submission.  
2. Navigate through the screens labeled:
   - `ClearText – Toolbar`  
   - `ClearText – Preview`  
   - `ClearText – Report Issue`  
   - `ClearText – Settings`  
3. Read the on-screen notes explaining:
   - How the plugin is toggled and configured  
   - How users compare original vs simplified text  
   - How feedback is submitted and used to improve future versions  

If a simple web demo is included:

1. Open `cleartext-demo.html` in a browser.  
2. Paste a short complex paragraph into the “Original text” panel.  
3. Choose a reading level and click **Simplify** to see a sample transformation.  
4. Use the feedback box to simulate reporting any problems with the simplification.

---

## 7. Roles & Contributions

- **Ellis Lee**
  - Issue statement and initial concept  
  - Literature review on plain language, WCAG, and cognitive accessibility  
  - Interface/interaction design for toolbar, preview, and feedback  
  - Drafting ethical and privacy considerations  

- **Sahana Rajagopalan**
  - User and stakeholder mapping (ESL learners, disabled students, educators)  
  - Comparative analysis of existing readability/simplification tools  
  - Design of feedback workflow and settings screen  
  - Refinement of equitable design principles and project framing  

We collaborated on core design decisions, writing, and integration of sources.

---

## 8. Feedback and Future Changes

ClearText is explicitly designed to evolve through feedback from people who face the strongest barriers to online comprehension.

### 8.1 How to Suggest Changes (Conceptual Plan)

In a deployed version, users would be able to:

- Click **“Report a rewrite issue”** directly in the plugin to:
  - Flag loss or distortion of meaning  
  - Describe when tone feels disrespectful or inaccurate  
  - Report confusing or unhelpful simplifications  

- Complete a short survey asking:
  - Who they are (e.g., ESL learner, educator, disability services; optional)  
  - What type of page they were reading  
  - What worked well and what did not  

### 8.2 How Feedback Would Be Used

- Prioritize feedback from:
  - Disabled users  
  - ESL/multilingual users  
  - Low-literacy and neurodivergent readers  

- Maintain a public change log documenting:
  - What was changed  
  - Which kind of feedback triggered the change  
  - Any new limitations introduced  

This approach follows W3C’s recommendation to include people with cognitive and learning disabilities directly in design, testing, and evaluation.:contentReference[oaicite:21]{index=21}

---

## 9. Ethical & Accessibility Considerations

- **Meaning & Risk**  
  - ClearText does not replace professional, legal, or medical advice. Users are encouraged to consult the original text for official meaning, especially for high-stakes content.:contentReference[oaicite:22]{index=22}  

- **User Autonomy**  
  - Users can toggle the plugin off, compare original and simplified versions, and decide which version to rely on.  

- **Privacy**  
  - A future implementation would prioritize local processing when possible and transparent, minimal data handling when remote processing is required.  

- **Scope & Limitations**  
  - Some texts (e.g., poetry, legal contracts, culturally dense writing) may lose important nuance when simplified. The design emphasizes transparency so users can always revisit the original text.

---

## 10. References

Ayre, J., Bonner, C., Muscat, D. M., et al. (2024). Online plain language tool and health information quality: A randomized clinical trial. *JAMA Network Open, 7*(10), e2437955.:contentReference[oaicite:23]{index=23}  

Cripwell, L., Legrand, J., & Gardent, C. (2024). Evaluating document simplification: On the importance of separately assessing simplicity and meaning preservation. In *Proceedings of the 3rd Workshop on Tools and Resources for People with REAding DIfficulties (READI) @ LREC-COLING 2024*.:contentReference[oaicite:24]{index=24}  

Harvard University Information Technology. (n.d.). *Use plain language*. Harvard Digital Accessibility.:contentReference[oaicite:25]{index=25}  

Huang, H.-C., Chern, C.-L., & Lin, C.-C. (2009). EFL learners’ use of online reading strategies and comprehension of texts: An exploratory study. *Computers & Education, 52*(1), 13–26.:contentReference[oaicite:26]{index=26}  

Kauchak, D., & Leroy, G. (2016). Moving beyond readability metrics for health-related text simplification. *IT Professional, 18*(3), 43–51.:contentReference[oaicite:27]{index=27}  

Moreno, L., Martínez, P., Alarcón, R., & Petrie, H. (2024). Designing user interfaces for content simplification aimed at people with cognitive impairments: The Easier web system. *Universal Access in the Information Society*.:contentReference[oaicite:28]{index=28}  

Pulrang, A. (2020, October 22). Plain language writing—An essential part of accessibility. *Forbes*.:contentReference[oaicite:29]{index=29}  

University of Michigan Accessibility. (n.d.). *Writing in plain language*. University of Michigan.:contentReference[oaicite:30]{index=30}  

W3C Web Accessibility Initiative (WAI). (2021). *Making content usable for people with cognitive and learning disabilities* (W3C Working Group Note).:contentReference[oaicite:31]{index=31}  

W3C. (2024). *Web Content Accessibility Guidelines (WCAG) 2.2*.:contentReference[oaicite:32]{index=32}  

