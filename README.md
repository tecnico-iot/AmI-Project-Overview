Instituto Superior Técnico, Universidade de Lisboa

**Ambient Intelligence**

# Project Overview

This document describes the organization of the project for the Ambient Intelligence / _Ambientes Inteligentes_ (AmI) course.

The document concludes with a calendar containing all the important dates.

For any questions regarding this document, please contact:  
[meic-ami@disciplinas.tecnico.ulisboa.pt](mailto:meic-ami@disciplinas.tecnico.ulisboa.pt)

# 1 Introduction

The AmI (Ambient Intelligence) course requires a practical project dealing with so called "smart" technologies.  
The whole process is organized in sequential stages, covering team formation, topic selection, proposal development, project execution, and presentation:

| **Stage**                                                                             |
| --------------------------------------------------------------------------------------|
| [1. Assemble team](#21-assemble-team)                                                 |
| [2. Pick topic area](#22-pick-topic-area)                                             |
| [3. Register team](#23-register-team)                                                 |
| [4. Present team and idea](#24-present-team-and-idea)                                 |
| [5. Write proposal with literature review](#25-write-proposal-with-literature-review) |
| [6. Submit and await feedback](#26-submit-and-await-feedback)                         |
| [7. Develop project](#27-develop-project)                                             |
| [8. Prepare demonstration](#28-prepare-demonstration)                                 |
| [9. Write report](#29-write-report)                                                   |
| [10. Submit code and report](#210-submit-code-and-report)                             |
| [11. Confirm presentation session](#211-confirm-presentation-session)                 |
| [12. Present and defend](#212-present-and-defend)                                     |  

<br />

# 2 Stages

Each stage of the project is described in the following sections.

## 2.1 Assemble team

Assemble a team of 3 students, committed to work together, and enrolled in the same laboratory schedule.

## 2.2 Pick topic area

The specific topic for the project should be selected by the project team.

We suggest that the team starts by selecting one of the following broad topic areas:

1. Smart Buildings  
2. Industry & Supply Chain  
3. Smart Cities  
4. Assisted Living

You can adapt ideas presented in the lectures or propose a new one.

## 2.3 Register team

Go to Fénix and register your team, on the laboratory schedule where all the team members are enrolled.  
You are expected to complete this registration before the first laboratory session.

Even if you do not have a full team yet, attend the first laboratory session, to meet colleagues also looking for a team.

Make sure your photograph is up-to-date and of good quality on Fénix.  
If your photo is not good enough, go to Fénix, Personal, Photograph, hover photo with mouse, Submit Photos.

## 2.4 Present team and idea

In the first laboratory session, each team will present its members and the initial project idea.  
Each team member should have one dedicated slide, featuring their name, concise biography, and prior experience with programming and hardware tinkering, e.g., projects with Arduinos or Raspberry Pis.  
The most important slide will present the initial project idea, including a title and a succinct description.  
You can present more than one idea, but no more than three.

## 2.5 Write proposal with literature review

After having chosen a topic, your team should prepare a proposal document.
The project proposal should describe the specific problem to address and the proposed solution.

Please bring a draft of the proposal to your next laboratory session to present it and receive feedback.  

One of the important parts of the document is the literature review.

### 2.5.1 Literature review

Your proposal must include a (small) literature review, focused on the topic area.
The review will start with a search for relevant scientific papers, where you will learn about the core concepts and approaches to similar solutions.
The bibliography should have two papers, from different authors.
These papers must have been published in a scientific journal or conference related with ambient intelligence in the last five years.

IMPORTANT: see [list of journals and conferences related with ambient intelligence](https://github.com/tecnico-iot/awesome-iot-ambient-intelligence#publications).  
You can also do an open search on sites like [Semantic Scholar](https://www.semanticscholar.org) or [Google Scholar](https://scholar.google.com).

### 2.5.2 Technical requirements

The planned project will need to include:

- sensors;
- actuators;
- network communication.

### 2.5.3 Document structure (mandatory)

1. Introduction  
_Provide an overview of the project, its significance, and objectives._
2. Literature Review  
_Summarize and cite the selected scientific papers, defining the main concepts, discussing strengths and weaknesses of the works, and influences they had on the proposal._  
_Expected size: approximately 200 words for each paper._  
3. Problem  
_Given the chosen topic area, what is the specific problem being solved?_  
_What is the value to be added by the proposed solution?_  
_Who are the stakeholders?_  
  3.1. Solution Requirements  
  _Enumerate solution requirements as a list of statements with numbered identifiers (R1, R2, ...)._  
  _Ensure each requirement is concise, specific, and testable, stating expected behavior without suggesting a specific solution._  
  3.2. Assumptions  
  _Which conditions are assumed to be true for the solution to operate as intended?_  
4. Proposed solution  
  4.1. Overview  
  _Present an architectural diagram and provide a brief explanation of all components._  
  4.2 Logical design  
  _Identify the main functions to be performed by the solution._  
  _Identify communicating entities and the messages they will exchange with a sequence or collaboration diagram._  
  4.3 Technology selection  
  _Identify the primary development platform (e.g. Arduino IDE, Android Studio, etc.)._  
  _Choose the programming language(s) for implementation._  
  _Describe the distinct devices and how they will be assembled and interconnected._  
  _Select communication technologies and protocols._  
  _[See suggestions](https://github.com/tecnico-ami/awesome-ambient-intelligence)._  
5. Bill-of-materials  
  5.1 Hardware  
  _Provide a list of required hardware components and their respective purposes._  
  5.2 Software  
  _Specify the tools and libraries to be utilized and their intended functions._  
6. Plan  
  6.1 Team organization  
  _Assign responsibilities to team members._  
  6.2 Tasks and milestones  
  _Outline the tasks for the project development._  
  _Define milestones of increasing functionality of the solution: basic, intermediate, advanced._  
7. Bibliography  
  _Provide the authors, title, and publication details of scientific and technical documents referenced in the proposal text._  
8. Declaration of Use of AI  
  _According to the Técnico template, as detailed further down._
  
Target size of document: 1000 words, limit 1500 words.

### 2.5.4 Additional document requirements

- PDF format;
- Mandatory file name `CXX_proposal.pdf`;
(where `C` is replaced with `A` for Alameda, `T` for Tagus, and `XX` is replaced with the Fenix group number with two digits);
- Report cover: Project title. Headed by course name, group campus, group number.
In the next row: group members sorted by ascending student number.
Include a team photo of the complete team, taken together, at the same physical location, arranged in sequence by ascending student number;
- Report body: The font should be no smaller than 11pt, with standard line and character spacing;
- The use of diagrams (such as UML or SysML) is recommended for clear and concise communication;
- Target size of 6 pages (including cover and bibliography);
- Pages must be numbered (preferably with a label like `Page X of Y`).

## 2.6 Submit and await feedback

Prior to the proposal deadline, submit a ZIP archive containing the proposal document and the literature review papers.

The proposal document will be read by the course faculty and you will receive feedback in the following laboratory session.  
Receiving the feedback is essential so that you can consider the proposal as approved, so be sure to attend in person.
Meanwhile, get started on the project.

## 2.7 Develop project

Develop project milestones over the available weeks.

Attend the lab sessions to present your ongoing development and receive early feedback from the faculty.  
A project that receives regular feedback can avoid mistakes, be improved earlier, and is more likely to achieve a better result.

## 2.8 Prepare demonstration

Write a [`README` file](https://gist.github.com/miguelpardal/dedf25563c37b8fa906fd8cf23b5daae) to be placed in the project's root directory, with step-by-step instructions to assemble and run your project.  
Take photos and record videos showing the project in action.

## 2.9 Write report

The project final report should describe the problem and the implemented solution, along with a presentation of the results.
The report document should update and extend the proposal document to reflect what was actually achieved.

### 2.9.1 Document structure (mandatory)

The report structure is the following:

1. Introduction  
2. Literature Review  
3. Problem  
  3.1 Solution Requirements  
  3.2 Assumptions  
4. Proposed solution  
  4.1 Overview  
  4.2 Logical design  
  4.3 Technology selection  
5. Bill-of-materials  
  5.1 Hardware  
  5.2 Software  
6. **Evaluation**  
  6.1 **Teamwork**  
  6.2 **Results**  
7. **Conclusion**  
8. Bibliography
9. Declaration of Use of AI  

The structure of the report document is similar to the structure of the proposal but the _Plan_ (old Section 6) is replaced by _Evaluation_ (new Section 6).
The _Teamwork_ (6.1) should review how the work was divided by the team.
The _Results_ (6.2) must present the main results and state which requirements (from Section 3.1) were actually satisfied (_satisfied_, _partially satisfied_, _not satisfied_) with brief explanations for each one.  
Finally, the _Conclusion_ (Section 7) should make a critical assessment of what was achieved, pointing out what the solution does well and where it could be improved in the future.

All sections must be updated to accurately reflect the final solution.

Target size: 1500 words, limit 2000 words

### 2.9.2 Additional document requirements

The changes to the proposal requirements are the following:

- Mandatory file name `CXX_report.pdf`;
- Target size of 10 pages (including cover and bibliography).

## 2.10 Submit code and report

Prior to the final deadline of the project, submit a ZIP archive containing all the developed code and resources.

IMPORTANT: the code archive and the report are submitted separately on the Fénix system.

### Code archive requirements

- ZIP format - without compiled code, only source and build scripts;
- The mandatory file name is `CXX_solution.zip`;
- `README` file, describing the required platforms, components, software, and setup instructions;
- All configuration files and scripts required to configure the solution on the specified platform;
- All developed source code;
- Existing tests and example files.

## 2.11 Confirm presentation session

The project presentations will occur on the dates following the submission deadline.  
The presentation session calendar will be made available during the final days of the project or after the submission.

Each group is assigned to a session, in their respective campus, preferably in the time-slot of laboratory they are enrolled to.  
If your group requires a change in the proposed slot, please contact faculty by email as soon as possible.

## 2.12 Present and defend

Each group will have to attend the full presentation session where they will present.  
The presentation slides must be in English and the presenters should also present in English.  
For the discussion questions, students can answer in Portuguese.

### 2.12.1 Presentation outline

The presentations will be organized as follows:

- 8 minutes for presentation of the work done, including a mandatory live demonstration  
(also prepare a video of the demonstration, as backup);
- 8 minutes for questions and answers.

It is highly recommended that each presentation includes the following slides:

- general architecture;
- setup process;
- operation process.

Each team member must participate and talk in the presentation, and be prepared to answer individual questions.  
If necessary, a more detailed discussion will be scheduled with each group.

### 2.12.2 Presence

The presentations are done by the whole group, in person, on campus.
Each group must attend from the beginning of their assigned session and remain for the duration of it.

Presenters need to be physically present in the lecture room.
Each student is also invited to attend another full session beyond the one where s/he will present.

### 2.12.3 Presentation archive requirements

IMPORTANT: after making the presentation, submit the presentation and media files on Fénix.

- ZIP format;
- The mandatory file name is `CXX_presentation.zip`;
- Presentation in PDF and also in source format (e.g. PowerPoint);
- Text file `url.txt` containing a download address for `CXX_media.zip`, an archive containing videos, photos, screenshots, and other media of the solution in action.
The link must be valid for one month after submission, at least;
- Optionally, the ZIP may also include an updated README and other files modified after the code submission.

### 2.12.4 Grading

The project grade will take into account:

- Literature review (10%);
- Project design/rational (20%);
- Project implementation (30%);
- Report (20%);
- Presentation (10%);
- Live Demonstration (10%).

If the demonstration is not live, then you forfeit that evaluation component.

----

# 3 Calendar

The relevant dates for the project are shown in the following calendar (all dates are in **2026**).

| **Stage**                    | **Deadline**                                                                      |
| -----------------------------|-----------------------------------------------------------------------------------|
| Assemble and register team   | Until Friday, February 20th, 20:00 or in the first lab                            |
| Present team and ideas       | In the lab session of Tuesday, February 24th                                      |
| Write proposal               | Until Friday, February 27th, 20:00                                                |
| Receive proposal feedback and approval               | In the lab session of Tuesday, March 3rd                                        |
| Receive feedback - basic               | In the lab session of Tuesday, March 10th                                        |
| Receive feedback - intermediate               | In the lab session of Tuesday, March 17th                                        |
| Prepare demonstration        | Start preparing midway through the development                                    |
| Receive feedback- advanced             | In the lab session of Tuesday, March 24th            |
| Write report                 | Regularly revise the document as progress is made                                 |
| Submit code and report       | **Code**: Tuesday, March 24th, 20:00. **Report:** Thursday, March 26th, 20:00     |
| Confirm presentation session | Until Friday, March 27th. Contact faculty if you have any issue with the schedule |
| Present and defend           | Sessions on Tuesday, March 31st. Submit presentation and media on the same day, until 20:00 |

## 3.1 Updates

IMPORTANT: keep track of the course [web site](https://fenix.tecnico.ulisboa.pt/disciplinas/AI3610/2025-2026/2-semestre) for announcements.

If there are changes to this document, they can be consulted in the _Git Commit History_.

## 3.2 Use of Artificial Intelligence

The Técnico [_Use of AI Guidelines_](https://tecnico.ulisboa.pt/en/news/campus-community/tecnico-apresenta-guia-para-a-utilizacao-responsavel-da-inteligencia-artificial/) defines levels of use.
For this project, they are:

- proposal and report - level 1 - yellow;
- code - level 2 - green.

### 3.2.1 Use of AI in proposal and report

<!--
**Level 0 (Red) – Prohibited Use**

At this level, the use of any AI tool is expressly prohibited at any stage of an assessment component, such as written or oral exams or the demonstration of a laboratory experiment. Students must complete the assessed work solely on the basis of their own knowledge and skills.

The corresponding pedagogical objective is to strengthen individual competencies in order to promote intellectual autonomy and technological independence.

Declaration of Use Template:

> “I declare that this assessment component was completed entirely without the use of any AI tools.”
-->

**Level 1 (Yellow) – Limited Use with Declaration Including Purpose of Use**

_At this level, the use of AI tools is permitted for tasks within an assessment component, such as idea generation, topic organization, brainstorming, language revision, structural suggestions, summarization, among others. Any generated content included in the final work must be reviewed and edited; therefore, a Declaration of Use and its purpose is required, including, if requested by instructors, the prompts used._

_The pedagogical objective is to foster the critical and ethical use of AI, encouraging students to take ownership of the creative process as well as the validation of content and bibliography in problem-solving tasks, thematic reviews, etc. This may include Laboratory Reports, Dissertations or Theses, PIC course unit reports, computational assignments, among others._

Declaration of Use Template:

> “All decisions and technical content in this work are my own.
> [List tools] were used for [functions].”

Example:

> “All decisions and technical content in this work are my own. 
> OpenAI’s ChatGPT (2025) [[https://chat.openai.com](https://chat.openai.com)] was used to generate the table of contents of this work.”

### 3.2.2 Use of AI in code

**Level 2 (Green) – Fully Permitted Use with Declaration**

_In this case, the use of AI tools is unrestricted and encouraged throughout the project/work. Students may use AI to generate, review, and complete content, provided they meet the assessment objectives. AI is understood as a collaborative tool, and its use must be declared._

_The pedagogical objective is to promote technological literacy and to develop the ability to integrate advanced AI tools into the planning and execution of engineering processes, innovation, and the resolution of complex or open-ended problems._

Declaration of Use Template:

> “AI tools were integrated into the development of the project. The following tools were used: [list tools].”

Example:

> “AI tools were integrated into the development of the project. The following were used:
>
> - OpenAI. (2025). ChatGPT [Large language model]. [https://chat.openai.com](https://chat.openai.com)
> - GitHub. (2025). GitHub Copilot [AI coding assistant]. [https://github.com/features/copilot”](https://github.com/features/copilot”)

----

## 3.3 Final words

We wish you all the best in this technical venture.
Make the most of it and we look forward to see what you will achieve!

----

[AmI Faculty](mailto:meic-ami@disciplinas.tecnico.ulisboa.pt)
