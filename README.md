# Cloth crashing Unreal Engine 5

Proof of Chaos cloth crashing UE5 when it collides with some meshes.

I consider it's a bug related to collisions transferred from older Unreal 
Engine to UE5. I made some tests: mesh with "old" collision (looks like a 
simple box) crashes UE5, but if I redo collision (Auto Convex Collision) 
there are no more crashes.

Credits:
* "Long Hemmed Skirt" (https://skfb.ly/oLREs) by madsstensrud is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
 
Used UE 5.3.2.