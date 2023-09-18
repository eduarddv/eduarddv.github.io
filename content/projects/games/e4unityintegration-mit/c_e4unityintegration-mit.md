### E4UnityIntegration-MIT

_E4UnityIntegration-MIT_ is an Android Unity plugin to integrate the Empatica E4 wristband used to obtain physiological measurements into the game engine. It is written in C# and Java.

The plugin spawned an associated short paper which I'm in the process of trying to get published. Once it is and there's no anonymity requirement anymore both the paper and the plugin will be linked here; in the meanwhile, please feel free to browse the full thesis linked further below.

The plugin was piloted and validated during a small scale human-subjects study exploring the relationships between physiological measurements and sense of presence in a VR game using _E4UnityIntegration-MIT_.

This project, consisting of _E4UnityIntegration-MIT_ and the human-subjects study, was developed over the course of 6 months during a research stay at MIT and was presented as my bachelor's thesis, earning me full marks (10/10). [View the full thesis.](/assets/documents/Bachelor_Thesis.pdf)

The work here highlights my ability to develop complex innovative technology under time constraints in an unfamiliar tech stack, as I had never previously developed for Android or for the Meta Quest 2 VR headset. It also showcases my ability to leverage my understanding of the fundamentals of the technology to dive deep into a problem. I had a particularly difficult debugging task during development which simultaneously involved an instant crash due to a bug in the E4 library (which ships pre-compiled) and a (hidden) multithreading issue that only occurred when deploying to devices (not in the Unity editor). Solving this issue required debugging dexterity, reverse engineering the library, intuition, and, most of all, patience and persistence.