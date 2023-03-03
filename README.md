# Shiran Yuan's STATS 201 Repository
This is Shiran Yuan's repository for the course STATS 201.

## Table of Contents
* [Bio](#bio)
* [Project Information](#project-information)
* [Data](#data)
* [Code](#code)
* [Spotlights](#spotlights)

## Bio
![Shiran](https://user-images.githubusercontent.com/105504535/213655331-9881b742-241d-48af-b3c3-27fdb4d8092d.jpeg)

Shiran Yuan was born on September 2007. He dropped out of primary school during second grade in 2016 (age 8) after receiving a scholarship, and began self-studying since then. 

In 2017 (age 9) he received IELTS band 7. 

In 2018 (age 10), he completed the Shing-Tung Yau Mathcamp course at Tsinghua University, received Honor Roll of Distinction in the Second Round of the Mathematics League Competition (Grades 9-12 Track), earned High Honors in the Johns Hopkins Center for Talented Youth's Talent Search Program, received a TOEFL score of 109, and was awarded the AP Scholar with Honor Award from the CollegeBoard. 

In 2019 (age 11), he received the AP Scholar with Distinction Award from the CollegeBoard and a DELF B2 (French language) certificate.

In 2020 (age 12), he completed the Hsue-Shen Tsien Excellence in Engineering Program Summer Camp course at Tsinghua University.

In 2021 (age 13), he was admitted to DKU with a full scholarship, and received the top prize at X-Institute (an academic research institution founded by Tsinghua University) Summer Camp.

In 2022 (age 14), he became an X-Institute Scholar, and received the Silver Medal in the iGEM Competition.

His current intended major is Applied Mathematics and Computational Sciences (Computer Science Track).

## Project Information

![STATS 201 Final Poster - Shiran](https://user-images.githubusercontent.com/105504535/221129801-41736a63-c0a0-446c-99de-b42e89d63a0f.png)

## Data

Data Source: `snscrape.modules.twitter`
* `Explanation_Data.txt`: Contains the raw content of all queried tweets.
* `PS2_Data.txt`: Contains the number of queried tweets for each day from Jan 1st 2013 to Dec 31st 2022. Days without queried tweets are not shown.

## Code

Modelling Tool: `scikit-learn`
* `PS2_Query_Data.ipynb`: Queries tweets and records their dates. Produces the data file `PS2_Data.txt`.
* `PS2_Process_Data.ipynb`: Processes and visualizes `PS2_Data.txt`. 
* `Final_Analyze_Data.ipynb`: This is the new part in this project: to analyze `PS2_Data.txt`. Produces the figure `causal_inference_spotlight.png`.

## Spotlights

`causal_inference_spotlight.png`: The results of the causal inference.

![image](https://user-images.githubusercontent.com/105504535/222707098-55688675-cd7b-478e-9e90-76a77d11d509.png)
