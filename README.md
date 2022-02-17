# CycleGAN-for-MRI-Images

There are two main types of MRI images, T1-weighted MRI and T2-weighted MRI images. Both types of MRI contrast different regions within the body.</br>
T1-weighted images specifically highlight fat tissue, while T2-weighted images highlight both fat and water within the body.</br>
T1-weighted → fat issue appear to be bright</br>
T2-weighted → both fat and water regions appear to be bright</br>

Difference between T1-weighted and T2-weighted</br>
![image](https://user-images.githubusercontent.com/60288450/154500260-5fba418c-0ee9-4dbd-bbae-852ce0837347.png)

Having both types of MRI scans can drastically enhance the accuracy of diagnosis by providing practitioners with a more comprehensive understanding.</br>
However, in practice, pathologists rarely have access to both types of MRI images for review and diagnosis purposes. This is because of a variety of reasons such as certain scan time limitations as well as other factors such as distorted contrast found in MRI images due to noise or artifacts.</br>
One of the ways to overcome these inefficiencies is to use a type of artificial intelligence technique called style transfer to synthesize MRI images of different contrast levels from existing MRI scans.</br>
Cycle Generative Adversarial Networks (CycleGAN) is an algorithm used to synthesize T1-weighted MRI images from T2-weighted MRI images and vice versa.</br>

## Total number of Epochs: 60
## Output at 26th Epoch
![image](https://user-images.githubusercontent.com/60288450/154499186-a6a36f28-d0f4-443f-a8df-29adf1d020f7.png)

## Output at 30th Epoch
![image](https://user-images.githubusercontent.com/60288450/154499426-653cf62c-20d7-4641-93b9-40fda542964e.png)
