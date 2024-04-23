# online_face_recognition_and_detection
online_face_recognition_and_detection

ToDo:
* Face Recognition model:
	- [x] Load a pre-trained model
	- [x] Apply incremental learning for new faces

* Face Tracking Pipeline:
	- [x] Face Tracker
 	- [ ] Combine MTCNN and KCF tracking
  		- [ ] Detect face using MTCNN and apply tracker
    		- [ ] Leverage CV algorithms to fast compare frames and use MTCNN where appropriate (new person joining the frame) -> stress on retaining high FPS  	 	
 	
* Finetune model online/Incremental learning:
  	- [ ] Finetune the model online 
