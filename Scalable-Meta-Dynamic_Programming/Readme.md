

##metaprogramming. 
##A subset of Aspect Oriented Programming

compiled languages allow for reflection but cause additional efforts in order to allow them to perform these applications at runtime. This makes sense for memory and efficiency concerns. However, without runtime applications metaprogramming actions like reflection cannot occour. Leaving a programmer ill equipped; not having a tool needed to build in the dynamic fashion they would appreciate.
nothing scales.
in order to make it scale. you have to make them work at runtime. 
... this readme is to start a thread on metaprogramming; to show code programmed and prepared presenting meta programming; where it excels and common languages for metaprogramming. I will get into different languages and oppertunities for them to contribute to scalable applications in my mind. This is a dialogue... if you come up with a good use case or response... please display it as a pull request. For too long I have searched github for metaprogramming ... scalable ... dynamic programming ... Dynamic Programming even has a different definition in programming related to mathematics or things like tail end recursion, where a solution must be waited for before continuing. However, these monikers should be inerlinked. It is frustrating that there is no landing page where this is consolidated.

reflection in c# https://www.tutorialspoint.com/csharp/csharp_reflection.htm
https://discussions.apple.com/thread/6890959?start=0&tstart=0


first let me give a definition of scalable code: 
scalable code ... will add another variable when needed. You could build a variable from a text document or users could build variables or additional features(at runtime) while a program is running. 

What needs to be remembered is that reflection is comparable to non tail end recursion. 
becuase it is not finding the solution and then carrying it forward.

reflection will eat up a lot of memory because it has to remember all of these variables names. 
However, reflection is often done by storing those names in ... a seperate file.
The pro to storing in a seperate file is that the program will not crash from holding too much active memory.
The con to storing in a seperate file is a significant slowdown in the program because it will need to page in and page out the information.

It is fine to store the reflection variables in active method as you have a limit to the scale and your hardwares computer memory can handle storing the variable information.

common examples of what I would call metaprogramming.
http://www.w3schools.com/php/php_ajax_php.asp
php... can be used to make scalable websites. Where loops can be used to display one record of information if there is one record in the database. Or 20 records of information if 20 records are in the database.
PHP actually writes the HTML code and can repeat its methods of building. Making it dynamic, or interactive.
rendering (will submit a query any number of times.)
Since php is rendered by the server the information is acquired by the server and then built before presented to the user. This means that a website with a large amount of manipulation or large latency delay to ping the server will take a considerably larger amount of time before being able to be rendered to the user.

(Asynchronous JavaScript)AJAX, is a programming principle, whereby java script, which is rendered to the user at runtime, can render information to the user quickly by only refreshing parts of the page that is new information. 
Apple script can perform reflection. A with relative speed. A program showing an example of reflection for a mac in apple script will be included in the file directory, showing hopefully, that the speed delay is not noticable.
My understanding is that scripting languages happen at runtime and therefore do not have significant delay implementing reflection.
Assertion to be checked: reflection in a scripting language or language operating at runtime that stays within volatile memory, not paged into a file or paged out of a file, has very small slowdown to the overall speed of the program.

However, Reflection in a compiled language has a large slowdown in overall program speed because information must figured out at runtime instead of its normal running at from byte code developed at compile time.

please only positive stuff. I am updating this with new information as it becomes availiable to myself. 
This readme and repository serves more as an investigation than a definitive text.

Regards, M D
