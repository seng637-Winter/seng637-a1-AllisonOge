>   **SENG 637 - Dependability and Reliability of Software Systems**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: 19|
|-----------------|
| Sami Abdelhalem |   
| Mohammad Hallaq |   
| Ogechukwu Kanu |   
| Olayinka Afolabi |
| Emmanuel Alafonye |


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

# Introduction

Exploratory testing is particularly valuable in the initial phases of development, especially when documentation is limited. It involves testers actively delving into the application, gaining insights into its features, and executing test cases in real time. This approach relies on the tester's domain knowledge, experience, and creativity to dynamically design and execute test cases, often without predefined scripts. It proves beneficial for discovering unforeseen defects, validating assumptions, and testing the application in an open-ended fashion. 

Manual testing is the process of hands-on validation of software for defects, conducted without the assistance of automation tools. Testers adhere to predefined test cases, systematically executing them and comparing the actual outcomes with the expected results. The primary purpose of manual testing is to address scenarios where automation proves impractical or cost-prohibitive, such as exploratory testing, usability testing, and ad-hoc testing. Additionally, manual testing proves advantageous in the early phases of a project when the application is undergoing rapid changes.

The lab is segmented into four primary sections:
1. Introduction to the System Under Test (SUT) and the defect tracking system.
2. Exploratory testing which was conducted manually without predefined scripts.
3. Manual scripted testing.
4. Regression testing which involved re-evaluating a system after modifications.
During the initial familiarization phase, we delved into the software system to be tested (referred to as the System Under Test, or SUT) and the JIRA defect tracking system. In the exploratory testing stage, we had the liberty to test the system in any manner we preferred. Upon transitioning to the manual scripted testing phase, we were mandated to utilize a predefined test manual to test the SUT. Lastly, we conducted a straightforward regression test on an updated version of the system (altered by fictitious developers in response to a list of defect reports) and appropriately updated the bug report in the defect tracking system.

# High-level description of the exploratory testing plan

The test plan was designed to state the objective, scope, duration and approach taken to test the SUT.

**Objective:** The objective of the exploratory testing is to uncover defects, and assess the implementation of system requirements and system usability by creatively and intuitively exploring the application.
Scope: The testing will focus on all functionalities stated in the system requirements.

**Duration:** The exploratory testing phase is planned to span about 24 hours, allowing testers to thoroughly explore the application.
### Approach:
**Familiarization:**
Testers will familiarize themselves with the application and any available documentation. Testers will understand the client’s requirements and use the information as a basis to explore the application. Identify critical features, user workflows, and potential risk areas.

**Testing Sessions:**
Testers will conduct exploratory sessions focusing on different aspects of the application. Sessions will be dynamic, allowing testers to adapt their testing approach based on findings.

**Documentation:**
Document test scenarios, observations, and any defects discovered during testing. Prioritize and report critical issues promptly.

**Feedback and Collaboration:** 
This test is conducted in groups of two/three who will collaborate and share insights during the testing process. 
Feedback sessions with the rest of the team will be conducted to discuss findings.

**Exit Criteria:** The exploratory testing phase will conclude when sufficient coverage is achieved, critical issues are identified and reported, and the testing objectives are met.

# Comparison of exploratory and manual functional testing

**Exploratory testing** embodies a dynamic and adaptable methodology in which testers concurrently devise and execute test cases. Instead of adhering to predetermined scripts, testers explore the application freely, drawing on their experience and intuition. This approach affords testers the flexibility to modify their testing strategies based on real-time observations and feedback, fostering creativity and the capability to uncover unforeseen issues. Moreover, upfront planning is kept to a minimum, facilitating swift adjustments to changes in the application. However, the success of exploratory testing heavily relies on the tester's skills, experience, and domain knowledge. Testers acquire knowledge about the application during testing, adjusting their approach as they unearth more insights. The emphasis is on immediate feedback and addressing issues promptly rather than on creating extensive documentation.

