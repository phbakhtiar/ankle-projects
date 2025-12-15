# ankle-projects
Codes are related to my 3D ankle reconstruction project for my PhD

Denoising Auto-Encoder based networks:
The Joint extraction networks receive X-ray images of ankle (localized) and extracts the Tibiofibular Joint from it. The anteroposterior (AP) images and lateral (LT) iamges are different in their size, so two separate networks are implemented.

VGG-16 Regressor:
The Reconstruciton network is desined to receive the AP and LT images of the joint and reveal the shape and pose parameters of a Statistical Shape and Intensity Model (SSIM) of the joint.

The networks are tuned by grid search hyper parameter optimization technique in separate files.
