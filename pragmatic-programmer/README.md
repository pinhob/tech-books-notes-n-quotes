## Topic 12: Trace Bullets

- An approach to focus of the main features on the system. Developing them in a framework that can be user tested with expanded with more features while the project moves forward

- Trace bullets approach != prototyping

> We use the term tracer bullet development to visually illustrate the need for immediate feedback under actual conditions with a moving goal.

> We look for something that gets
us from a requirement to some aspect of the final system
quickly, visibly, and repeatably.
Look for the important requirements, the ones that define the
system. Look for the areas where you have doubts, and where
you see the biggest risks. Then prioritize your development so
that these are the first areas you code.

> Tracer code is not disposable: you write it for keeps. It contains
all the error checking, structuring, documentation, and selfchecking
that any piece of production code has. It simply is not
fully functional. However, once you have achieved an end-toend
connection among the components of your system, you can
check how close to the target you are, adjusting if necessary.
Once you’re on target, adding functionality is easy.
Tracer development is consistent with the idea that a project is
never finished: there will always be changes required and
functions to add. It is an incremental approach.

> In a tracer code development, developers tackle use cases
one by one. When one is done, they move to the next. It is
far easier to measure performance and to demonstrate
progress to your user.

> You use the technique in
situations where you’re not 100% certain of where you’re going.
You shouldn’t be surprised if your first couple of attempts miss:
the user says “that’s not what I meant,’’ or data you need isn’t
available when you need it, or performance problems seem
likely. So change what you’ve got to bring it nearer the target,
and be thankful that you’ve used a lean development
methodology; a small body of code has low inertia—it is easy
and quick to change. You’ll be able to gather feedback on your
application and generate a new, more accurate version quickly
and cheaply. And because every major application component is
represented in your tracer code, your users can be confident
that what they’re seeing is based on reality, not just a paper
specification.

> Prototyping generates disposable code. Tracer code is lean but
complete, and forms part of the skeleton of the final system.

## Topic 13: Prototypes and Post-it Notes

> prototyping is much cheaper than full-scale production.

> We build software prototypes (...) to analyze and expose risk, and to offer chances for correction at a greatly reduced cost.

> What sorts of things might you choose to investigate with a prototype? Anything that carries risk. Anything that hasn’t been tried before, or that is absolutely critical to the final system. Anything unproven, experimental, or doubtful. Anything you aren’t comfortable with. You can prototype: Architecture; New functionality in an existing system; Structure or contents of external data; Third-party tools or components; Performance issues; User interface design.

> Prototyping is a learning experience. Its value lies not in the code produced, but in the lessons learned. That’s really the point of prototyping.

> Before you embark on any code-based prototyping, make sure that everyone understands that you are writing disposable code. Prototypes can be deceptively attractive to people who don’t know that they are just prototypes. You must make it very clear that this code is disposable, incomplete, and unable to be completed.

> If you feel there is a strong possibility in your environment or culture that the purpose of prototype code may be misinterpreted, you may be better off with the tracer bullet approach. You’ll end up with a solid framework on which to base future development.

> Properly used prototypes can save you huge amounts of time, money, and pain by identifying and correcting potential problem spots early in the development cycle—the time when fixing mistakes is both cheap and easy.

### Topic 14: Domain Languages

> Your business users will have a vague idea of what they want to achieve, but they neither know nor care about the details. That’s part of our value: we intuit intent and convert it to code.

> Our suggestion is fairly simple: don’t spend more effort than you save. Writing a domain language adds some cost to your project, and you’ll need to be convinced that there are offsetting savings (potentially in the long term).

> We’d recommend using external languages only in cases where your language will be written by the users of your application.