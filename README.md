# K-Nearest Neighbor Based Spoken Letter Recognition

**Project Summary**: Spoken letter recognition is the task of hearing a spoken letter and identifying the corresponding written letter, e.g. hearing the letter "B" and providing the written letter B. This project examines whether a K-Nearest Neighbor (KNN) model can complete the task of spoken letter recognition. In order to do so, a KNN model was trained on a multi-class dataset of isolated spoken letters. As said dataset is high-dimensional, Principal Component Analysis was used to reduce data dimensionality from 617 to 179, and a ball tree was used to improve the KNN model's efficiency. Ultimately, the resulting KNN performed well, achieving a macro-precision, macro-recall, and macro-F1 score of 0.93. Letters with distinct pronunciations were easiest for the model to classify - H, I, O, W, R, X, Y, while letters with pronunciations similar to other letters of the alphabet were hardest for the model to classify - B, M, N, P, V. 

***

#### File Structure 

| File/Folder Name | Function |
| ------ | ------ |
| isoletData | contains ISOLET, the data used in the project |
| papers | research papers related to/used in the project |
| KNN_Model_Visualization.ipynb | contains data preprocessing, the KNN model, and visualizations of results |
| Project Proposal.pdf | the initial project proposal |
| Project Report.pdf | the final project report |
| Project Presentation (Slides).pdf | the slides for the project presentation|

The recorded project presentation can be found here: https://drive.google.com/file/d/1tIaCXCMZbT3GPmfd-b_dtlrKH77lqrAJ/view?usp=drive_link

***
#### How to Use

To run the project, run the provided Jupyter notebook. The following libraries are required: 


| Required Libraries | 
| ------ | 
| pandas |
| NumPy | 
| scikit-learn | 
| matplotlib | 
| seaborn |

***

#### References 

[1] R. Cole, Y. Muthusamy, and M. Fanty. “The ISOLET spoken letter database.” 1996. \
[2] M. Fanty and R. Cole. “ISOLET”. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/54/isolet. \
[3] M. Fanty and R. Cole. “Spoken letter recognition”. Advances in Neural Information Processing Systems (NIPS Conference). 1990. pp. 220-226. \
[4] T. Liu, K. Yang, and A. Moore. “The IOC algorithm: efficient many-class non-parametric classification for high-dimensional data”. Proceedings of the Tenth ACM SIGKDD International Conference on Knowledge Discovery and Data Mining. 2004. \
[5] F. Markus. “Why is speech recognition difficult?”. Semantic Scholar. 2003. \
[6] H. Nock and S. Young. “Loosely coupled HMMs for ASR”. Sixth International Conference on Spoken Language Processing (INTERSPEECH). 2000. \
[7] Pedregosa et al., “Scikit-Learn: machine learning in Python”, Journal of Machine Learning Research, vol. 12. 2011. pp. 2825-2830. 

---


