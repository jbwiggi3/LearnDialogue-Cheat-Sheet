# [LearnDialogue Cheat Sheet](https://github.com/jbwiggi3/LearnDialogue-Cheat-Sheet/)
### Being a Mentor

[LearnDialogue Website](http://research.csc.ncsu.edu/learndialogue/)

## Mentoring
Throughout your graduate career there will most likely be times where undergraduates will help out on projects, completing a REU (or Research Experience for Undergraduates). It is important to be aware of the differences between undergraduates and graduate students, but also not underestimate the significant contributions that undergraduates are capable of during their time with the lab. Here are some items to keep in mind: 
- Undergraduates will have a smaller amount of time for the research, most likely 10 hours a week, and assignments given to them should have these time restraints in mind
- The undergraduates may or may not come from a Computer Science background, and these differences should be considered when developing a project for them to work on
- Undergraduates should usually not be assigned mission critical items for research projects

As a mentor, it will be your responsibility to bring them into the academic world and allow them to test the waters and see if it is a potential career they would be interested in.

### General Structure for Student Project:
1. Get to know the student: What are the students general interest? How do these related to the group? How much do they understand about the academic world? What are their strengths?
2. Help them conduct a guided literature review: Assign a few papers that surround their interests and get the student to read them. Have meetings with the student where you talk about their reflections from the paper and their strategies when reading the paper. Try to pick the following papers based on the direction that the previous paper took the student.
3. Allow student to bring some papers to you: Teach the student how to look up research papers on their own and send you a paper they find interesting. Get them to have more control in the discussions around these papers.
4. Help them develop a research question: Considering the student's interests, help them formulate a research question which could at least potentially be a workshop paper submission. It doesn't have to be super novel, just not done on the project yet.
5. Get the students to look up other papers that have asked similar questions: Tell the student to look carefully at the methods the author's of these papers used when answering the questions. What statistical tests were used? What kind of sample? Are there any places they might be able to think of improvements?
6. Do that research: Now the students can try to take the analysis plan that they have formed and run with it. Let them work on this and check in periodically. It is not a bad idea to have some small simple analysis that you could review with them before they move on to a bulkier analysis.
7. Review: Talk with the students about there findings. What does this mean? Does it support other findings? What directions does it make them consider?
8. Write it up: Help the students combine their work into a short paper just to complete the process. This could be run past Dr. Boyer at some point for her to talk about with the students and even potentially get them a publication.

### Sample Past REU Projects:
- Automatic Facial Expression Detection: The undergraduate worked with a tool for automatically tagging facial expressions, and developed a dataset of facial expression data for the JavaTutor Intelligent Tutoring System
- Dialogue Act Classification: The undergraduate reviewed the dialogue interactions from the JavaTutor corpus and the literature on tutorial dialogue act tagging to come up with a set of dialogue act tags that more accurately represented the dialogue exchanges between students and tutors. The student then tagged the corpus, and had another undergraduate tag a subset so that a kappa could be calculated. Then the student built an automatic dialogue act classifier using NLP and machine learning.
- Recognizing Student Certainty in Spoken Utterances: The undergraduate conducted a literature review on prosody and found tools which could be used to calculate prosody features (such as frequency, intensity and cadence). Features were iteratively developed to combat gender differences (such as only considering relative frequency features) and to give a rich description of the utterance (such as considering the utterance as a whole, but also the beginning, middle and end of each utterance). These features were then used to predict student certainty using certainty tags that were tagged by the student and verified by a kappa calculated using a friend's tags.
