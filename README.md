# Dog-Classification-Classification
This is a Deep Learning Model built using the a library called fast.ai which, has gather a large  amount of hype in current day,for its simplicity in code and length of the code we write write to built a model.
![Screenshot from 2019-05-23 21-06-53](https://user-images.githubusercontent.com/29728855/58266484-5cb2bb00-7d9f-11e9-864b-4574ab70ae4c.png)

I have used the [Oxford-IIIT Pet Dataset](http://www.robots.ox.ac.uk/~vgg/data/pets/) by 
[O. M. Parkhi et al., 2012](http://www.robots.ox.ac.uk/~vgg/publications/2012/parkhi12a/parkhi12a.pdf) 
which features 12 cat breeds and 25 dogs breeds. 
Our model will need to learn to differentiate between these 37 distinct categories.
According to their paper, the best accuracy they could get in 2012 was 59.21%, 
using a complex model that was specific to pet detection, with separate "Image", "Head", and "Body" models for the pet photos. 

The dataset can downloadd by using `untar_data` function to which we must pass a URL as an argument and which will download and extract the data.

## The Model built using fast.ai library is now it is 96% (2019) accurate whch is very much better than the paper accuracy with is 59.12% in 2012.
