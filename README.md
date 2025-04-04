# CBT1055
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1055 is from Joseph Reichman and contains an extension     *   FILE1055
//*           and modernization of File 192 from (the late)         *   FILE1055
//*           Mitchell Marx.  This is a generalized recovery        *   FILE1055
//*           routine, which had to be modernized to accommodate    *   FILE1055
//*           64-bit registers (which were not around in the early  *   FILE1055
//*           1990's), and it needed to be enhanced, to show where  *   FILE1055
//*           a program bombed, if it didn't bomb in the original   *   FILE1055
//*           caller's address space.                               *   FILE1055
//*                                                                 *   FILE1055
//*           The main program here is called GRECOV, which is      *   FILE1055
//*           invoked as an ESTAEX.  GRECOV writes its output to    *   FILE1055
//*           a previously defined GDG member,                      *   FILE1055
//*                                                                 *   FILE1055
//*           GRECOV now runs principally as an ESTAE.              *   FILE1055
//*                                                                 *   FILE1055
//*           Test cases to run GRECOV (the main routine) are       *   FILE1055
//*           supplied in members CESTAE and CLIENT.                *   FILE1055
//*                                                                 *   FILE1055
//*           Because this code is a modification of the code in    *   FILE1055
//*           File 192, much of that material has been kept here    *   FILE1055
//*           as well for completeness.  Unfortunately, both        *   FILE1055
//*           Mitchell Marx and Penelope Davis have passed on, and  *   FILE1055
//*           it is hoped that this work of theirs, so thorougly    *   FILE1055
//*           modernized and improved, will live on and continue    *   FILE1055
//*           to benefit many people.  Using the new methods which  *   FILE1055
//*           were originated by the current author, it will now    *   FILE1055
//*           be possible, when a program will abend in a system    *   FILE1055
//*           module (and not in its own code), to trace the        *   FILE1055
//*           origins and registers of the true abending program,   *   FILE1055
//*           at least most of the time.  Please reply for          *   FILE1055
//*           support, to:                                          *   FILE1055
//*                                                                 *   FILE1055
//*           email:  Joseph Reichman <reichmanjoe@gmail.com>       *   FILE1055
//*                                                                 *   FILE1055
//*           Joe could not dream up all cases that his new         *   FILE1055
//*           methods (of tracking sets of registers) will work     *   FILE1055
//*           on, so he is depending on feedback from you, the      *   FILE1055
//*           users of this code, to help work out all of the       *   FILE1055
//*           abending situations.  Please write to Joe with any    *   FILE1055
//*           problems or questions.                                *   FILE1055
//*                                                                 *   FILE1055
```
