# Alzheimer-s-Disease-Classifier
The aim of this project is to use features extracted from MRI images, together with additional data, retrieved from the Alzheimer’s Disease Neuroimaging Initiative (ADNI) database (http://adni.loni.ucla.edu/ and www.adni-info.org) to classify the healthy cognitive normal (CN) subjects and patients with Alzheimer's Disease (AD)

These features come from a number of healthy cognitively normal (CN) subjects and patients with Alzheimer’s Disease (AD).

## Dataset Description

This dataset contains information from 220 subjects based on features extracted from MRI images and additional data from Alzheimer's Disease Neuroimaging Initiative (ADNI) Database. These features come from a number of healthy cognitively normal (CN) subjects and patients with Alzheimer’s Disease (AD).

## Data Dictionary

RID: Individual identifier
BRAIN: Whole Brain. A summary measure of total brain parenchyma, including the Cerebral-Cortex, Cerebellum-Cortex, Thalamus-Proper, CaudatePutamen, Pallidum, Hippocampus, Amygdala, Accumbens-area, VentralDC, Cerebral-White-Matter, Cerebellum-White-Matter, and WM-hypointensities. As such, it does not include ventricles or other CSF spaces, and is not intended to be used as a measure of intracranial volume.
        
EICV: Estimated Intracranial Volume, aka eTIV. To generate the mask, the baseline image is automatically segmented; all thus-defined brain and ventricular voxels are given the value 1 with all other voxels 0. This binary mask is then repeatedly smoothed with a Gaussian kernel to produce a simply connected uniform mask, covering all sulci, whose boundary tapers smoothly from 1 to 0 over the length of a few voxels. Ideally, the mask would end on the skull and include the brain stem down to where it starts to bend with the neck. The smoothing can be controlled fairly nicely to begin tapering at the skull, so that voxels with a mask value less than 1 can be considered outside the ICV and therefore ignored.

VENTRICLES: Ventricles

LHIPPOC: Left Hippocampus

RHIPPOC: Right Hippocampus

LINFLATVEN: Left inferior lateral ventricle

RINFLATVEN: Right inferior lateral ventricle

LMIDTEMP: Left Middle Temporal

RMIDTEMP: Right Middle Temporal

LINFTEMP: Left Inferior Temporal

RINFTEMP: Right Inferior Temporal

LFUSIFORM: Left Fusiform

RFUSIFORM: Right Fusiform

LENTORHIN: Left Entorhinal

RENTORHIN: Right Entorhinal

DXCURREN: Diagnostic status: 0 implies negative (normal) and 1 implies positive (demented)

