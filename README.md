# Micro Elbow Fitting assembly defect detection in manufacturing process.

## What do elbows do?
In addition to the flex point for your arm, elbows are industrial fittings that change the direction of piping. The connections allow you to reroute regularly threaded pipes to turn corners or fit in limited space without the expense of buying a pipe bender.

Standard elbows come in a few different angles – 45°, 90°, and, although they are less common, 22.5° angles – and can be made of the same materials as any other piping. We have a wide selection of elbows and other fittings in stainless steel 304 or 316.

[More](https://www.directmaterial.com/fittings-what-is-an-elbow)

# Problem statement
When manufacturing micro elbow fittings that used in aeronautical and medical equipment quality of the assembly is an utmost concern. Given the size of the fitting is less than 10mm x 10mm, the defect detection process is painstaking. The process has to be automated. 

#Objective 
To build a defect detection system using deep learning models.

#Build summary
Using ImageNet VGG16 weights and transfer learning a model is built on TensorFlow framework.
 
# Conclusion
Model was able to achieve valuation accuracy of 100% with training and valuation loss almost near to 0. Able to predict hardest to find rejects like barb connector screw being not fully engaged. Overall, satisfied of the performance with the limited number of image data used; but in future heavy image augmentation maybe reduced or replaced by more image data.
