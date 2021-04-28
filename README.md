# taskKG.github.io

## Empirical Study

- [Task data selection](https://github.com/taskKG/taskKG.github.io/blob/main/task_post_data/judge_functional_issue_data.xlsx). In this data, we randomly select the post, and the field is_functional_issue_ is marked with a decision on whether it is a task post or not. The sampling and removal were conducted several times until we obtained 410 task-related questions. The manual removal was conducted by two students independently (two MS students, both with more than four years Java experience)
- [Task modify record](https://github.com/taskKG/taskKG.github.io/blob/main/task_post_data/judge_functional_issue_data.xlsx).In this data, it contains the post title modification record of the sampled task post. In the posthistoryTypeID field, '1' represents the original post and '4' represents the post title modification.The Text field is the current title of the post. We collected each title edit record with the previous version of question title (i.e., initial title or the last title edit record)
- [Task modify category](https://github.com/taskKG/taskKG.github.io/blob/main/task_post_data/task_post.xlsx). This data shows the manual classification results for each task post title modification category. We classified the edit record into four categories:Edit Action、Edit Object、Edit Constraint and Others.

## experiments
- [RQ1](https://github.com/taskKG/taskKG.github.io/blob/main/RQ/RQ1.replication.xlsx). We evaluate the intrinsic quality of the task KG by assessing the correctness of the annotated questions in the task KG. 
- [RQ2](https://github.com/taskKG/taskKG.github.io/blob/main/RQ/RQ2.replication.xlsx). We evaluate the effectiveness of TaskKQ4Q by asking participants to complete a set of programming tasks. When they need to learn how to solve a specific task, we ask them to find the specifics on Stack Overflow. They do that writing questions on their own and with the TaskKQ4Q tool. 
 
