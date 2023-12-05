# Sleep Health and Lifestyle PROJECT
We will use a dataSet from Laksika Tharmalingam, especial thank you!
It can be found in url="https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/data"

Mi notion portfolio project url="https://www.notion.so/Full-Project-Sleep-Health-and-Lifestyle-642b503669cc4aeba79b0dec9323e446?pvs=4"

### What is Sleep?
Sleep is a period of rest. Sleep is a state of reduced mental and physical activity in which consciousness is altered and sensory activity is inhibited to a certain extent. During sleep, there is a decrease in muscle activity, and interactions with the surrounding environment. While sleep differs from wakefulness in terms of the ability to react to stimuli, it still involves active brain patterns, making it more reactive than a coma or disorders of consciousness.

### Why is it important?
Sleep isn’t just a time when your brain and body shut down. Getting enough sleep helps you think more clearly and react more quickly. Not getting enough sleep can be dangerous, not only affecting your performance, but your health and mood, too.

### Purpose of Project
In this analysis we want to determine if:

* There are a relation in between gender or age with the amount of hours of sleep?;
* There are a relation in between profession with the type of Sleep Disorders?
* If sleep quality can be use as a health marker;
* And if so, can we predict health by sleep quality?

### Data Overview
Person ID: An identifier for each individual. Gender: The gender of the person (Male/Female). Age: The age of the person in years. Occupation: The occupation or profession of the person. Sleep Duration (hours): The number of hours the person sleeps per day. Quality of Sleep (scale: 1-10): A subjective rating of the quality of sleep, ranging from 1 to 10. Physical Activity Level (minutes/day): The number of minutes the person engages in physical activity daily. Stress Level (scale: 1-10): A subjective rating of the stress level experienced by the person, ranging from 1 to 10. BMI Category: The BMI category of the person (e.g., Underweight, Normal, Overweight). Blood Pressure (systolic/diastolic): The blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure. Heart Rate (bpm): The resting heart rate of the person in beats per minute. Daily Steps: The number of steps the person takes per day. Sleep Disorder: The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).

### Details about Sleep Disorder Column:
None: The individual does not exhibit any specific sleep disorder.
Insomnia: The individual experiences difficulty falling asleep or staying asleep, leading to inadequate or poor-quality sleep.
Sleep Apnea: The individual suffers from pauses in breathing during sleep, resulting in disrupted sleep patterns and potential health risks.

## Conclusion
Now we can answer our questions and come to some conclusions:

### There are a relation in between gender or age with the amount of hours of sleep?;
Insomnia occurs equally in both males and females
Female is happen to be have more Sleep Apnea than Males l So we can realize that we have more woman over 45years then Males in the data base, and in the other hand we have more young Males than Females, which can indicate why we have a significant bigger number of Females with sleep apnea (It's a sleep disorder more linked with older ages) and more Males with none sleep disorder, since normally most sleep disorders begin in adulthood.

### There are a relation in between profession withthe types ofSslee Disordersp?
The top Insomnia professions are Salesperson, followed by Teacher, and Accountant.
Nurses are having Sleep Apnea the most than other occupations
Doctor, Engineer, Lawyer are having the best sleep in our list.
We can relate to the finds as some professions with more energy demanding being the ones with better sleep and since nurses are having more Sleep apnea is most likely that they are Females over 45yo. The "Insomnia professions" are likely to be stressfull professions as Salesperson.

### Can sleep quality be use as a health marker?
We can use the blood presure data to estimate a healthier person.
Normal BP is 120/80 - which conincides with None sleep disorder
Insomnia sleep disorder likely at 130/85 to 135/90 blood pressure
And lastly Sleep Apnea sleep disorder likely at 140/95 blood pressure, which in medicine would be studied and most likely medicated.
We can analyse having or not having Sleep Disorders as health marker, but when it comes to the Quality of Sleep is almost unintuitive that the people with higher BP are the ones having the best sleep, but we can infer that is because our body position alters our BP, getting lower.

### And if so, can we predict health by Sleep Disorders?
As we can use diferent health makers, some we already used here as BMI, BP and others as Risk of IAM, Mental Disorders or Metabolics Disorders to relate as Sleep Disorders or the lack of them ("None") can be impact in our quality of life.
