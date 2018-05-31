# zombie_cluster_test

This project is the result of a test I had to pass after applying to a position of Data Scientist at Machine Learning consulting company in 2017.

## The test - as provided by the company

Briefly, the task has two parts:
(1) soft-skills part: imagine we have three projects to do now, how will you manage work in our team?
(2) technical part: solve one of the tasks.

Here are details:

### 1. You are a manager.

Let’s imagine that we have ten people, some are experts in software engineering, some in machine learning/optimization, some have experience with databases, and some are great with visualization tools. We just secured three contracts. Thus, our goal is to solve problems for three clients (see tasks: Rescue stations, 911 call center working hours, and Navigation) and we have to present our idea for a solution and demos to each client within 1.5 months.
- How will you schedule work to meet the deadlines?
- Which particular solutions/directions will you suggest to our employees so that they don’t explore too many wrong methods?
- Write your solution in one page (max). Add only important and relevant information there.
- You can use figures, graphs, etc. if it helps.
- It’s your imagination, so you can be as crazy as you want to be :-)

### 2. Technical part.

Solve one of the three tasks (_I am showing only one here_) mentioned above and described below (you can choose which one you’d like to tackle).
- Show results in the form of a two page (max) paper - shorter is better. Only important information should be there.
- You can use whatever programming language or tool you choose (Keep in mind license requirements and costs and don't assume the existence of any licensed software at this stage). Send the code with your solution too, please.
- If you are familiar with data-processing algorithms and machine learning, it should be a two-night problem.
- Pictures, equations, graphs....everything is very welcomed in your document.
- In your solution, it will be also beneficial if you shortly discuss the following:
- If you had more time to solve it, what more would you do?
- What are the limitations of your solution?
- In the report, discuss which technique you used. Why is your method suitable for the solution?


### Task: Rescue stations

**Data** : https://storage.googleapis.com/montco-stats/tz.csv

Here is data from accidents that happen in city XYZ.
Evil zombies have destroyed all central rescue stations in the city. The state has statistics where emergency problems occurred in last year (data above) and they are not sure whether the emergency stations were placed efficiently. Note that ambulances were sent only to EMS problems. Therefore, they asked us to find places where they should build 5 (of the same size) emergency stations. What will their position be? (for the sake of simplicity, you can use manhattan distance, but you can also link it to the real geographic distance if you want :)