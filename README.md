# INFO 4940/5940-011: How LLMs work, their potential and limitations
Spring 2026

MW 10:10 - 11:25, Hollister 366

### Instructor: Jacob Matthews (jam963)
#### PhD TA: Zhiwen Qiu (zq76)
#### MPS TA: Karam Hejazin (kh878)
#### Undergrad TAs: Cathy Zhao, Sruthi Sentil, Samruddhi Oke, Sofie Cole

### Office Hours (as of 01/28)
Jacob: M 12:30-13:30, Gates 223

## Setup
Clone this repo:
```
git clone https://github.com/jam963/info-4940-llms-s26.git 
```
[Install `uv`](https://docs.astral.sh/uv/getting-started/installation/) if you haven't already, then
```
cd info-4940-llms-s26
uv sync
```

# Syllabus

### Credits and Credit Hour Options
- 3 Credits, letter grade only
- Graduate students will complete an additional research project

### Prerequisites 
Familiarity with data-oriented programming in Python, including numpy. You should be comfortable with quantitative machine learning techniques such as model training, data manipulation/cleaning, and descriptive statistics. 

## Course Description
Large language models (LLMs) are ubiquitous. This course is about how they work, understood in both a technical and holistic sense: what's going on inside these models, and how do they interact with the rest of the world? 

More specifically, this course will cover: 
- What a (large) language model actually is and how it compares to other types of ML models
- The current LLM ecosystem
- Prompting, "thinking", in-context learning, finetuning
- How LLMs are evaluated
- How to interpret what LLMs are doing 

## Course Structure and Mechanics
Wednesday sessions will cover technical background, while Monday sessions will be focused on collaborative, hands-on activities. We will use class time to work together (in small groups or as an entire class) and share results. 

This course should be accessible to anyone with the proper pre-requisites. If you have any form of documented disability that affects your ability to participate fully in the course, we will work with you to ensure that you have the best possible chance to succeed. For all students, we ask that you be proactive in communicating with course staff about any life circumstances that may affect your engagement or performance in the course. 

## Course Materials
Everything required for the course will be available either on Github or CMS. Make sure that you're watching/starring this repo and staying up to date. 

## Assessment 

| Category                            | Ugrad | Grad |
|-------------------------------------|-------|-------|
| In-class Worksheets (participation) | 15%   | 15%  |
| Take-home assignments               | 35%   | 25%  |
| In-class Exams (2)                  | 30%   | 30%  |
| Final Presentation                  | 20%   | 10%  |
| Graduate Research Project           | 0%    | 20%  |

The grading scale is numeric, with scores >= 97 A+, 93 A, 90 A-, 87 B+, etc. There is no curve. 

**You must pass each component of the course to pass the class.** A score below 63% in any of the above categories will result in an overall grade of F. 

### In-class Worksheets
To encourage attendance, participation, and engagement with material, you will complete short worksheets in class on an approximately weekly basis. They will not be announced in advance of the day that they are assigned. These worksheets are graded for *engagement*, not correctness: all work that clearly shows effort and thought will receive full credit. Worksheet solutions will be posted here.

### Take-home assignments
Assignments will alternate between individual and group-level assignments. They will have both coding and written components. They will be available on CMS.

### In-class Exams
This course will have two exams (see the Schedule below). They will be completed during normal class sessions[^1] without collaboration, notes, or cheatsheets. The best way to prepare for the exams will be to attend class, complete in-class activities, and do the homework. 

### Final Presentation
All students will complete a group Final Presentation during finals week. This short presentation will discuss related material (research, products, methods, etc.) that we did not cover explicitly in class. Graduate students are required to present the results of a more substantial research project (see below). More information will be posted closer to the end of the semester.

### Graduate Research Project
In addition to the Final Presentation, graduate (Masters and PhD) students will complete a short written report on their chosen research topic. More information about the Research Project will be posted in due course.

## Attendance Policy
Attendance is mandatory. You must attend all lectures. *In-class worksheets cannot be made up outside of class time.* Because life is unpredictable, you may miss two worksheets and still receive full credit. If you attend every class and complete all worksheets, you will receive a small amount of extra credit.[^1]

## Slip Day Policy
In the same spirit as the course Attendance Policy described above, we will not grant extensions to homework deadlines[^1] on an individual basis outside of truly exceptional circumstances. Instead, everyone will be given 5 total slip days for the whole semester. You can use them how you wish, but *it is up to you to keep track of them*: CMS will not stop you from exceeding your total allowance of slip days. If you turn in an assignment after a deadline with no remaining slip days, you will receive a zero on that assignment. For group assignments, slip days are still counted on an individual basis: if you are out of slip days, your group must turn the assignment in on time for you to receive credit, regardless of how many slip days other members of your group may have. *Slip days **may not** be used for Worksheets, Exams, Presentations, or Projects*.  

## Generative AI Policy
You are permitted to use AI under the following conditions. 
- You may *apply* AI *to* your writing, but you may not *substitute* AI for your writing. Generating text and code can be helpful, but a key goal of this course is to build condidence in indepedently organizing, designing, and writing.
- Everything that you turn in should be text that you or your group members have typed unless otherwise specifically indicated. In other words, you may use AI tools to check, debug, or critique, but not to actually *do* any part of assignments or projects.
- **There is zero-tolerance for "AI slop".** Course staff reserve the right to identify and penalize assignments with the characteristics of "AI slop". 


## Schedule

| Week | Monday | Wednesday |
|------|--------|-----------|
| 1 (1/19)   | No class | Intro: What is an LLM? | 
| 2 (1/26)   | Use cases and key players |  Inference w/ Hugging Face | 
| 3 (2/02)   | Predictions and representations | Prompting vs. Training | 
| 4 (2/09)   | What makes a good prompt? | Neural Networks |
| 5 (2/16)   | No class (Feb. break) | Gradient descent and AdaGrad |
| 6 (2/23)   | Finetuning a small LLM | Tokenization | 
| 7 (3/02)   | Training and comparing tokenizers | Attention, embeddings, transformers | 
| 8 (3/09)   | **Exam 1 (covers weeks 1-6)** | Data, alignment, societal impacts | 
| 9 (3/16)   | Exploring (pre/post)training datasets | Instruction tuning | 
| 10 (3/23)   | Comparing base and instruction-tuned models | RAG and embedding models | 
| 11 (3/30)  | Similarity, retrieval, prompting | Efficiency (quantization, LoRA) | 
| 12 (4/06)  | Spring break | Spring break | 
| 13 (4/13)  | Impacts of quantization | Interpretability methods | 
| 14 (4/20)  | Exploring SAEs and linear probes | Agents and tools |
| 15 (4/27)  | **Exam 2 (covers weeks 7-13)** | Multimodality | 
| 16 (5/04)  | Summary and wrap-up    | No class | 

Final presentations and final project deadlines will be due after classes end (date TBD). 
Please note that this schedule is subject to change. Check this repo frequently to ensure that you are up to date. 



[^1]: If you have a relevant SDS accommodation that would be affected by this policy, please discuss this with me as early as possible (i.e. well in advance of any deadline or missed class) so that we can make the appropriate arrangements. 



