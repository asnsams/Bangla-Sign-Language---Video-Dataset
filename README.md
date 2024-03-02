# Bangla Sign Language Video Dataset

This repository hosts a collection of datasets for Bangla Sign Language video dataset, aimed at supporting research and development in sign language recognition and machine learning. Below is a summary of the available datasets. 

# Remarks: 
* I skipped video dataset for Bangla letter recognition, as to the best of my knowledge, Bangla sign language users do not actively use them to communicate with each other. So, future research should focus on Word-level or Continuous Sign Language.
* Same for Static/Image-based Sign language, as most of the sign actions can not be showcassed through images which make the approach redundant.


This repository hosts a collection of Open access and public datasets and papers for Bangla Sign Language, aimed at supporting future research and development in sign language recognition and machine learning. Below is a summary of the available datasets.

| Dataset               | Continuous/Word-level | Word-Classes | Type                 | Videos | Signers | Availability  | Paper Link                               | Dataset Link                        |
|-----------------------|-----------------------|---------|----------------------|--------|---------|---------------|------------------------------------------|------------------------------------|
| SignBD-Word  [1]         | Word-level            | 200 [subclass 90]    | RGB, Skeleton        | 6000   | 14 |  Public     | [Link to PDF](https://drive.google.com/file/d/1GAjHdofGGxOfCnD81pvdiocs53M3ZucQ/view) | [Link to Dataset](https://sites.google.com/view/signbd-word/dataset)|
| MVBSLW50 [2]    | Word-level | 50       | RGB, Skeleton         | 4000  | 40     | Private| [Link to PDF](https://arxiv.org/pdf/2302.11559.pdf)              | None |
| BdSL40 [3] | Word-level | 40       | RGB | 611 | N/A      | Public | [Link to PDF](https://arxiv.org/pdf/2401.12210.pdf)            | [Link to Dataset](https://github.com/Patchwork53/BdSL40_Dataset_AI_for_Bangla_2.0_Honorable_Mention)|
| BdSLW60 [4] | Word-level | 60      | RGB | 9307 | 18      | Public | [Link to PDF](https://arxiv.org/ftp/arxiv/papers/2402/2402.08635.pdf)              | [Link to Dataset](https://github.com/Patchwork53/BdSL40_Dataset_AI_for_Bangla_2.0_Honorable_Mention)|

The datasets listed above are compiled to facilitate the development and testing of algorithms for Bangla Sign Language recognition. Each dataset varies by the number of classes, type of data provided (e.g., RGB video, depth maps, skeleton data), the total number of videos, the number of signers, availability (whether the dataset is publicly available or private), and links to the dataset's descriptive PDF and the dataset itself.

## Availability

The availability column indicates whether a dataset is publicly accessible or private. For datasets marked as private, researchers may need to contact the dataset providers for access permissions.

## Acknowledgements

We acknowledge the contributions of all the researchers and participants who have made these datasets available for the broader research community.

For more information or to contribute to this collection, please contact [contact-information].

**Cite my paper if this repo helped you in any way! **

_A. Sams, A. H. Akash and S. M. M. Rahman, "SignBD-Word: Video-Based Bangla Word-Level Sign Language and Pose Translation," 2023 14th International Conference on Computing Communication and Networking Technologies (ICCCNT), Delhi, India, 2023, pp. 1-7, doi: 10.1109/ICCCNT56998.2023.10306914.
_

**Reference: **
[1] A. Sams, A. H. Akash and S. M. M. Rahman, "SignBD-Word: Video-Based Bangla Word-Level Sign Language and Pose Translation," 2023 14th International Conference on Computing Communication and Networking Technologies (ICCCNT), Delhi, India, 2023, pp. 1-7, doi: 10.1109/ICCCNT56998.2023.10306914.

[2] M. S. Islam, A. J. M. A. Joha, M. N. Hossain, S. Abdullah, I. Elwarfalli, and M. M. Hasan, "Word level Bangla Sign Language Dataset for Continuous BSL Recognition," 2023. [Online]. Available: arXiv:2302.11559.

[3] H. S. Shahgir, K. S. Sayeed, M. T. Tahmid, T. A. Zaman, and M. Z. Ul Alam, "Connecting the Dots: Leveraging Spatio-Temporal Graph Neural Networks for Accurate Bangla Sign Language Recognition," 2024. [Online]. Available: arXiv:2401.12210. [Accessed: day-month-year].

[4] H. A. Rubaiyeat, H. Mahmud, A. Habib, and M. K. Hasan, "BdSLW60: A Word-Level Bangla Sign Language Dataset," 2024, arXiv:2402.08635. [Online]. Available: https://arxiv.org/abs/2402.08635



<!--
A few more papers you can check out on related topic :
* M. A. Rahaman, M. H. Ali, and M. Hasanuzzaman, "Real-time computer vision-based gestures recognition system for Bangla sign language using multiple linguistic features analysis," Multimed Tools Appl, vol. 83, pp. 22261–22294, 2024. [Online]. Available: https://doi.org/10.1007/s11042-023-15583-8
* 

