# Fake tasks & CGAN

# Description
Nowadays the world is suffering from fake tasks. So, the purpose of Generative 
Adversarial Networks (GAN) is to build two networks one network called 
generator which is specified to generate fake tasks, and the other network called 
discriminator which is used to distinguish between the fake and legitimate tasks. 
But the GAN has some limitation is being overcome by conditional GAN (cGAN) 
which is passed the label class to the network. So, in this project we first establish 
our models which are random forest, naïve based, and Adaboost to just classify 
fake and legitimate tasks. Then we applied a generator to generate 2000 fake tasks 
and then passed these fake tasks to models to see its performance which is be very 
low because he will test data see it for first time. After that, we applied a 
discriminator to those fake tasks to be distinguished and labeled then we applied 
the fake tasks to the models again to see its performances after the discriminator 
which is increased from 59% to 92% for a random forest algorithm and for 
Adaboost 57% to 93%.



   
# Conclusion :

In this project, we used three different stages to classify legitimate and fake tasks. 
First, we admit classical machine learning algorithms such as random forest, 
Adaboost, naïve based, ensemble vote, and ensemble weighted which are 97% for 
ensemble weighted, ensemble vote, Adaboost, 100% for the random forest, and 
finally 85% for naïve based classifier. The second technique was to generate 2000 
fake tasks using a generator network and then we applied random forest, 
Adaboost, and naïve-based algorithms we notice that the accuracy is very low 
which are 59%, 57%, and 50% respectively because the model classifies data as 
the first time, we learn on it. The third technique used the discriminator network 
to distinguish between legitimate and fake tasks then we applied the machine 
learning algorithms we notice the accuracy increased hugely which are 92% for 
the random forest, and 93% for the Adaboost classifier. 
