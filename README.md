2022 

[Report containing all details about project](https://github.com/mickrew/Diabetic-Retinopathy-Detection/files/9641081/Report.pdf)

# Diabetic-Retinopathy-Detection
The objective of the project is to build, develop and compare different neural networks suitable to distinguish the different levels of diabetic retinopathy using Deep Learning techniques.
## Decription
The objective of the project is to build, develop and compare different neural networks suitable
to distinguish the different levels of diabetic retinopathy using Deep Learning techniques.
Diabetic retinopathy, also known as diabetic eye disease (DED), is a medical condition in which
damage occurs to the retina due to diabetes mellitus. Diabetic retinopathy affects up to 80
percent of those who have had diabetes for 20 years or more. At least 90% of new cases could
be reduced with proper treatment and monitoring of the eyes. The longer a person has diabetes,
the higher his or her chances of developing diabetic retinopathy. 

**Diabetic retinopathy** is the main cause of blindness in the working-age population of the
developed world. It is estimated that it affects more than 93 million people. Diabetic retinopathy
(DR) is an eye disease associated with long-standing diabetes. Progression to impaired vision can
be slowed down or avoided if DR is detected in time; however, this can be difficult as the disease
often shows few symptoms until it is too late to provide effective treatment. The need for a
comprehensive and automated DR screening method has long been recognised, and previous
efforts have made good progress using image classification, model recognition and machine
learning.

The **dataset** consists of a large number of high-resolution retina images (~4752x3168) taken in a
variety of conditions. For each subject are provided photos of both the left and right retina.
Images are labelled with a subject ID in addition to a label that specifies whether the photo is left
or right retina (e.g. 1_left.jpeg is the patient’s left eye with ID 1).
A medical specialist then evaluated the presence of diabetic retinopathy in each image on a scale
of 0 to 4, reported below:

0. NO DR
1. Mild
2. Moderate
3. Severe
4. DR Proliferating

The images in the dataset come from different models and types of cameras that can affect the
visual appearance of left and right. Some images are shown for how you could see the retina
anatomically (macula on the left, optic nerve on the right for the right eye). Others are shown as
they would be seen through a microscope condensing lens (inverted) as seen in a typical ocular
examination. To have the dataset balanced and maintain the consistency of data in each photo,
some of them have been reversed in order to always display the same way photos of right or left
retinas. Like any real data set, a minimal amount of noise is present in both images and labels.
Images, for example, may be out of focus, under-exposed or overexposed.
Due to the large size of the dataset (~89GB) a preprocessing phase is required to be able to
manage the material through Google Colab. During this phase we decided to reduce the
resolution of the images, as found in the literature, to 786x524 so as to reduce the size of the
dataset by 99% bringing it up to ~1GB.

The DR has two major types: the Non-Proliferative Diabetic Retinopathy (NPDR) and Proliferative
Diabetic Retinopathy (PDR). The DR in the early stages is called NPDR which is further divided
into Mild, Moderate, and Severe stages.

- **Mild** stage has one micro-aneurysm, a small circular red dot at the end of blood vessels.
- In the **Moderate** stage the micro-aneurysm rapture into deeper layers and form a flame-
shaped haemorrhage in the retina.
- The **Severe** stage contains more than 20 intraretinal haemorrhages in each of the four
quadrants, having definite venous bleeding with prominent intraretinal microvascular
abnormalities.
- **PDR** is the advanced stage of DR which leads to neovascularization, a natural formation of
new blood vessels in the form of functional microvascular networks that grow on the inside
surface of the retina.
