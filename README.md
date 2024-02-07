Alexandre Nouar's projects - neuroscience and AI unique insights.

I am CTO and student in AI at MIT. I want to challenge my knowledge with unknown and really hard data, which makes it intellectually stimulating. Sun tzu says : "in the midst of chaos, there is opportunity" (the art of war)

Source images and data were collected on OpenNeuro, https://docs.openneuro.org/index.html# This project is made by an amateur (ok, neophyte) in the neuroscience field, however objectives are to dive with in the deep ocean and see how AI can help us find things out. Sometimes we seek feedback from newcomers, because they are unbiased. So am I. It is intended to make pattern matching of realtime brain iMRI and timelapse of events triggering reaction. We use 60 GDPR-friendly patients' data with data pre-processing and feature engineering so data can be used for deep learning.

I do not have the pretention I'll find anything, I just want to do something really hard, almost impossible. Audiard says "Idiots will dare anything, that's how you recognize them." That's me :) but an idiot trying is more likely to succeed than the wisest passive, so all in all, who is the real idiot ?

_________________________Engineer aspects ______________________________

To increase AI speed, it is decided use Spark for core deep learning operations, indeed it is better for scaled machine clusters than CUDA, and can use (lesser indeed, but 2 GPUs with Spark libraries will still better perform than one in CUDA) the same libraries. Cuda is better machine-wise (one big set of GPU's in a single machine system), Spark is better for several clusters. Both use parallel computing, even if CUDA enables a more granular way of memory management (and more granulars ways to fail).

First iteration will use a single node spark cluster, with a great desire to add a second computer on spark and use both. We use GPU acceleration libraries, and have a will to scale things up. 

