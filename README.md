# GRADE-ToothFairyChallenge
ToothFairy: Cone-Beam Computed Tomography Segmentation Challenge – MICCAI 2023, Global Reference Attention Guided Segmentation (GRADE)

* train_lq.py : coarse segmentation on low resolution dense pseudo-labels -> probability maps - global context reference
* train_lq_finetune.py : fine tuning on ground truth labels
* train_grc_pretrain.py : fine segmentation on high resolution dense pseudo-labels, use of gcr as 2ch input
* train_gcr_finetune.py : fine tuning on ground truth labels - high resolution

src: train models
challenge: submit a challenge docker container  

