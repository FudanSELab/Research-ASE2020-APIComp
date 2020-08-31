# examples of API selection task

1. From the Stack Overflow question [Instant vs LocalDateTime - When to prefer one over the other](https://stackoverflow.com/questions/35251000/instant-vs-localdatetime-when-to-prefer-one-over-the-other), the scenario description "I need to save and present datetime of events that happened in my server in UTC. I have the option of using Instant.now() or LocalDateTime.now()" is proposed by the questioner of the post. The comparison APIs are java.time.Instant.now() and java.time.LocalDateTime.now(java.time.ZoneId).


2. From the Stack Overflow question [What is the difference between getDeclaredConstructors and getConstructors in the Class API?](https://stackoverflow.com/questions/8249173/what-is-the-difference-between-getdeclaredconstructors-and-getconstructors-in-th), based on the problem description, we define the scenario description "what is the purpose of accessing a private constructor?". The comparison APIs are java.lang.Class.getConstructors() and java.lang.Class.getDeclaredConstructors().

3. From the Stack Overflow question [Differences between HashMap and Hashtable?](https://stackoverflow.com/questions/40471/differences-between-hashmap-and-hashtable), the scenario description "Which is more efficient for non-threaded applications?" is proposed by the questioner of the post. The comparison APIs are java.util.HashMap and java.util.Hashtable.


For all API selection task results, you can view the [file](https://github.com/FudanSELab/Research-ASE2020-APIComp/blob/master/RQ6/result/GA/)