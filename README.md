---
title: "⚙️ Student Performance GCE AL Exam 2020 "
date: 2022-10-05T14:08:51+05:30
draft: false
tags : ['Python','Data-engineering','AWS VM']
description : "This is far more the biggest and most favorite project of mine. Go through the project details.You might find this interesting. "
---


## 🌐 [Kaggle Link](https://www.kaggle.com/datasets/sasikaamarasinghe/student-performance-gce-al-exam-2020-sri-lanka)

### DOI - 10.34740/kaggle/ds/2302701

This is by far my biggest and most favorite project. Take a look at the project details; you might find it interesting.

This dataset contains information on the performance of students in the GCE Advanced Level (AL) exam in Sri Lanka in 2020. It was collected by [Sasika Amarasinghe](https://www.kaggle.com/sasikaamarasinghe) and is available on [Kaggle](https://www.kaggle.com/datasets/sasikaamarasinghe/student-performance-gce-al-exam-2020-sri-lanka).

---
>I removed some columns from the original dataset for ethical reasons. However, I can provide a sample of the data when a search query is entered.

<!-- {{<video src="https://sasikaa073-projects.netlify.app/videos/search.mkv" controls="yes">}} -->
<video src="https://sasikaa073-projects.netlify.app/videos/search.mkv" controls="yes" width="800" height="600">
  Your browser does not support the video tag.
</video>


When a school candidate's name is provided, the system retrieves comprehensive details, including their birthdate, which is not originally disclosed on the exam result sheet. (Applicable to candidates from the 2020 AL batch 😄)



---
## Dataset Characteristics
- The dataset consists of over 300,000 records of student performance in the GCE AL exam in Sri Lanka.
- The data includes information on student identification, school, district, medium of instruction, stream, and their scores in different subjects.
- The data also includes the overall Z-score of each student, which is a standard score that indicates the number of standard deviations by which the student's exam results are above or below the mean.

## Variables
- `Index`: A unique identifier for each student
- `School ID`: Identification number of the school
- `District`: District where the school is located
- `Stream`: Science, Arts, or Commerce stream of the student
- `Medium`: Sinhala or English medium of instruction
- `Subjects`: The scores of the student in each of the subjects - Mathematics, Science, English, Buddhism, and History
- `Z-Score`: The overall Z-score of the student

## Use Cases
- This dataset can be used to study the performance of students in different subjects and in different streams, medium of instruction, and districts.
- The data can also be used to study the relationship between student performance and demographic factors such as medium of instruction and district.
- This dataset can be used to identify the factors that contribute to the performance of students in the GCE AL exam and to make recommendations for improving student performance in the future.

## Usability
- 9.41 / 10

## Sources

- Data was collected from (https://www.doenets.lk/examresults) which is the exam result site in Sri Lanka

## Collection Methodology

- The data was scraped using a Python script written by the author, using the index number as the primary key.
- Subsequently, the national identity card numbers were decoded to extract applicants' birthdays and genders.
- Due to privacy concerns, "Full name," "National Identity Card number," and "Index number" were removed, but the birthdays and genders were added to the dataset.
- AWS EC2 instances were employed to collect data concurrently, reducing both the time and data usage.

I was awarded a bronze 🥉 medal for this dataset, receiving 38 upvotes in the Kaggle Community, along with very positive feedback from the community members.

## Testimonials for the dataset

> ⭐ This can be actually used to look after the academic likelihoods and whereabouts of Sri Lankan students' academics! Great job! -- [VISHESH THAKUR - Datasets Expert](https://www.kaggle.com/vishesh1412)

> ⭐ This data could be used for EDA, visualization and even model development! Good work and great dataset! -- [RAVI RAMAKRISHNAN-Notebooks Grandmaster](https://www.kaggle.com/ravi20076)


