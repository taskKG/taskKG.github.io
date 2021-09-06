# Replication Package for Helping Developers Write Better How-To Questions using a Task Knowledge Graph

## Motivational Study

- [Task-Related Question Selection](https://github.com/taskKG/taskKG.github.io/blob/main/task_post_data/Task-Related_Question_Selection.xlsx). In Section III Motivational Study. We randomly selected questions with title edit records from the dump and manually removed questions not related to tasks. The sampling and removal were conducted several times until we obtained 410 task-related questions. The manual removal was conducted by two students independently (two MS students, both with more than four years Java experience). This [xlsx](https://github.com/taskKG/taskKG.github.io/blob/main/task_post_data/Task-Related_Question_Selection.xlsx) file includes all questions we sampled. As a result, we annotated 737 question and 410 questions are task-related and 327 questions are not related to task. Each row in xlsx file corresponds to a sampled question with our annotation. The last three columns, “annotator1”, “annotator2”, “arbitration” indicate the results of the two annotators and the final arbitration result respectively. 0 means that the question is not task-related, and 1 means that the question is task-related.
- [Task-related Questions with Title Edit Records](https://github.com/taskKG/taskKG.github.io/blob/main/task_post_data/Task-related_Questions_with_Title_Edit_Records.xlsx). It contains sampled 410 task related questions with title edit records. The “posthistoryTypeID” colunm, ‘1’ represents the initial question title and ‘4’ represents a title edit record. The Text field is the current title of the question. The edit records for the same question are arranged in chronological order. 
- [Edit Record Classification](https://github.com/taskKG/taskKG.github.io/blob/main/task_post_data/Edit_Record_Classification.xlsx). This file includes the manual classification results for sampled title edit records. We classified the edit record into four categories: Edit Action、Edit Object、Edit Constraint and Others. Last four columns indicate the classification result for those four category. “1” represents that the edit record belongs to the category and “0” represents that the edit record doesn’t belong to the category.

## Experiments
- [RQ1](https://github.com/taskKG/taskKG.github.io/blob/main/RQ/RQ1.replication.xlsx). We evaluate the intrinsic quality of the task KG by assessing the correctness of the annotated questions in the task KG. 
- RQ2. We compared ChatBot4QR and TaskKQ4Q through [18 questions](https://github.com/taskKG/taskKG.github.io/blob/main/SOQuestions.xlsx) from Stack Overflow.(The implementation of ChatBot4QR we obtained comes from [here](https://osf.io/npwg4/?view_only=560f6453f31a439db469d7fe4c82dbec)) We invited 9 participants to use different tools to complete the title of the corresponding question. Evaluate and get the [results](https://github.com/taskKG/taskKG.github.io/blob/main/Result.xlsx).
- RQ3. We evaluate the usefulness of TaskKQ4Q by asking participants to complete a set of programming tasks. When they need to learn how to solve a specific task, we ask them to find the specifics on Stack Overflow. They do that writing questions on their own and with the TaskKQ4Q tool. 
  - [Participants Selection](https://github.com/taskKG/taskKG.github.io/blob/main/experiments/Participants_Selection_Questionnaire.docx). To recruit participants, we used a questionnaire to select 16 qualified students from a class of 49 students as participants. The questionnaire assessed their programming knowledge and whether they would need help to complete the four given programming tasks. The doc is the questionnaire to select participants.
  - [Programming Tasks](https://github.com/taskKG/taskKG.github.io/blob/main/experiments/TaskList.replication.docx). Tasks with detail context. The file includes all tasks with detail context.
  - The KG we built will be released after the paper is accepted.

