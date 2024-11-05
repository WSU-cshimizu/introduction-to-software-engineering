# User Interaction (UI), User Experience (UX), HCI (Human-Computer Interaction) & Frameworks
Key goals are:
1. Understand fundamental principles of UI/UX design and HCI.
2. Recognize the role of usability and user-centered design in software development.
3. Identify key design elements that contribute to a positive user experience.

## User Interaction vs User Experience
These are very intertwined, as the design and implementation of a _user interface_ dictates the types of _user interactions_ and, therefore, dictates the overall _user experience_. 

**UI (User _Interface_)**  
- Choosing appropriate affordances and signifiers.
  - Affordances: the characteristics of an object or space that indicate how it can be used or how to interact with it.
  - Signifiers: perceptible cues that designers include in (eg) interfaces so users can easily discover what to do.
- The look and feel of the interface, 
- Visual design elements like colors, typography, buttons, and layout.
- Aiming for aesthetically pleasing and consistent design

**UI (User _Interaction_)**
- Includes actions or gestures like clicking, swiping, and typing, which are responses to affordances.
- Deals with interactive elements like buttons, gestures, and response times.
- Concerned with making interactions smooth, responsive, and intuitive.
- Reducing user effort and make completing tasks straightforward.

**UX (User _Experience_)**  
- Deals with the functionality, usability, and satisfaction of the interaction.
- Concerned with user journey, accessibility, and problem-solving.
- Creating a seamless, enjoyable, and meaningful user experience.

## Human-Computer Interaction (HCI)
- Human-Computer Interaction focuses on understanding how a human interprets and interacts with a computer.
  - Studies usability, ergonomics, and the impact of design on users
- This is a broad field of study, and frequently out of scope for the "normal" developer, but it is generally a good idea to keep certain things in mind.
  - Interdisciplinary field focusing on how people interact with computers and technology.
  - Integrates principles from psychology, design, computer science, and engineering.
- Create interfaces that are intuitive, efficient, and accessible to diverse users.
- Involves methods like user testing, prototyping, and iterative design.
- User-centered design to make technology more adaptable and responsive to human needs.

## Core UI/UX & HCI Principles
- **Usability**: Definition and components (effectiveness, efficiency, satisfaction).
   - **User-Centered Design (UCD)**: Emphasize user involvement in the design process.
   - **Affordance & Signifiers**: Elements that make UI interactions intuitive.
   - **Feedback & Visibility**: Highlight the importance of providing users with cues about system status.
   - **Accessibility**: Overview of designing for diverse users (e.g., color contrast, screen readers).
   - **Consistency**: Importance of uniform design across the application.
   - **Interaction Design**: Discuss design patterns that improve interaction (navigation, layout, etc.).

## UI/UX/HCI Assessment Frameworks
When it comes to design there are a few evaluation tecniques we can ensure that we following the rules of the UX Honeycomb.
1. Systematic Human Error Reduction and Prediction Approach (SHERPA). SHERPA emphasizes the developer to consider user needs and optimize functionality across various platforms. They use a methodical design process called hierarchical analysis that involves breaking down a task into sub-task to make sure that by the end goal any forseeable error in the function is caught.
  - [Resource Link](https://core.ac.uk/download/pdf/334415.pdf)
2. The System Usability Scale (SUS): Created by John Brooke, the SUS has been tried and tested over almost 30 years of use. Constructed similar to a Likert scale, the SUS has 10 questions that refer to the end product, and users will then rate the agreeability to these question on a scale of 1-5: 1 being 'disagree' and 5 being 'agree.'' Then, through a very simple calculation, you can obtain the SUS score. This can help a developer identify where there design might be weak allowing for a more precise fix.
  - https://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/
  - https://www.interaction-design.org/literature/article/system-usability-scale
3. A cognitive walkthrough: This is a simple technique that is used to aid in understadn the learnability of a system to a new user. Essential this allows for a reviewer(s) to walk thorugh a task and provide feedback based on their presective of a new users. This is a cheap way to take an object look at the product to ensure that it is user friendly to all users.
  - https://www.nngroup.com/articles/cognitive-walkthroughs/

## Some References
* https://en.wikipedia.org/wiki/Human%E2%80%93computer_interaction
* [UI in Minority Report](https://www.theawl.com/2013/02/how-minority-report-trapped-us-in-a-world-of-bad-interfaces/)
