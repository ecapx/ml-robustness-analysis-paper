# Robustness Analysis of Machine Learning Models using Domain-Specific Test Data Perturbation
This study examines how perturbations in image, audio, and text inputs affect the performance of different classification models. Various perturbators were applied to three seed datasets at different intensities to produce noisy test data. Then, the models' performance was evaluated on the generated test data. The findings indicate that there is a consistent relationship between larger perturbations and lower model performance across perturbators, models, and domains. However, this relationship varies depending on the characteristics of the specific model, dataset, and perturbator.

## Tested Datasets & Models
### Image
Dataset: [ImageNetV2](https://github.com/modestyachts/ImageNetV2)

Models:
- [XCeption](https://keras.io/api/applications/xception/)
- [InceptionResnetV2](https://keras.io/api/applications/inceptionresnetv2/)
- [MobileNetV2](https://keras.io/api/applications/mobilenet/#mobilenetv2-function)

### Audio
Dataset: [Speaker Recognition](https://www.kaggle.com/datasets/kongaevans/speaker-recognition-dataset)

Model: [Speaker Recognition CNN](https://keras.io/examples/audio/speaker_recognition_using_cnn/)

### Text
Dataset: [AclImDB](https://ai.stanford.edu/~amaas/data/sentiment/)

Model: [Text Classification](https://keras.io/examples/nlp/text_classification_from_scratch/)


## Results
### Image
![ImageNetV2 Results](images/image_results.png)

### Audio & Text
![Speaker Recognition Results](images/audio_text_results.png)
