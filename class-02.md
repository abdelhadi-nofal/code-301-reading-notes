# jQuery 

jQuery offers a simple way to achieve a variety of common
JavaScript tasks quickly and consistently, across all major
browsers and without any fallback code needed.

## What is jQuery?

jQuery is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.

jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

The jQuery library contains the following features:

HTML/DOM manipulation
CSS manipulation
HTML event methods
Effects and animations
AJAX
Utilities
Tip: In addition, jQuery has plugins for almost any task out there.

Why jQuery?
There are lots of other JavaScript libraries out there, but jQuery is probably the most popular, and also the most extendable.

Many of the biggest companies on the Web use jQuery, such as:

Google
Microsoft
IBM

### LOADING JQUERY FROM A CDN

When a page loads jQuery from
a CDN, you will often see a
syntax like the one shown below.
It starts with a <script> tag that
tries to load the jQuery file from
the CDN. But note that the URL
for the script starts with two
forward slashes (not http:).
This is known as a protocol
relative URL. If the user is
looking at the current page
through https, then they will not
see an error that tells them there
are unsecure items on the page.
Note: This does not work locally
with the f i l e:// protocol.
This is often followed by a
second <script> tag that
contains a logical operator,
which checks to see if jQuery
has loaded. If it has not loaded,
the browser tries to load the
jQuery script from the same
server as the rest of the website.

WHERE TO PLACE YOUR SCRIPTS
The position of <scri pt> elements can affect
how quickly a web page seems to load.

SPEED
In the early days of the web, developers were told to
place the <script> tags in the <head> of the page
as you do with style sheets. However, this can make
pages seem slower to load.
Your web page may use files from severa l different
locations (e.g., images or CSS files might be loaded
from one CDN, jQuery could be loaded from the
jQuery or Google CDNs, and fonts might be loaded
from another third party).
Usually a browser will collect up to two fi les at a time
from each different server. However, when a browser
starts to download a JavaScript file, it stops all other
downloads and pauses laying out the page until the
script has finished loading and been processed.
Therefore, if you place the script at the end of the
page before the closing </body> tag, it will not affect
the rendering of the rest of the page.





***

## 6 Reasons for Pair Programming

Iterative loops. Code reviews. Fast feedback. Error checking and linting. These are software engineering practices that have proven to dramatically improve the quality of code developers produce. What if you can could get all of this, instantaneously, while typing code line by line and character by character? You can, with pair programming, a technique common to many agile work environments.

More “two heads are better than one” than “stop reading over my shoulder,” pair programming is the practice of two developers sharing a single workstation to interactively tackle a coding task together. At Code Fellows, pair programing is one way we foster a collaborative environment while developing key industry skills.

### How does pair programming work?

While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

### Why pair program?

While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking: using the correct words to communicate an idea Reading: understanding what written language intends to convey Writing: producing from scratch a meaningful

Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

During a five-hour paired lab session, Code Fellows students work on all four of these language-specific skills. The abilities they foster will serve them well in completing assignments, in their own communication and learning, in interviews, and in readiness for a job at a company that utilizes this agile practice.

Wow, all that? Let’s take a look!

1. Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making. Research indicates that pair programing takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging (let alone exposing users to a broken product). So, in the long-run, it’s often actually more efficient than two people working on separate features. When coming up with ideas and discussing solutions out loud, two programmers may come to a solution faster than one programmer on their own. Also, when the pair is stuck, both programmers can research the problem and reach a solution faster. Researches also identified pairing enhances technical skills, team communication, and even enjoyability of coding in the workplace.

2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. It is harder to procrastinate or get off track when someone else is relying on you to complete the work. Popping open your Facebook timeline is just that less enticing when someone else is looking at your screen.

Another important aspect of learning to program is knowing when to ask for help. We advise our students to spend no more than fifteen minutes stuck on a problem before asking a teaching assistant or instructor for help. When developers pair program, they rely more on each other and can often find a solution together without needing to ask for additional help. Ultimately, this boosts overall confidence.

3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of. If one developer has a unique approach to a specific problem, pair programming exposes the other developer to a new solution.

Often times, the developers in a pairing have different skill sets. If one programmer is more experienced in a certain skill, they can teach a student who is less familiar with that area. The less experienced developer benefits from the experienced developer’s knowledge and guidance, and the latter benefits from explaining the topic in their own words, further solidifying their own understanding.

4. Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities. Pair programming not only improves programming skills, but can also help programmers develop their interpersonal skills. When just grabbing the keyboard and taking over isn’t an option, getting good at finding the right words is a skill unto itself.

This has long-term career impacts. As much as employers want strong programmers, they know it’s essential to hire people who can work well with others.

5. Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base. By doing so, companies can get a better feel for how an applicant will fit into the team and their collaboration style.

For most roles, the ability to work with and learn from others and stellar communication skills are as (or more!) important to a company than specific technical skills. Pair programming strengthens all of those skills.

6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.
