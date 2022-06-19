# coding3-final-work

Throughout the semester, I have learnt some models about machine learning and tried to apply some of them in my class quiz.
In the final work, I first tried to apply the DCGAN I learnt in the course to run a dataset on cats. However, the results were not what I was expecting. 
![dcgan](https://user-images.githubusercontent.com/91951125/174497301-7e9e197e-eb94-4d83-a775-c3dd1bbcdf3b.gif)


I then found the pix2pix library, which did what I was hoping for. It was recently peony season and I really like peony flowers, so I created datasets of peony flowers for training. The peony flowers were restored through line drawings. (The datasets I uploaded to GitHub). Afterwards I put my datasets into this pix2pix model for training. The finished image turned out as follows. During this process I tried to modify the optimiser and some values, which didn't work very well. The number of datasets I had was not enough images due to time issues. I believe that if I had a larger number of datasets, the training might have worked better.
<img width="1101" alt="截屏2022-06-18 02 01 59" src="https://user-images.githubusercontent.com/91951125/174497346-1a2f363a-8124-44b2-a747-9f304b0da960.png">


Source Code GitHub：https://github.com/tensorflow/docs/blob/master/site/en/tutorials/generative/pix2pix.ipynb
