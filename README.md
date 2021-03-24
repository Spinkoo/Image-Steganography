# Image-Steganography
Image Steganography in the frequency domain 

https://youtu.be/XYZ9XcAZiyI

This application is a projection to a steganography idea in the frequency domain based on the jpeg compression on different colorspaces written in c++ and designed by qt 


1-This project and all its tests were made by me - a third year student at the houari boumedien university Algeria -, So i would like any reviews/improvments to make and I would accept any critisim 

2- This algorithm was made to test how far could steganography go in terms of capacity while keeping the secrecy on the cover & the best possible quality of the message after

Pros/Cons of the algorithm :

Pros :

1-It supports big sized messages ( the image message can be as big as the cover go ) 

2-The cover after inserting the message won't have any visual affects ( very little noise and as big the cover goes as it goes better - the message still can go as big & it would be still improving - ) 

3-The cover image noise is measured in psnr after inserting a message as it would be shown for you after the process

4-The message after extraction would be in a good state sometimes it would get a bit corrupt but it's mostly worth it compared with how big the message size can be 

5-For formats like bmp/png the file size wouldn't really be or leave any traceable signs - sometimes the file size gets smaller -

6-The algorithm can be improved to support 3 image message ( of the same size as the cover image )

7-The algoirthm complexity is O(n^2) where n is max(width of cover,height of cover)

Cons : 

1-The cover image can't stand lot of attacks ( after all you can't have perfectly both ways) and the message would be destroyed

2-The message quality decreases 

3-It doesn't support jpeg compression or any compression that affect widely the frequency domain

Side note: I apologize for the design it wasn't made to impress users but just to make it easier for you to try the algorithm and get some reviews

And here I present to you some of the experimental results : the core of the test was to :

1-Compare the noise in the cover image after inserting it ( using PSNR )

2-Compare the similarity between the message before inserting it & after extracting it 

![alt text](https://i.ibb.co/G5ggm0Q/c1.png)

![alt text](https://i.ibb.co/YD1yg1F/c2.png)

![alt text](https://i.ibb.co/sbrJqcH/c3.png)

![alt text](https://i.ibb.co/fp7khwL/c4.png)
