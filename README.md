# COVID-19 Xray Detection using Convolutional Nueral Network (CNN)

## What is Covid 19?
The 2019 novel coronavirus (COVID-19) presents several unique features. While the diagnosis is confirmed using polymerase chain reaction (PCR), infected patients with pneumonia may present on chest X-ray and computed tomography (CT) images with a pattern that is only moderately characteristic for the human eye Ng, 2020. COVID-19’s rate of transmission depends on our capacity to reliably identify infected patients with a low rate of false negatives. In addition, a low rate of false positives is required to avoid further increasing the burden on the healthcare system by unnecessarily exposing patients to quarantine if that is not required. Along with proper infection control, it is evident that timely detection of the disease would enable the implementation of all the supportive care required by patients affected by COVID-19.

## What is Convolutional Neural Network?
A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics.

## Dataset
We used dataset from kaggle --> kaggle.com/khoongweihao/covid19-xray-dataset-train-test-sets

## Project Goals
As we know, lung condition examination at the hospital takes a long time to see the results. Therefore, I created pneumonia detection to help doctors identify if there is an anomaly or something in the human lungs through x-ray images.

The trained model will be used to predict whether the uploaded image indicates pneumonia or normal.
