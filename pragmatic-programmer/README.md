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