# Zork Syntax Walkthrough

Once in the LFE REPL, start Zork-style shell:

```lisp
> (spels:start)
```

You will be greeted with the following:

```text

         ..~;;;##################################;;;~..
 .....~.~~~~;;;###    Casting SPELs in LFE    ###;;;~~~~.~.....
       ..~.~;;;##################################;;;~.~..

Welcome!

Type 'help' (without the quotes) for a list of available commands.
To jump right in and play, you can start with the 'look' command :-)

spels>
```

Here's a walk-through:

```text
spels> look

You are in the living-room of a wizard's house. There is a wizard snoring
loudly on the couch.
You see a whiskey-bottle on the ground. You see a bucket on the ground.
There is a door going west from here. There is a stairway going upstairs from
here.

spels> take bucket

You are now carrying the bucket.

spels> go west

You are in a beautiful garden. There is a well in front of you.
You see a frog on the ground. You see a chain on the ground.
There is a door going east from here.

spels> take chain

You are now carrying the chain.

> go east

You are in the living-room of a wizard's house. There is a wizard snoring
loudly on the couch.
There is a door going west from here. There is a stairway going upstairs from
here.

spels> go upstairs

You are in the attic of the wizard's house. There is a giant welding torch in
the corner.
There is a stairway going downstairs from here.

spels> weld chain bucket

You have achieved the 'weld-chain' goal!

The chain is now securely welded to the bucket.

spels> look

You are in the attic of the wizard's house. There is a giant welding torch in
the corner.
There is a stairway going downstairs from here.

spels> go downstairs

You are in the living-room of a wizard's house. There is a wizard snoring
loudly on the couch.
There is a door going west from here. There is a stairway going upstairs from
here.

> go west

You are in a beautiful garden. There is a well in front of you.
You see a frog on the ground.
There is a door going east from here.

spels> dunk bucket well

You have achieved the 'dunk-bucket' goal!

The bucket is now full of water.

spels> go east

You are in the living-room of a wizard's house. There is a wizard snoring
loudly on the couch.
There is a door going west from here. There is a stairway going upstairs from
here.

spels> splash wizard bucket

You have achieved the 'splash-wizard' goal!

The wizard awakens from his slumber, greets you warmly, and thanks you for
pulling him out of a rather nasty dream.
Your reward, it seems, is a magical low-carb donut which he hands you ...
right before drifting off to sleep again.

You won!!
```
