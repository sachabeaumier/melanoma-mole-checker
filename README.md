To access Notebook, click Binder and run each codeblock sequentially

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sachabeaumier/melanoma-mole-checker.git/HEAD)


This project/repo is a successful proof of concept test in regards to applications of Deep Learning engineering on problems within the domain of Bioinformatics. This repo builds on the paper by Codella, N.C., Gutman, D., Celebi, M.E., Helba, B., Marchetti, M.A., Dusza, S.W., Kalloo, A., Liopyris, K., Mishra, N., Kittler, H. and Halpern, A., 2018, April. Skin lesion analysis toward melanoma detection: A challenge at the 2017 international symposium on biomedical imaging (isbi), hosted by the international skin imaging collaboration (isic). In 2018 IEEE 15th International Symposium on Biomedical Imaging (ISBI 2018) (pp. 168-172). IEEE. .

This PyTorch script when run allows users to upload an image of a mole to probabilistically determine whether they are a Melanoma, Nevus or Seborrheic Keratosis. This application is trained and validated with data collated by Pablo Lopez Santori (University of Edinburgh) as available at https://www.kaggle.com/datasets/wanderdust/skin-lesion-analysis-toward-melanoma-detection and implements the Resnet18 Deep Learning Model which has been pretrained for the purposes of solving problems in the domain of Image Classification Machine Learning.

Melanoma would be considered cancerous and if found, would be advised to see a doctor/dermatologist. Nevus moles are considered borderline and has the capacity to turn Melanomic (it would be advised to keep track of theses moles and see if they change in the future as there is possibility for a Nevus mole to become Melanomic). Seborrheic Keratosis is considered non-cancerous.

This PyTorch script is at present a minimal viable product/personal project for the purposes of increasing developer knowledge in the domain of Deep Learning. Further work is required in regards to fine-tuning of models for higher degrees of accuracy - as well as deployment as a web application microservice (msg me if you're keen to collaborate). also pls note this  author accepts no liability for findings found therein.
