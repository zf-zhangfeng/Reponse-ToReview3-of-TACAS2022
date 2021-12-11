## Response to Review 3:

Thank you very much for carefully reviewing our work, we will improve our draft according to your valuable comments, remove the typos and make the presentation more clear. 

8.	We are very sorry that we can’t describe clearly the transition relation “\phi”: Firstly, the \phi indeed defines a transition relation rather than a function. Secondly, this transition relation is used in the execution of the OS model, which can be used to generate the operational semantics.
9.	We think that it’s difficult to ensure that the formalization actually captures the semi-formal standard description. Specification validation and test can help to address this problem, which actually has been partially carried out in our work. The conformity proof also helps to address this challenge. 
10.	At the end of Section 2, "... multiple partitions execute on different cores concurrently", we should not substitute "concurrently" with "simultaneously". We can use "parallelly", but researchers rarely use the word "simultaneously" in the context of concurrent and parallel executing.
11.	We will add the rigorous and clear definition of “concurrency”.
12.	We are very sorry that we didn't describe clearly the type "mtxSta" which is a to the type MUTEX_STATE_TYPE and the type MUTEX_STATE_TYPE can present a "status information" of a mutex.
13.	The "procCntxt" is at the third line from last in Figure 4.
14.	The "interC" is just a filed name for a data type in Isabelle/HOL, which represents inter-partitinon communications.


