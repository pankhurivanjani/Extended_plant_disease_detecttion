**Dataset Selection Reviews**

1. **Plant_leaves**

* Dataset contains fruits like Guava Jamun Lemon Mango Pomegranate OR Arjun Basil Chinar

* Each has healthy and diseased images between 150-300 each

2. **plantae_k**

* Dataset contains kashmiri fruits apple apricot cherry cranberry Grapes peach pear walnut

* Each has healthy and diseased images between 50-90-150 each

3. **PlantDoc-dataset**

* Bell pepper, corn,potato, tomato (many diseases), grape leaf, apple 

* test => around 10 images

* train => round 60-80

* Already research paper is also there with this dataset

** [paper1](https://www.researchgate.net/profile/Manish_Chandra18/publication/341322315_CLASSIFICATION_OF_VARIOUS_PLANT_DISEASES_USING_DEEP_SIAMESE_NETWORK/links/5ebaa82f299bf1c09ab52e48/CLASSIFICATION-OF-VARIOUS-PLANT-DISEASES-USING-DEEP-SIAMESE-NETWORK.pdf)

** [survey-paper2](https://arxiv.org/abs/2006.11391)

4. **Kaggle new-plant-disease-dataset**

* Augmented dataset of plant village

* Apple(many), corn, potato(many), tomato(many), 

* Various notebooks available of projects using this dataset for comparison

5. **crowdAI-dataset**

* plantvillage dataset but coz of submissions we can get benchmarks and stuff

6. **UCI dataset**

* Rice-specific 

* KInda 6 years old

7. **Digipathos Plant Disease Image Database == database provided by EMBRAPA (Brazilian Agricultural Research Corporation)**

* Soyabean, citrus, coconut, dry bean, corn, passion fruit, coffee,  grapevine, cashew, cassava

* like 50-60 images in some, lesser in others

* Can't find any benchmarks for now


*Final-notes*

Plant villages dataset is actually very useful if used in combination with other dataset too. For fruits plant_leaves and plant_k seems to be best, for tomato potato, corn bell pepper we can get from plant village as well as plant doc. Using augmented dataset along with plant village would be good again. 

Focusing on the crops/veggies/fruits would make it easier to finalize the datset accordingle.

If large dataset is required in training, few crops will be automatically eliminated

Is it possible to combine two different datasets?

Mostly datasets have a single leaf, multiple leaves part is next challenge. So, should we try looking into this part too?
