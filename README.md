# Can_a_Phone_Camera_Identify_Baby_In_Utero
One of my most fun projects to date. I wanted to see if I could use an algorithm to identify a baby in utero through a phone camera. Discussion here. 

Whether it's one's first pregnancy or one's 50th, there's often a lot of anxiety surrounding the question of if the baby is doing ok. 

I've long been interested in optical monitoring methods (like light) using simple technology (in this case a camera phone). And was very interested if I could somehow identify my baby in-utero using only a phone camera. 

A very simple project anyone can do is to mimic a pulse ox with a video of a patch of skin and look for the delta in pixels. After all, a pulse oximeter detects the amount of light passed through the skin and measures the difference. So if one looks for the delta, one can at least get a very simple reading of heart rate. 

For my own experimentation I've found that adding a flashlight can add too much light scatter to an image and make it hard to visualize any features below. So just standard lighting is often acceptable for this.

My question, was given that a fetal (baby's) heart rate is also different than an adult's, could I look for the delta within the delta to find an image of the baby? I used a video of my own stomach to test out this potential technology (I also had to wiggle my phone camera around a lot as this little girl can move!) and aimed it at the location I knew she should be as confirmed by ultrasound. I first confirmed her location via actual hospital ultrasound and our home ultrasound (We have a $3k Butterfly!). Next I looked for the delta within deltas on frames captured using standard light and was able to find the following outline of a head-down figure with arms and at least one leg. The resolution on this is terrible and I plan to adjust the code to see if I can get it better. But I wanted to share initial results of this work in progress because how cool! 

My next steps are to try and calculate her heart rate and get the code in working condition to either share or deploy on an app. 

![unnamed-1](https://github.com/user-attachments/assets/f71b776b-7243-47ab-bbe1-39dfcbf31151)
