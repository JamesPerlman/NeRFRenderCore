## LATEST UPDATE

A substantial refactor is underway (~90% complete) to make the upcoming Python API easier to manage.  
The Python API will allow a developer to consume certain CUDA functionalities.  
The Blender integration will come after the Python API is complete.  
Estimated ETA on the Blender plugin is ~March 1, 2022  
After the Blender integration is complete, I will release a binary along with the [addon codebase](https://github.com/JamesPerlman/blender_nerf_tools)

## INTRODUCTION

Hello NeRF enthusiasts!  Here you will find my NeRF rendering and training library.  The core principles of this NeRF method are based on the incredible work of [Thomas Müller](https://tom94.net/), [Alex Evans](https://research.nvidia.com/person/alex-evans), [Christoph Schied](https://research.nvidia.com/person/christoph-schied), and [Alex Keller](https://research.nvidia.com/person/alex-keller), in their paper [Instant neural graphics primitives with a multiresolution hash encoding](https://arxiv.org/abs/2003.08934).  

Yes, I realize there is already a [CUDA implementation](https://github.com/nvlabs/instant-ngp), but I wanted to take a crack at reimplimenting this myself for the challenge, and for artistic uses such as:  

* Spatial distortions  
* Multiple NeRFs in one scene  
* Multi-GPU capabilities  
* Shadertoy-style effects  
* Fractals  

Since everything here has been written from scratch, this codebase is permissively licensed and commercial-use-friendly.  

DISCLAIMER: Although I am extremely passionate about NeRFs and their artistic applications, I do not have a deep background in ML research or CUDA development, and the code I've written here will certainly reflect that.  But perhaps that's where you come in!  Feel free to browse and suggest changes, this is all a learning process!  

Enjoy!  
-James  
https://twitter.com/jperldev

## TEST DATA

Until we have an extensible data loader, the test data I'm working with is here:  

https://www.dropbox.com/sh/qkt4t1tk1o7pdc6/AAD218LLtAavRZykYl33mO8ia?dl=1

## THANK YOU

Many thank-yous to open source projects that will allow this project to reach its full potential (in order of integration date):

https://github.com/pkestene/cuda-proj-tmpl [[LICENSE](https://github.com/pkestene/cuda-proj-tmpl/blob/master/LICENSE)]  
https://github.com/NVlabs/tiny-cuda-nn [[LICENSE](https://github.com/NVlabs/tiny-cuda-nn/blob/master/LICENSE.txt)]  
https://github.com/nlohmann/json [[LICENSE](https://github.com/nlohmann/json/blob/develop/LICENSE.MIT)]  
https://gitlab.com/libeigen/eigen [[LICENSE](https://gitlab.com/libeigen/eigen/-/blob/master/COPYING.APACHE)]  
https://github.com/nothings/stb [[LICENSE](https://github.com/nothings/stb/blob/master/LICENSE)]  
https://github.com/bmild/nerf [[LICENSE](https://github.com/bmild/nerf/blob/master/LICENSE)]  
https://github.com/nerfstudio-project/nerfstudio [[LICENSE](https://github.com/nerfstudio-project/nerfstudio/blob/main/LICENSE)]  
https://github.com/KAIR-BAIR/nerfacc [[LICENSE](https://github.com/KAIR-BAIR/nerfacc/blob/master/LICENSE)]  
https://github.com/ashawkey/torch-ngp [[LICENSE](https://github.com/ashawkey/torch-ngp/blob/main/LICENSE)]  
https://github.com/google/nerfies [[LICENSE](https://github.com/google/nerfies/blob/main/LICENSE)]  
https://github.com/glfw/glfw [[LICENSE](https://github.com/glfw/glfw/blob/master/LICENSE.md)]  
https://github.com/pybind/pybind11 [[LICENSE](https://github.com/pybind/pybind11/blob/master/LICENSE)]  

LICENSES TO BE ADDED TO CODEBASE SOON.  CHECK LICENSES/ DIRECTORY

## CITATIONS

Next-level respect to the researchers much of this codebase is based off.  Thank you for making your research public.  This would not have been possible without you.  

Mildenhall, Ben, et al. "NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis." arXiv, 2020.  doi:10.48550/arxiv.2003.08934 - (https://arxiv.org/abs/2003.08934)  
Müller, Thomas, et al. "Instant neural graphics primitives with a multiresolution hash encoding." *ACM Trans. Graph.*, 41(4), 102:1-102:15 - https://doi.org/10.1145/3528223.3530127  
Max, Nelson. "Optical Models for Direct Volume Rendering." IEEE Transactions on Visualization and Computer Graphics (1995) - https://courses.cs.duke.edu/spring03/cps296.8/papers/max95opticalModelsForDirectVolumeRendering.pdf  
Müller, T. (2021). tiny-cuda-nn (Version 1.7) [Computer software]. https://github.com/NVlabs/tiny-cuda-nn  
Fawzi, A., Balog, M., Huang, A. et al. Discovering faster matrix multiplication algorithms with reinforcement learning. Nature 610, 47–53 (2022). https://doi.org/10.1038/s41586-022-05172-4  
Alman, Josh, and Virginia Vassilevska Williams. "A Refined Laser Method and Faster Matrix Multiplication." arXiv, 2020, doi:10.48550/arxiv.2010.05846.  https://arxiv.org/abs/2010.05846  


## SUPPORTERS

Extreme thank yous to these subscribers on Twitch (https://twitch.tv/jperldev) who support this project's development!

madclawgonzo - Requested a haiku written by ChatGPT: "Madclawgonzo / Subscribing to your stream / Software project."  
anonymous - Requested to remain anonymous  
gusround - https://github.com/candidogustavo  
slowcon - "uncle slowcon is here with the 4090"  
likid_3 - <3  
cognitrol - Supporting cool work that helps the community explore technology  
dankmatrix - (pending message)  
seferidis - (pending message)  
memepp - (pending message)  
Dakren12 - (pending message)  
Relakin - (Confused)  
flouwr - (pending message)  
