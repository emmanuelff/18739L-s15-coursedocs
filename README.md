# 18739L: Special Topics in Security I

This is a seminar course in computer security. The course will cover
the latest advancements, techniques, theories, systems, and ideas in
computer security. Open to PhD students, or with instructor
permission. The content varies each semester. 


## Course Overview

This course has one goal: to significant improve students ability to
compete in Capture the Flag (CTF) computer security competitions.
Computer security is both a research topic and a skill.  We have
structured this course to provide a forum for deliberate practice of
computer security concepts and skills.  Like any type of practice,
what you get out is heavily influenced by how much you put in.

Why do we focus on CTFs? Because they are a microcosm that demonstrate
larger computer security concepts, problems, and skills.  CTF problems
tend to be "smaller" than real life problems, but by being small they
allow us to focus on specific ideas.

**Warning:** If you have not done previously done either (a) CTF
  competitions, or (b) received an A in 15-213/18-213, you will have a
  bad time. 

  * Instructor: David Brumley
  * Teaching Assistant: Rijnard van Tonder
  * Course time: Mondays and Wednesdays 02:30pm - 03:20pm
  * Course location: SH 208, Pittsburgh, PA
  * Course units: 12
  * Pre-requistes: 18730 or 18487 or instructor permission. Permission
    is generally granted to students who either get an A in
    18-213/15-213 or are able to rapidly get to the final level of
    picoctf.com.

## Topics Covered

Computer security in practice, and thus in CTFs, is usually broken
down into the following areas:

  * Binary code analysis, vulnerability discovery, and exploitation
  * Reverse engineering
  * Cryptography
  * Web security, including scripting languages, database backends,
  session management, etc.
  * Forensics
  * Miscellaneous security topics as they appear in CTF challenges


## Course Structure

The goal is for you to learn and improve. We assume that since you
have taken 15-213 or an introduction to security course that you
already have a rough idea of the basics like memory safety attacks,
basic crypto principles, and so on.

I believe that to get to the next level, you need to start
practicing. You need to get stuck. You need to read wikipedia,
textbooks, and new articles to find gaps in your knowledge. You need
to figure out what you don't know yet, and what you probably should
learn. You need others to give you hints on what they did.

