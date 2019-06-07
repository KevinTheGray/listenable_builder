# listenable_builder

ListenableBuilder is an extension of AnimatedBuilder that doesn't do anything except **possibly** make your code more readable.  

## Why?

Because Flutter is heavy on animations, and using an AnimatedBuilder for infrequent and simple state changes can just read weird.

ListenableBuilder sounds more like what you'd expect.  This widget rebuilds when the listenable I give it updates.
