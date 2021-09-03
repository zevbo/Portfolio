# Portfolio

**Virtual Robot Mania**: https://github.com/zevbo/VirtualRobotMania

During the covid-destroyed summer before freshman year of college, the lack of robotics and socialization was really hitting me. So, I decided to knock out two birds with one stone. I took a couple weeks, and cobbled together a small scale car-like robot simulator in Scheme that was so easy for even beginners to code. I organized a competitions centering around it for my extended family, and it was a lot of fun.

I then re-wrote it with a closer focus on making it sustainable for multiple competitions. I changed programming languages to OCaml, I created an original 2d physics engine from scratch, and designed a standard system to make new competitions. If you're interested specifically in my physics engine, it can be found in this directory: https://github.com/zevbo/VirtualRobotMania/tree/master/ocaml/virtuality2d/src. The section of the simulator I am most proud of is how I deal with collisions, the code for which can be found here: https://github.com/zevbo/VirtualRobotMania/blob/master/ocaml/virtuality2d/src/body.ml#L709.

**Bloomberg's Comdb2**

As a rising sophomore, I worked on bloomberg's 20 year old internal RDBMS, called comdb2. My branch, which is currently in the process of being merged into master, can be found here: https://github.com/zevbo/comdb2/tree/feature-final.

The main feature I added was a singular primative that would allow the user to audit a table, the documentation for which can be found here: https://github.com/zevbo/comdb2/blob/feature-final/docs/pages/programming/triggers.md#audit-triggers.

I also extended their transaction model to allow one command to execute multiple "schema changing" actions in the same transaction. The defintion here of schema change is not the standard one of changing the format of a table, but rather anything that changes the format of the entire database; that includes everything from deleting a table, to creating a trigger.

**Highschool Robotics**: https://github.com/SciBorgs/InfiniteRecharge-2020 and https://github.com/SciBorgs/DeepSpace-2019

Junior and Senior year of high school I put a lot of effort into my robotics team. On the DeepSpace-2019 repository, I wrote a lot of valuable automation which I was proud of, but I hadn't yet learned how to actually design code architechture, and as a result it's not designed praticularly inutively. However in 2020, where I wrote less of the automation, I put a lot of effort into creating a powerful and intuitive architechture for the rest of the team to use. 

If you're interested, go to https://github.com/SciBorgs/InfiniteRecharge-2020 and follow the READMEs. They're short and straight to the point :)

**Small Projects**: 

Sometimes all I want to do is write a short program to play a game or something, which I will generally write in Racket. A couple of fun examples are a connect 4 game with adjustable size (https://github.com/zevbo/Random-Racket-Stuff/blob/master/Adjustable%20Connect%204.rkt), a sudoko solver (https://github.com/zevbo/Random-Racket-Stuff/blob/master/sudokuSolver.rkt), and a program to show how images transform moving at relativistic speeds (https://github.com/zevbo/Java-Stuffs/blob/master/Modern%20Shapes/ModernShapes.java).
