Alexandre Nouar's Projects: Neuroscience and AI Insights

Welcome to a journey where neuroscience data meets artificial intelligence. I'm Alexandre Nouar, CTO and an AI student at MIT, embarking on a quest to challenge my knowledge against some of the most intellectually stimulating and chaotic data out there. As Sun Tzu puts it, "In the midst of chaos, there is opportunity."

_________________________Context and Objectives__________________________

Data Source and Ethics:
The imaging data and related information have been sourced from OpenNeuro, a treasure trove of open-source neuroscientific data (https://docs.openneuro.org). My approach to this project is that of a passionate neophyte in the field of neuroscience, keen on exploring the deep data ocean to discover how AI can uncover hidden patterns. The data utilized in this project is GDPR-compliant, involving 60 participants, ensuring respect for privacy and ethical standards.

Project Ambitions:
The objectives of this endeavor are threefold:

1 - To leverage cutting-edge AI to parse through real-time brain iMRI data and time-lapse sequences, searching for patterns linked to neurological events.
2 - To delve into data pre-processing and feature engineering, setting the stage for sophisticated deep learning applications.
3 - To conduct a sociological analysis, grouping patients into clusters and scrutinizing brain images for discrepancies in neural responses to identical stimuli.

Perspective and Resolve:

As a newcomer to the realm of neuroscience, I bring an unbiased lens and a zeal for discovery that I hope will shed light on new facets of the brain. This project is a testament to the belief that a fresh perspective can unearth novel insights, particularly when combined with a methodical and innovative approach to data analysis.

I step into this project with the humility of an 'idiot' who dares to venture into the unknown, as Michel Audiard aptly put it. Yet, it is precisely this audacity to attempt the seemingly impossible that can lead to breakthroughs. After all, the 'idiot' who tries is more likely to succeed than the sage who remains passive. The true measure of wisdom may well lie in the willingness to act upon it.

So, let the journey begin — where the audacious 'idiot' meets the meticulous scientist, and together, we strive to unravel the mysteries of the human brain.


_________________________Engineer aspects ______________________________

To enhance the processing speed of our AI, we've opted to utilize Spark for the core deep learning operations. Spark outshines CUDA when it comes to scaled machine clusters, offering efficient parallel computing across multiple nodes. While CUDA excels in single machine systems with a high concentration of GPUs, Spark provides us the flexibility to expand and harness multiple clusters. Though it offers less granular control over memory management, Spark's ability to scale and utilize GPU acceleration libraries makes it the preferred choice for our ambitions of scaling up.

Our initial foray will engage a single-node Spark cluster, but there's a keen interest in integrating a second machine into the Spark cluster to leverage dual computing power.

________________________Results so Far__________________________________

The application of AI has allowed us to isolate distinct clusters of patients. The insights gleaned from these clusters remarkably mirror the societal and healthcare challenges faced in the US, all derived from a detailed questionnaire. Out of 59 participants, 17 have been successfully clustered. The limited number may stem from the multitude of factors considered. A second iteration is planned, aiming to streamline the model by focusing on essential factors determined by the AI itself, potentially leading to more comprehensive clustering.

Step 1 (first iteration) is now complete.





