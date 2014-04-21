TDD-Notes
=========

Notes on this lecture: https://www.youtube.com/watch?v=HhwElTL-mdI
=========

TDD:

Intelligence is a liability.

—> Smart people can make progress without process. (This is not a good thing).

Professionals:

- Design, plan, and prepare first
- then do the work

-> this produces better results <i>faster</i>

Process is the difference between surgery and cutting people open.

It’s the difference between <b>software engineering</b> and <b>programming.</b>

———

“If I take the time to write tests, I won’t finishing this feature in time.”

—> Don’t be this guy.

———

Software Process:

- Architecture
- Conventions & Standards
- Version Control
- Coordination (agile, etc.)
- <b> Test-driven development </b>

Tests Provide:

- Documentation of code
- Catch future errors (when it breaks, we know)
- Long-term time savings

———

TDD is more than just writing tests:

- Decide what the code will do.
- Write a test that will pass if the code does that thing
- Run the test, see it fail (<i>this step is more important than you think</i>)
- Write the code
- Run the test, see it pass

—> Do this for every couple of lines of code

———

TDD Provides:

- Design and plan before you code
- Document your design
- Proof that code implements design
- <b>Encourages design of testable code</b>

———

Testable code, remarkably, looks a lot like good code!

If you write the tests first, you can’t write code that is too complex to understand and maintain

Testable code:

- Modular
- Decoupled design
- Methods of limited scope
- Shrinking in cyclomatic complexity (the amount of paths through the code).
- etc.

RESULT: Better code <i>in less time.</i>

— CAVEAT: You will have to do this for a while before you will be faster.

— CAVEAT2: Intelligence is an ASSET. Be smart about how you test.

———

USE JUDGMENT:

- Some things are too hard to test
- Some tests are too trivial to be useful
- Overtesting is also possible (try to test each thing once).
- Exploratory coding w/o tests is OK! (you don’t know what you want to do or how you want to do it yet, but as soon as you hit production code, RED-GREEN-REFACTOR).

———

— A lot of places bring in junior developers who are really bright, but do not have good process. Nail down process, keep away consultants.