+++
title = 'The Impact of Biases in Facial Recognition Artificial Neural Networks'
date = 2024-03-08T17:31:11-05:00
draft = false
tags = ["project","ComputerScience"]
summary = "SUNY Oswego Honors Thesis"
+++

In the field of artificial intelligence, the topic of neural network prejudice and bias is becoming more well-known by the day. More instances of unethical AI practices have been documented by the [AIAAIC database](https://www.aiaaic.org/aiaaic-repository), with instances branching outside of the scope of this project. It is now well understood that there is a major issue with how we are currently creating neural networks, because a lot of the facial recognition software (whether it be for commercial or personal use) that is being created is deeply flawed in regards to accuracy and equity between populations. For example, there have been many studies that show facial recognition and automatic gender recognition (AGR) technology's accuracy rates are significantly worse on [Black Women](https://www.media.mit.edu/projects/gender-shades/overview/) and/or [transgender](https://www.morgan-klaus.com/pdfs/pubs/Scheuerman-CSCW2019-HowComputersSeeGender.pdf) people. Because of this influx of new research on the subject of AI Ethics since [around 2014](https://hai.stanford.edu/news/2022-ai-index-industrialization-ai-and-mounting-ethical-concerns), I decided to try my hand at helping the field try to mitigate this issue, because of the devastating real-life effects that this can have when this technology is deployed commercially or by the government on these populations.

For the basis of my honors thesis at SUNY Oswego, I used two convolutional neural network (CNN) models that allowed me to probe some pressing questions on facial recognition neural network biases:

  1. How do biases infiltrate neural networks and affect their accuracy rates?
  2. What are the real-life effects of the reprecussions caused by these biases on marginalized groups of people?
  3. How can we mitigate some of the biases leading to gender prejudice in neural networks?

1) There have been many studies which have shown the wide array of ways that biases can infiltrate neural networks; one notable mention being through unbalanced datasets. This means that a lot of the datasets being used to train facial recognition neural networks are mostly cisgender white men, and therefore affect the accuracy rates to be better on that group. This disproportionately affects groups that are traditionally underrepresented (both in these datasets and in other places), such as transgender people and non-white individuals.

2) These biases can negatively affect these marginalized groups, which is shown through the real-life reprecussions that have already been discovered. Some considerable instances include [police](https://towardsdatascience.com/how-bad-facial-recognition-software-gets-black-people-arrested-3c02738a3d54) using facial recognition software to identify criminals, and instead misidentifying innocent Black individuals as criminals, as well as the potential for [transgender](https://dl.acm.org/doi/10.1145/3173574.3173582) people being misgendered by machine learning algorithms not being able to change their prescribed gender, leading to harmful [mental health effects](https://psycnet.apa.org/doiLanding?doi=10.1037%2Fsah0000070).

3) I hypothesize that we can mitigate some of the potential biases leading to racial and gender prejudice in facial recognition technology by opting for a balanced dataset for training, as well as moving forward in the future instead of using a male/female binary gender option, opting to use a masculine/feminine continuous spectrum.