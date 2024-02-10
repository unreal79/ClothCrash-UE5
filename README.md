# Cloth crashing Unreal Engine 5

Proof of Chaos cloth crashing UE5 when it collides with some meshes.

I consider it's a bug related to collisions transferred from older Unreal 
Engine to UE5. I've made some tests: mesh with "old" collision (looks like a 
simple box) crashes UE5, but if I redo collision (Auto Convex Collision) 
there are no more crashes.

Used UE 5.3.2.

## Links
Discussion here: https://forums.unrealengine.com/t/assertion-failed-pointfaces-pointindex-num-3-file-build-ue5-sync-engine-source-runtime-engine-private-skeletalmeshcomponentphysics-cpp-line-3181/1220899

Credits:
* "Long Hemmed Skirt" (https://skfb.ly/oLREs) by madsstensrud is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
