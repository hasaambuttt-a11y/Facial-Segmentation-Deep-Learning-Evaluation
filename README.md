# Facial-Segmentation-Deep-Learning-Evaluation

## Goal:
Compare classical mathematical edge detection methods against modern deep learning architectures for facial recognition in complex environments.  

## Technical Stack:
Python, OpenCV, MTCNN, K-Means Clustering, HOG+SVM.  

## Key Methodology:
Manually implemented 1st Derivative (Sobel, Prewitt) and 2nd Derivative (Laplacian, LoG) operators to analyze edge detection robustness.  
Evaluated the precision of Haar Cascades and HOG+SVM against a three-stage MTCNN refinement process.  

## Technical Insight:
Analyzed "noisy" environments (e.g., Times Square) to prove that deep learning models learn features in layers, outperforming human-defined gradients in chaotic settings.  
Used the Elbow Method for optimal K selection in unsupervised pixel-based segmentation.  

## Outcome:
Demonstrated that deep learning is the most robust choice for real-world facial analysis compared to classical speed-focused methods.
