# Reusing scene objects in SpriteKit

For table and collection views, there is a standard way of repopulating cells with new data that reduce recreation of new cell objects.
Imagining scenario in which user constantly switches SKScenes, there is no dequeueReusableScene(withIdentifier:). I guess this not necessarily means there is no underlying optimisation. Is there one, or it must be assumed that with every presentScene(_:transition:) previous scene is always destroyed?
If it is so, than is storing a buffer of some scenes a good practice?

