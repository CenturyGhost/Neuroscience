Alexandre Nouar's projects - neuroscience and AI unique insights.

Source images and data were collected on OpenNeuro, https://docs.openneuro.org/index.html# This project is intended to make pattern matching of realtime brain iMRI and timelapse of events triggering reaction. We use 60 GDPR-friendly patients' data with data pre-processing and feature engineering so data can be used for deep learning.

It is intended to use Spark for core deep learning operations, indeed it is better for scaled machine clusters than CUDA, and can use (lesser indeed, but 2 GPUs with Spark libraries will still perform better than one in CUDA) the same libraries, even though less efficient. Cuda is better machine-wise (one big set of GPU's in a single machine system), Spark is better for several clusters. Both use parallel computing, even if CUDA enables a more granular way of memory management.

python3 -m pip install tensorflow[and-cuda]
# Verify the installation:
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"