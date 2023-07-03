********** Important Information for Stock Price Forecasting **********

To achieve the best results based on the performance of the models, it is necessary to apply Hyperparameter Tuning (HPT). This process involves creating an array of parameters and systematically testing individual values for each parameter to find the optimal combination that yields the best results.

Applying Hyperparameter Tuning can be time-consuming depending on the specifications of your computer system. For forecasting tasks conducted in environments like JupyterLab and Jupyter Notebook, your computer will initially utilize the CPU and RAM resources for processing and tuning optimization. To expedite the process, you can make use of the cloud-based service provided by Google by clicking on the link below. The cloud-based system offers the option of selecting "None - TPU - GPU" for the runtime environment in your work. By choosing "GPU" as the runtime, you enable the utilization of your computer's graphics card, which can accelerate the processing speed.

Google Colaboratory: "https://colab.research.google.com/"

NOTE: Google Colaboratory provides a limited free service. When using GPU resources, it may terminate the GPU usage once a certain limit is reached, which can lead to the interruption of your work.

***** How can I activate GPU usage on my computer? *****

If you have an NVIDIA graphics card on your computer, you can leverage GPU utilization in JupyterLab and Jupyter Notebook environments with the help of the "tensorflow" library. Tensorflow can seamlessly integrate with the "CUDA" core architecture present in NVIDIA graphics cards.

You can visit the website linked below, navigate to the GPU section, and find out which version of tensorflow is compatible with which "CUDA" and "cuDNN" architecture. Based on that information, you can easily download the corresponding versions.

Tensorflow Source: "https://www.tensorflow.org/install/source_windows?hl=en"

Currently:

Tensorflow version 2.10.0 is compatible with:
- Python versions between 3.7 and 3.10
- CUDA version 11.2
- cuDNN version 8.1

Additionally:

CUDA® architectures support NVIDIA graphics cards with architectures 3.5, 5.0, 6.0, 7.0, 7.5, 8.0, and above. You can click on the link below to visit the CUDA page and check the CUDA architecture of your graphics card and its compatibility.

CUDA® architectures page: "https://developer.nvidia.com/cuda-gpus"
CUDA® toolkit: https://developer.nvidia.com/cuda-toolkit-archive
cuDNN drivers: https://developer.nvidia.com/rdp/cudnn-archive

NOTE: For desktop computer graphics card architecture information, use the "GeForce and TITAN Products" tab. For laptop computer graphics card architecture information, use the "GeForce Notebook Products" tab.

NOTE: Ensure that your NVIDIA graphics card drivers are up to date. Tensorflow currently supports NVIDIA graphics card drivers v450.80.02 or above. Use the link below to find and download the latest version of your graphics card driver.

NVIDIA GPU Drivers: "https://www.nvidia.com/download/index.aspx?lang=en-us"