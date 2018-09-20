C++ Build Systems
=================

My Metric:
----------

* Building sub-targets
* Building different editions of the software (dev, release, sanity, ...)
* Building different target architectures
* Learnability (Also Relearnability)
* Decorativeness
* Completeness (Turing Complete. Should be possible, but hard. Whenever you have to do Turing-Complete stuff, it should feel like a hack, so that you don't build magic into your build-system)
* Convenience (Which leads to better quality of the build-descriptions)
* Correctness (No Clean Build Culture)
* Performance (Turnaround Times)
* Scalability (Check out projects which are using the system already at scale to check this attribute)
* Multi-Language-Support 

After the talk, I got some feedback. Open-Source was one suggestion as part of the metric. While I didn't mention it explicitly, Open-Source was part of my decision as well. Do not marry proprietary build systems!

Scenarios for evaluation
------------------------

* Source Code in a Single Directory
* Source Code in Multiple Directories
* Changing the compiler / different build-tools
* Building multiple variants
* Clean build
* Debugging incorrect builds

The Categories
--------------

* Low Level (e.g. Make)
* Meta (e.g. CMake)
* Imperative (e.g. SCons)
* Declerative (e.g. Bazel/Buck)
* Custom (Don't do it!)

How are the metrics and the category related? You apply the metric to one representative within the category. The resulting category for which the representative stands for is your goto-category. Within the category, you can then try out the alternatives as well.

Resources
---------

The Goto-Resource, if you have to make a decision or make improvements:

* "Software Build Systems" by Peter Smith

My Slides are in this repo as well.


