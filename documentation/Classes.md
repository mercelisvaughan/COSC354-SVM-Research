#   
  
Classes:  
OpenCV class, SVM model class, helper functions  
  
OpenCV class  
- face_cascade  
- eye_cascade  
+ detect_face(img)  
+ detect_eyes(img)  
  
Helper  
+ store_faces(results_of_faces: List[img])  
  
SMV Model  
- model: svm.SVC  
+ train()  
+ predict()  
+ evaluate()  
  
SVM MODEL USES -> HELPER FUNCTIONS   
HELPER FUNCTIONS GET DATA FROM -> OPENCV CLASS  
  
USER INJECTS DATA IN OPENCV CLASS  
