# The Concept
Essentially, I'm aiming for a mini companion to have in my vehicle. Just to keep me company for the long lonely drives or whatever. This document will serve as my guidelines to building out this project. I may probably make it into a full stack application at some point, but no promises.

## Layout
Ideally, I want the features for the Service to be separated into modules. These modules will contain all of the information needed in order to have a certain feature working. As such, there will also be a main file, which will load all of the modules appropriately.

## Functionality
The Service will be interacted with by use of Voice Commands, which can be processed in said main thread. From there, keywords will bee chosen from a provided list (ideally from the loaded modules), where if the keyword matches up, the function would be executed.

That's essentially how I want the core of this to be done.

## Modules
Ideally, modules should be split into Online and Offline, the offline ones always being available, and the online ones providing additional features through the use of external APIs.

## Frontend
Eventually, I would like the PI to spin up a localhost frontend, so users can also interact with it to some extent via a UI instead of having to be solely voice activated. However, I will most likely keep this frontend to something extremely simple, because anything else might be too much stress. But we'll see.