### E4UnityIntegration-MIT

_E4UnityIntegration-MIT_ is an Android Unity plugin to integrate the Empatica E4 wristband used to obtain physiological measurements into the game engine. It is written in C# and Java.

The plugin, which was released as open source, spawned an associated short paper which I'm in the process of trying to get published. [View the (anonymised) paper.](/assets/documents/IEEE_CoG2023_Empatica_E4_auxiliary_short_paper.pdf). [Browse the source code.](https://osf.io/v9whk/?view\_only=dc43354770044134a45c0a74c312514f)

The plugin was piloted and validated during a small scale human-subjects study exploring the relationships between physiological measurements and sense of presence in a VR game using _E4UnityIntegration-MIT_.

This full project, consisting of _E4UnityIntegration-MIT_ and the human-subjects study, was developed over the course of 6 months during a research stay at MIT and was presented as my bachelor's thesis, earning me full marks (10/10). [View the full thesis.](/assets/documents/Bachelor_Thesis.pdf)

The work here highlights my ability to develop complex innovative technology under time constraints in an unfamiliar tech stack, as I had never previously developed for Android or for the Meta Quest 2 VR headset, as well as to quickly get up to speed with unfamiliar research. Moreover, it shows I can perform in the face of tasks I have not been prepared for; my mathematics and CS education certainly did not cover how to carry out human-subjects experiments!

It also showcases my ability to leverage my understanding of the fundamentals of the technology to dive deep into a problem. I had a particularly difficult debugging task during development which simultaneously involved an instant crash due to a bug in the E4 library (which ships pre-compiled) and a (hidden) multithreading issue that only occurred when deploying to devices (not in the Unity editor). Solving this issue required debugging dexterity, reverse engineering the library, intuition, and, most of all, patience and persistence.