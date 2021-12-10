## Lock-free Skip List
Team members: Chen He, Yida Wu

### Links

* [Web Page](https://supertaunt.github.io/CMU_15618_project.github.io/)
* [Proposal](./15618_project_proposal.pdf)
* [Milestone Report](./15618_project_milestone.pdf)
* [Poster](./15618_project_final.pdf)
* [Final Report](./15618_project_presentation.p)

### Summary

We implemented three versions of the skip list including a coarse-grained lock-based version using a global mutex, a fine-grained lock-based version based on multi-level locking and a lock-free version using CAS. Given the experimental results on a 8-core shared memory multiprocessor, we demonstrate the performance of the fine-grained lock-based version and lock-free version and their benefits and drawbacks.

### Schedule 

| Timeline       | Task                                                        | Progress    | Assigned |
|----------------|-------------------------------------------------------------|-------------|-------------|
| 11/04 - 11/08  | Investigate on the research paper and discuss the idea.     | Done | Together |
| 11/09 - 11/15  | Implement coarse-grained version of skip list.              | Done | Together |
|                | Implement  the contain function in the fine-grained skip list. | Done | Yida Wu |
|                | Implement  the insert function in the fine-grained skip list. | Done | Yida Wu |
|                | Implement  the delete function in the fine-grained skip list. |  Done | Yida Wu |
| 11/16 - 11/22  | Implement insert function in lock-free skip list            | Done | Chen He |
|                | Implement delete function in lock-free skip list            |  Done | Chen He |
|                | Implement contain functions in lock-free skip list            | Done | Chen He |
|                | Finish milestone report.                                     | Done | Together |
| 11/23 - 11/26  | Finish remaining part of delete function in lock-free skip list. |  Done | Chen He |
|                | Finish the remaining part of the delete function in the fine-grained skip list. |  Done | Yida Wu |
| 11/27 - 11/28  | Verify the correctness for the implementation and fix problems. | Done | Together |
| 11/29 - 12/03  | Design test cases to evaluate performance. | Done | Together |
|                | Conduct performance evaluation. | Done | Together |
| 12/04 - 12/09  | Finish final project report. |  Done | Together |
|                | Finish poster. | Done | Together |















