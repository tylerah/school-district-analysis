# Analysis of School District Test Scores Using Python, Pandas, and Jupyter Notebook
## Overview of Analysis
The purpose of this project was to replace innacurate data that was determined to exist for the 9th grade students at Thomas High School following the discovery of academic dishonestry. The district wanted this data to be corrected and to perform the school district analysis again to verify what impact the erroneous data might have had the initial results. Subsequent to replacing the innacurate data, DataFrame containing the following metrics were generated: 
* district summary
* school summary
* top 5 performing schools
* bottom 5 performing schools
* average reading scores
* average math scores
* scores by school spending per student
* scores by school size
* scores by school type

## Results
### School District Summary
The school district summary was not affected very much. The average scores remain roughly the same. 

Original:

![summary](https://user-images.githubusercontent.com/104606662/191144585-111986d0-ad15-418d-ad8d-23e3ca277ae8.png)

Corrected:

![summary_corrected](https://user-images.githubusercontent.com/104606662/191144592-c8601e30-e757-4feb-9137-af75d164af5b.png)

### School Summary
The school summary is largely unchanged. This is to be expected because only data from Thomas High was compromised. However, even the scores at Thomas High that were directly impacted were still very comparable having changed less than a single percent.

Original:

![Screen Shot 2022-09-19 at 7 21 02 PM](https://user-images.githubusercontent.com/104606662/191146688-d84c9caa-db90-4962-ac61-c8abe437e10a.png)

Corrected:

![Screen Shot 2022-09-19 at 7 24 57 PM](https://user-images.githubusercontent.com/104606662/191147021-b1947085-46d0-4cb1-b100-5598ed90b19e.png)

### Thomas High School's Performance Relative to Other Schools
Given that the overall percentages did not change much, as seen in the previous summary DataFrames, Thomas High School's overall performance relative to other schools did not change either. Thomas High remains second in the district. 

Original:

![Screen Shot 2022-09-19 at 7 34 49 PM](https://user-images.githubusercontent.com/104606662/191148112-e1d33a42-60ec-4e75-922d-d129e25ff72d.png)

Corrected:

![Screen Shot 2022-09-19 at 7 34 58 PM](https://user-images.githubusercontent.com/104606662/191148124-72387132-38c6-4876-bf38-564e77ff5a9f.png)

### Scores by Budget, School Size, and School Type
As consistent with the other DataFrames, there was no noticeable change in any of these DataFrames. The impact of correcting the erroneous data for Thomas High had a negligible impact. 

Scores by budget
Original:

![Screen Shot 2022-09-19 at 7 45 58 PM](https://user-images.githubusercontent.com/104606662/191149257-75b62dc1-aec3-466b-92d9-857cc39d6eec.png)

Corrected:

![Screen Shot 2022-09-19 at 7 46 08 PM](https://user-images.githubusercontent.com/104606662/191149246-e739a1a4-1f41-48bc-b2d3-f7b18db5d831.png)


Scores by school size
Original:

![Screen Shot 2022-09-19 at 7 45 20 PM](https://user-images.githubusercontent.com/104606662/191149151-69054dd6-e822-43b1-b783-bce5d941a3fb.png)

Corrected:

![Screen Shot 2022-09-19 at 7 45 29 PM](https://user-images.githubusercontent.com/104606662/191149154-94401acd-45bd-4d12-9c29-be8e1f919137.png)


Scores by school type
Original:

![Screen Shot 2022-09-19 at 7 43 52 PM](https://user-images.githubusercontent.com/104606662/191148990-0471ed6d-be62-45a8-aabf-efdca7a7fc43.png)

Corrected:

![Screen Shot 2022-09-19 at 7 44 01 PM](https://user-images.githubusercontent.com/104606662/191148980-df56f0db-81f0-47da-9ec3-0e535a562dc1.png)

