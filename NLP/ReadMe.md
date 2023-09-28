Code implemented on Python 3.9.10
To make these program work you have to install:
tensorflow and numpy
{
!pip3 install tensorflow
!pip3 install numpy
}

Train is for training the model and saving it. For better accuracy you can add news and do not forget to update list of labels
(If you add news as a good ones, add number of these news as in the 101 line in the code.
for i in range(x+(number of added news)) where x is existing number.)

Recognise is for recognising news. Just add data set with news (data.csv as implemented in the code)
It is important to have dataset in 2 columns (date, news)
 
