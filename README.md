# CUWT-WHT-ViT: Trait-guided wheat cultivar classification

Ziyang He<sup>1,+</sup>, Gang Sun<sup>1,+</sup>, Greg Deakin<sup>2</sup>, Zhenjie Wen<sup>1</sup>, Robert Jackson<sup>2</sup>, Ji Zhou<sup>1,3*</sup>, Lei Ju<sup>2*</sup>

Ziyang He, heziyang@stu.njau.edu.cn, ORCID: 0009-0001-6862-8449  
Gang Sun, gang.sun@njau.edu.cn, ORCID: 0000-0002-6548-5980  
Greg Deakin, Greg.Deakin@niab.com，[ORCID to be added]  
Zhenjie Wen, WenZhenjie@njau.edu.cn， ORCID: 0000-0002-8191-1070  
Robert Jackson,  Robert.Jackson@niab.com，[ORCID to be added]  
Ji Zhou, Ji.Zhou@njau.edu.cn or JZhou@CEMPS.ac.cn, ORCID: 0000-0002-5752-5524  
Lei Ju, Lei.Ju@niab.com, ORCID: 0000-0002-0048-7440

<sup>+</sup> These authors contributed equally to this work.  
<sup>*</sup> Corresponding authors.

This repository provides the source code, trained deep learning models, example datasets, analysis results and supplementary tables for the article titled **“From Traits to IDs: Multi-trait Learning with Knowledge Distillation for Varietal Classification”**.

The project presents the China-UK Wheat Traits (CUWT) dataset and the Wheat Trait-guided Vision Transformer (WHT-ViT), a trait-guided deep learning framework for field-based wheat cultivar classification using dual-view smartphone images collected from China and the UK.

The complete CUWT image dataset is deposited in Zenodo: **[Zenodo DOI / reviewer link to be added]**.

The main files are as follows:

(1) CUWT dataset.zip - The China-UK Wheat Traits (CUWT) dataset used for model testing and reproducible examples. The complete CUWT image dataset is available through Zenodo: **[Zenodo DOI / reviewer link to be added]**.

(2) Trained deep learning models - The trained WHT-ViT model and trait-teacher models used for wheat cultivar classification and trait-guided learning.

(3) Analysis results - Model evaluation results, baseline comparisons, trait prediction results and source data supporting the main figures.

(4) Supplementary tables - Supporting materials for CUWT construction, trait annotation, model comparison and wheat cultivar classification.

(5) WHT-ViT - Scripts required for the WHT-ViT model to run.

(6) Step1_pre_processing.ipynb - Python-based source code that contains image pre-processing and preparation of dual-view wheat images.

(7) Step2_trait_analysis.ipynb - Python-based source code that contains spike detection, segmentation and extraction of breeder-relevant spike traits.

(8) Step3_WHT-ViT_training_and_evaluation.ipynb - Python-based source code that contains model training, trait-guided knowledge distillation and wheat cultivar classification.

(9) Step4_result_analysis.ipynb - Python-based source code that contains result analysis, statistical comparison and figure source data generation.

To install Python, Anaconda and Libraries

If you wish to run from the source code provided in this project, you will need to set up Python on your system.

• Read the beginner’s guide to Python if you are new to the language: https://wiki.python.org/moin/BeginnersGuide

• For Windows users, Python 3 release can be downloaded via: https://www.python.org/downloads/windows/

• To install Anaconda Python distribution:

1) Read the install instruction using the URL: https://docs.continuum.io/anaconda/install

2) For Windows users, a detailed step-by-step installation guide can be found via: https://docs.continuum.io/anaconda/install/windows

3) An Anaconda Graphical installer can be found via: https://www.continuum.io/downloads

4) We recommend users install the latest Anaconda Python distribution

Some dependencies of the Jupyter notebooks:

       Python=[version to be added];
       PyTorch=[version to be added];
       Torchvision=[version to be added];
       timm=[version to be added];
       ultralytics=[version to be added];
       SAM2=[version to be added];
       Scikit-image=[version to be added];
       OpenCV=[version to be added];
       Pandas=[version to be added];
       Numpy=[version to be added];
       Scipy=[version to be added];
       Scikit-learn=[version to be added];
       Matplotlib=[version to be added];

Data availability

The complete CUWT image dataset is deposited in Zenodo and will be available at **[Zenodo DOI / reviewer link to be added]**.

The GitHub release provides source code, trained model weights, example datasets, analysis results and supplementary tables supporting the results presented in the article. Other data and user guides are available from the corresponding authors upon reasonable request.

License

Source codes, notebooks, example imagery, analysis results and trained DL models are shared under **the MIT license**. The complete CUWT dataset follows the license specified in the Zenodo record **[license to be confirmed]**. For any commercial use, please contact the corresponding authors listed above.