**Manual functional testing** encompasses the development and execution of pre-established test cases derived from specifications and requirements. Testers adhere to a predefined set of test cases, limiting the flexibility to investigate unforeseen scenarios. The repetition of test cases is permissible to uphold consistency and reliability. This testing method necessitates meticulous planning and documentation of test cases before execution. The effectiveness hinges on the precision and comprehensiveness of both the test cases and accompanying documentation. Testers can reliably execute predetermined scenarios, a crucial aspect in regression testing. Finally, it entails the thorough documentation of test cases, test steps, and anticipated results.

# Notes and discussion of the peer reviews of defect reports

We deliberated on the sufficiency and comprehensiveness of the test cases, addressing queries about the coverage of all relevant scenarios and identifying potential gaps in test coverage. Our initial focus was on scrutinizing the requirements and ensuring the alignment of test cases with the specified criteria. We engaged in discussions about any discrepancies or deviations to promote accurate testing. Feedback regarding the clarity and understandability of the test cases was also provided, with particular attention given to addressing ambiguous or unclear instructions.
For test cases with repeatability, we delved into the importance of consistency to ensure uniform results. Any concerns related to variability in test outcomes were duly discussed. We underscored the significance of documentation quality, emphasizing the need for clear articulation of test steps and expected results. Any suggested improvements or clarifications in the documentation were brought to the forefront.
Turning to the defect report, our peer review discussion encompassed the following considerations: meticulous notetaking to evaluate the clarity of defect descriptions. Recognizing that ambiguous or unclear defect reports could impede the debugging process, we devoted attention to this aspect. Reproducibility of reported defects was another focal point, with discussions centering on unclear or inconsistent steps for reproducing defects. The discussion also delved into the assigned severity and priority for each defect, with input provided to ensure alignment with the impact on the system and the urgency for resolution.

# How the pair testing was managed and team work/effort was divided 

During the exploratory testing stage, the team formed pairs or groups of three to conduct the test. In these pairs or groups of three, one member communicates the testing procedure to uncover a bug while another member reports the bug in the tracking software. A detailed table showing the subgroups and members is shown in Table 1.  The tracking software was accessible to all members of the team and a format for reporting bugs was reached for uniformity. Whereas in this manual scripted testing stage, the team divided the tests equally among themselves and properly communicated how the defects in the bug-tracking software would be reported to distinguish them from those of the exploratory test. After the manual scripted stage was completed successfully, each member worked either individually or in pairs or groups of three on the regression testing with version 1.1 of the SUT using the defects reported in the tracking software and updated any defects that were fixed as well as reported any new bugs that were found along the way. In this stage, we also resolved similar defects reports or overlapping defect reports by linking them in their appropriate manner or completely deleting ones that were totally similar to another.
> Table 1. Team members of subgroups for exploratory testing of the SUT

| **Teams** | **Members**|
| ---------- | ---------- |
| 1          | Mohammad Hallaq <br/> Ogechukwu Kanu |
| 2           | Sami Abdelhalem <br/> Olayinka Afolabi <br/> Emmanuel Alafonye|


# Difficulties encountered, challenges overcome, and lessons learned
During the laboratory session, our team faced several challenges, both on an individual and collective level. The process of identifying bugs and defects during the exploratory testing stage significantly improved as we gained a deeper understanding of the System Under Test (SUT). This improvement was a direct result of dedicating time to familiarize ourselves with the system requirements and the intricacies of the SUT, enabling us to uncover outcomes that deviated from the specified requirements.
Collaboration played a pivotal role in overcoming these challenges. As we worked together on tasks, there was a meaningful exchange of ideas and thoughts derived from individual studies. This collaborative approach enhanced our collective understanding of the SUT and contributed to a more effective identification of defects. Recognizing the importance of teamwork, we not only learned how to conduct individual tests proficiently but also grasped how these tests interconnect within the context of the lab.
In essence, the challenges encountered in the lab became opportunities for growth and improvement. Our collaborative efforts not only deepened our understanding of the SUT but also fostered a more comprehensive and efficient testing process.

