# Domain One A: Guidelines, principles and techniques for meeting success criteria 

W3C, the World Wide Web Consortium, publishes W3C Recommendations including: 
- 	Web Content Accessibility Guidelines (WCAG) 2.2 - Web content
- 	User Agent Accessibility Guidelines (UAAG) 2.1 – Software used to access the web, browsers and media players
- 	Authoring Tools Accessibility Guidelines (ATAG) 2.0 – Software and services that people use to create web content
- 	Accessible Rich Internet Applications (WAI-ARIA) 1.2 - ARIA specification

## Understand and Interpret WCAG 2.2

### Versioning: 2.0 2008, 2.1 2018, 2.2 2023
#### WCAG 2.1
- 	Added SC for new input modes like touch or speech. More criteria that focuses on individuals with low vision or cognitive disabilities not addressed in 2.0 
#### WCAG 2.2 
- 	Added further requirements for cognitive and keyboard only users. Focus Not Obscured, Target Size, Dragging  Movements.
### Principles 
- 	Perceivable: presented in  way users can perceive
- 	Operable: operable in different ways such as keyboard or voice recognition
- 	Understandable: UI must be understandable to all users
- 	Robust: can be interpreted by a wide variety of users, including assistive tech 
### Guidelines
Under each principle there are guidelines, 13 in total. They provide the basic goals towards making content accessible.
- 	1.1 Text Alternative
- 	1.2 Time Based Media
- 	1.3 Adaptable
- 	1.4 Distinguishable
- 	2.1 Keyboard Accessible
- 	2.2 Enough Time
- 	2.3 Seizures and Physical Reactions
- 	2.4 Navigable
- 	2.5 Input Modalities
- 	3.1 Readable
- 	3.2 Predictable
- 	3.3 Input Assistance
- 	4.1 Compatible

### Success Criterion 
The specific testable criteria. Has 3 levels of conformance A, AA, AA. 
A: most base with the boradest impact 
AA: Inforporates additional criteria that supports a wider context of users. The most often cited in legal reuirements, the standard most are going for. 
AAA: Highest level, ensures contetnt is accessible for the widest range of users. Not always realistic and does not apply to all scenarios. 

### Techniques 

Sufficicent: reliable ways to meet SC. If sufficient techniques are implemnted, then you meet the SC. 

Advisory: Suggested way to improve accessibility, very helpful to some users and may be needed by other users. Consider advisory and not sufficent due to: May not be sufficient alone, bay be based on technology that is not yet stable, may not be testable, provide realted accessibility beneifits but not directly related to the SC. Encouraged to meet all when approrpriate to meet the needs of the widest range of users.

Failures: Things the cause accessibility barries and fair specific SC. Documented so authoers know what to avoid and evals can check. Does not meet WCAG 2.2 unless an alternative is provided without the failure. 

### Normative and non-normative information in WCAG 2.2.
Normative = required for conformance. 
Defines accessibility practices required for conformance and verification. Minimum to make websites accessible. 

Non-normative = never required for conformance, content identified as “informative”. 
Guidance and techniques for interpreting and confirming with the normative requirement. Changes more frequently than normative documents. 
The main content of WCAG 2.2 is normative. Non-normative is the intro materials, appendixes, diagrams, examples, and notes. Advisory info to help interpret the guidelines but does not create requirements that impact conformance. 

## Understand and interpret WAI-ARIA 1.2
### Understand the purpose and impact of WAI-ARIA 1.2. 
###  Understand the WAI-ARIA 1.2 model of roles and properties.
### Know when and why to use WAI-ARIA 1.2, and when to use standard HTML instead
#### 5 rules of aria
1. Don'y use aria, if you can use HTML instead
2. Don't change native semantics
3. All interactive aria roles need to be operable by a keyboard
4. Don't use `role="presentation"` or `aria-hidden="true"` on visible focusable elements
5. All interactive elements must have an accessible name
## Understand and Interpret ATAG 2.0
## Understand and interpret EN 301 549
“Harmonized” European Standard. Developed by 3 official European Standard Organizations CEN, CENELEC, and ETSI. Voluntary technical specifications for presumed conformity. Efficient way to show compliance, orgs are free to choose other technical solutions to fulfill legal obligations. 
Originally developed for procurement of accessible products and services. 
Currently being updated to support the European Accessibility Act (EAA) that will enter into effect on June 28th 2025. 
Adopted outside of Europe as well. 

### Know what kind of technologies are addressed by EN 301 549 
ICT product and services. Broader than web a11y, includes things like hardware, software, support services as well as web, documents, and apps. 

### Describe how WCAG is represented in EN 301 549 
Intends to harmonize with WCAG in clauses 9, 10, 1. Current version references WCAG 2.1 SC A and AA as well as the non-normative W3C guidance on apply WCAG 2.0 to non-web.  

### Understand the intent and scope of requirements in Annex A Table A1 that go beyond WCAG 
Current version includes annex A table showing presumed conformance for website and apps of the Web Accessibility Directive covering public sector bodies.
Annex A presents the relationship between the technical specifications and the web accessibility directions. 





