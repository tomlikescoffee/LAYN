# LAYN - Love Is All You Need (And Exam Timetabling)

During my second year of university one of my chosen modules was Artifical Intelligence Methods (AIM) which focused on how heuristics are employed to provide acceptable solutions to NP-complete problems within a reasonable time frame. NP-complete problems are ones where verifying a proposed solution may not take very long but actually finding the solution may take an incredibly long time. Whilst the module itself focused on the bin-packing problem and the travelling saleman problem (TSP) one problem that caught my interest was the graph-colouring problem. 

The graph colouring problem can be summarised as assigning colours (or some other label) to each vertex in a graph such that neighbouring vertexes connected by edges do not share the same colour (or label). The graph colouring problem is NP-complete for all K >= 3 (where K is the number of labels) and has several real-world applications such as resource allocation (scheduling), compiler optimisation and solving sudokus.

As of the time of writing this, it has been over two years since I completed the AIM module and as time has passed I've inevitably begun to forget some of the content taught in the module which is a shame as it was one of my favourite modules. 

Which brings me to the purpose of this project LAYN, with the following goals: 

- Relearn or brush up on forgotten content from the AIM module (hyerheuristics, genetic algorithms, heuristics)
- Learn new or different Artifical Intelligence methods to balance exploratoin vs exploitation   
- Learn a new programming language (C++)
- Learn about common DevOps tools (docker, CI/CD pipelines, testing, GitHub Actions) 
- Use everything learned to develop a tangible exam timetabling application

I've chosen C++ as I've wanted to learn the language for quite a while and enjoyed using C whilst at university. Furthermore, prior projects have been written solely in Python and I use the langage on a daily basis professionally so learning a different language that's a little more low level will be a nice change of pace. 

DevOps is an area of software developnment I have significant knowledge gaps in and figured there would be no time like the present to try learn more about setting up CI/CD pipelines and using tools like docker for deployement. 

Fundamentally the main goal of this project is to successfully develop an application that given a list of students, a list of exams and a set of available rooms can produce a timetable that includes as few overlapping exams for a given student as possible. This can then be extended to accomodate different hard and soft contraints like restricting the exams to a specific time period (e.g. two weeks), restricting exams to certain rooms (e.g. IT exams can only be done in rooms with computer accss), giving rooms and occupancy limit or having preferred slots for exams (morning, afternoon evening). Learning C++ and DevOps are considered secondary goals that can be completed in tandem with the main project goal.  