None of these things are best facilitated by a lecture by
me. Therefore, we have a somewhat different structure to this class:

  * Practice. Students will be required to participate in wargames and
    competitions.  We will start with picoCTF, which has a fairly well
    considered skill level progression. As the course progresses, we
    will target harder wargames and CTFs.     
  * Teach.  The best way to show what you really know is to try and
    teach it to someone else. However, my experience is course
    presentations of assigned topics tend to not work well.  In this
    class we will try a more experimental approach where students
    describe what they are "stuck" on, and other students try and help
    them through. 
  * Develop new challenges. Students will develop CTF problems.  This
    may seem simple, e.g., buffer overflows are created by mistake
    each day, how hard could it be to create an intentional one?
    However, it's more tricky.  Designing a problem
    [requires careful consideration](http://captf.com/maxims.html) so
    that players have the "aha" moment when solving it. (Note even
    PPP, a very experienced team that creates over 100 challenges a
    year, throw out tons more because they aren't good enough.)


## Practice

We will practice by solving "wargame" challenges (security challenges
that are not part of a competition) as well as participate in real
CTFs. By the end of this semester you will have completed picoCTF,
microcorruption, IO, webhacking.kr, and one wargame of your
choice. You will also have completed two CTFs.

### Wargames

  * [picoCTF](http://picoctf.com). Grading: 3500 and up: A, 3000 - 3500: B,
    2500-3000: C, 2000-2500: D, Fail below, and I will ask you to drop
    the class. 
  * [Microcorruption](https://microcorruption.com/login).  16 and up:
    A, 14-16: B, 12-14: C, 11: D, below that: F.
  * [IO](http://io.smashthestack.org/): TBD.
  * [Web hacking](http://webhacking.kr/): TBD.

All wargames must be done individually. Wargames often require an
account. In such cases the student should register an account, and
update the github document that maps their username to their andrew
ID.  You should solve each challenge on your own. It's ok to ask
others for tips, but you need to be able to work through the problem
on your own, and explain what you did.  I suggest you use time right
before and after class to ask questions of some of the more
experienced players. 

We check progress in class. We will maintain a document mapping your
CTF ID to your andrew ID.  Since we will be working on CTFs in class,
we will walk around and check to see what level you are on.

### CTF contests
     
 * [Boston Key Party](http://bostonkeyparty.net/): Feb 27 - March
      1, 2015. Note this is not a regular class time! Participation
      means working at least 10 hours total.  Required.
 * Ghost in the shell: Jan 16-18, 2015. Optional. Extra Credit.
 * Codegate (when announced). Required. 

Students should register using a name that is prefixed with CMU
(assuming you are not competing as PPP). We will use github to map
which students (by andrew ID) are on each team.  Students must submit
a screen shot at the end of the contest with their score.

## Teaching

In each class I will iterate until class is over the following
procedure:

   * Pick a student, have them come up to the display and talk about a
   problem they are working on.
   * Have other students who have solved the challenge give
   hints. They may be asked to log on themselves and walk through.
   * Work as a class to summarize overall techniques.

As I mentioned above, this is an experiment. We will adapt if it does
not appear to be working. I hope it does. I hope everyone comes into
class with questions that we can try to work through together.

## New Challenges

Even student will develop 3 new substantive CTF challenges.  The
minimum requirements are:

  * The problem should have a clear concept being taught.
  * There should be a detailed walkthrough of problem and solution.
  * There should be an annotated bibliography of other sites and
  resources for learning about the material.
  * Keys should be auto-generated.
  * It should tie into the picoctf platform.
  * Code should be signed off by at least 2 others in class.  We
    follow standard
    [peer review guidelines](https://github.com/thoughtbot/guides/tree/master/code-review)
  * Code will be hosted on github.  (We will allow for private repos,
  and have applied for the educational discount.)

As mentioned above, creating good challenges is hard, but
learnable.  You should make sure you devote sufficient time to create
a problem (probably somewhere in the area of 2-8 hrs).

Our process will be:

  * Students will propose a project. This will include:
    * The problem area (crypto, binary exploit, etc.)
    * the skill level
    * what you expect a person to know to solve it
    * problem setup
    * a walkthrough.
  * We will discuss all problems in class. I expect a number of
    problems will be deemed bad, and will have to be reproposed.
  * Problem implementation. We will implement in the picoctf framework.
  * Test play in class. We will get feedback. The best 5 problems will 


## Research

Students will propose a research project towards the end of the
semester. The research will be how to automate CTF problem solving. By
default, you will focus on binary analysis.  I will accept other
compelling ideas on an individual basis. 

There will be a project proposal, a mid-term meeting, and final
presentations. In the final presentation I expect you to show several
problems solved in class that your project helps solve.

As an example of a steller, independently-motivated project, look no
further than [Qira](https://github.com/BinaryAnalysisPlatform/qira). 

## Grading

Great hackers, as well as great researchers, are curious. They learn
things on their own.  They try to understand things that catch their
eye deeply. I would expect a hacker mentality. This is also an
elective, high-level class.  You don't have to take it, and you
shouldn't unless you are deeply interested in the subject.  Therefore,
I ask that you not play the game of the least amount of work to
technically satisfy a requirement.  Do a good job.

We will guarantee an A for 90-100%, B 80-90%, C for 70-80%, D for
60-70%, and R for all other grades.  Fractional percentages will be
[rounded half up](http://en.wikipedia.org/wiki/Rounding#Round_half_up).

Percentages will be weighted as follows:

 * Course participation.  You get 2 free classes you can miss. After
   that, you will loose 5% your total grade per class missed.  No
   exceptions without a doctors written note for a medically serious life
   event.
 * Wargames.  Grades for each point bracket will be posted in this document.
 * CTFs: You must spend 10 hours per CTF on each of the two CTFs. This
   will be somewhat of an honor system.
 * CTF problems created. Grading TBD. 
 * Course project. Your course project must demonstrably make CTF
   problem solving easier.  Note we do not start course projects until
   near the end of the semester in order to make sure you have
   sufficient experience.  The requirements are:
   * Initial proposal. The proposal should include example problems
     you have solved this code will help with.
   * Meeting with David for feedback.
   * Demo of final tool. The demo will show how 3 problems are solved
     more easily with your tool.
   * Final writeup and code release.


Grades will be weighted 30% practice, 30% CTF problems, 20% research
project, 20% class attendance. Note the heavy weight on
attendance. This is because for the course to work, students have to
be in class to talk about where they are stuck, as well as give hints
and advice to others.  If you're not in class, you aren't doing these
things.


## Git account structure

Every student should maintain notes and code at github.com. It's
important to be able to reflect back on how you solved previous
problems, and be able to reproduce them. We may even ask you to
reproduce them. 

We heavily encourage markdown for notes. 

Please structure your git account as follows:

   * ctf/_ctfname_/_problem_/.  For each ctf named _ctfname_ and each
   problem.
   * wargames/_wargamename_/_problem_/. Similar to above.
   * myctf/{prob1, prob2, prob3}/
      * src: problem source.
      * doc: problem walkthrough
      * tests: unit tests. Have them. 



## Calendar

The first month or so of the course focuses in playing CTFs.  You
can't create good problems or write interesting tools without some
experience.  The next month continues with playing problems, and asks
you to start designing problems.  The final month focuses on
developing automated tools for CTF. 

Anytime there is a deadline, it is due at 2:30pm eastern time. We will
check git's timestap.  Please do not ask for late days unless there
was a true medical emergency. I die a little when I get asked for late
days.

  * 1/12. First day of class.  Everyone signs up for picoctf. Does
    problems for level 1-4.
  * 1/14. jburket presents picoCTF level 4: two problems. 
  * 1/19. No class. Martin Luther King Day
  * 1/21. Wargame walkthroughs. 
  * 1/26. David gone. Wargame walkthroughs hosted by TBD.
  * 1/28. David gone. Wargame walktrhoughs hosted by TBD.
  * 2/2. Wargame walkthroughs. PicoCTF score due in class.
    Start microcorruption.
  * 2/4. Wargame walkthroughs
  * 2/9.  David gone. Wargame walkthroughs hosted by TBD.
  * 2/11. Wargame walkthroughs.

**You will have had about a month of practice at this point.**

  * _2/15_ noon: CTF problem 1 proposal due. Note this is not a class day.
  * 2/16. CTF problem 1 proposal discussion in class. 
  * 2/18. Microcorruption due.  Start on IO.
  * 2/23. Wargame walkthroughs.  CTF problem 1 code due.
  * 2/25. CTF problem 1 play-through in class. If you don't have code
    that builds and integrate, you will get a zero! You have been warned.
  * 2/27 - 3/1: Boston Key Party Party. We will reserve a room, and
    get food. 10 hours total of time. There will be a log. Scouts honor.
  * 3/2. Boston Key Party Review. 
  * 3/4. IO due. Note research problem proposals and CTF problem
    proposal 2 and research project proposal due. 

**At this point, you will have completed a large portion of picoctf,
    microcorruption, and IO. You will have also done one real ctf. You
    will have created 2 problems. I would guess you have moved at
    least beyond beginner to the intermediate phase.**

  * 3/9. No class. Spring Break.
  * 3/11. No class. Spring Break.
  * 3/16. Start on webhacking.kr. 
  * 3/18. No class. Work on research and CTF problem.
  * _3/21._  CTF Problem 2 due. Note: not a class day.
  * 3/23. In-class meetings with David on proposals. Rest of class
    plays through CTF problems with feedback. CTF Problem 3 proposal due.
  * 3/25. Wargame walkthrough and feedback on proposals.
  * 3/30. Wargame walkthroughs.
  * 4/1.  webhacking.kr due. CTF Problem 3 due. 
  * 4/6.  CTF Problem 3 play through. Start on user choice wargame.
  * 4/8.  Status report on projects with David during class time.
  * 4/13. Wargame walkthrough. 
  * 4/15. Note Carnival runs 4/17 - 4/20, with PlaidCTF.
  * 4/20. Wargame walkthrough. 
  * 4/22. Final project presentations
  * 4/27. Final project presentations
  * 4/29. Final project presentations. Final wargame due.


## Reading

  * [PicoCTF: A Game-Based Comptuer Security Competition for High School Students](https://www.usenix.org/conference/3gse14/summit-program/presentation/chapman)
  * [CTF Field Guide](https://trailofbits.github.io/ctf/ctf.html)
  * [LiveCTF](http://www.twitch.tv/livectf)
  * [Practice CTF List and Archive](http://captf.com/practice-ctf/)
