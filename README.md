# Reusing scene objects in SpriteKit

For table and collection views, there is a standard way of repopulating cells with new data that reduces recreation of new cell objects.
Imagining scenario in which user constantly switches SKScenes, there is no dequeueReusableScene(withIdentifier:). I guess this not necessarily means there is no underlying optimisation. Is there one? Should it be assumed that with every presentScene(_:transition:) previous scene is always destroyed, unless there are other references to it? If it is so, than is storing a buffer of some scenes a good practice?

# Is this logical to expect any declarative framework to be an alternative for SpriteKit in the future?
I guess declarative paradigm make sense if there are predefined ways of fulfiling most expectations. Is SpriteKit adaptable to the new paradigm? Would trying to extend SwiftUI to match a standard SpriteKit's use cases be a foolish endevour?

# In SwiftUI every animation would always take the shortest path. It is easy to imagine animating position along the path. Is lack of this option the design choice or just the current state of the framework? 

TO DO: add code example
