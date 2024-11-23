The proposed model uses Genetic Algorithm to find the best feature extractor among the famous pre - trained deep leaning models such as VGG19,ResNet50 and DenseNet121.
After mentioning the feature extractors, we are using three dense layers. The genetic algorithm is also used to find the best suited number of nuerons and the activation functions. The accuracy of the model is 97.3%.

to run the model use following code 

new_model = tf.keras.models.load_model('best_driver_distraction_model.h5')
new_model.summary()

now you can perform any .evaluate() or .fit() on the loaded model
