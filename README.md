
# opportunity analysis



## Problem Statement

This project helps stakeholders opportunity analysis.
Therefore, the project aims to identify the Sectors and products with the most sales potential. It also reflects the team’s success rate in converting opportunities and pinpoints the clients with the highest opportunity volume. Additionally, a monthly performance analysis is provided, including comparisons between managers and customer segmentation based on market and industry




### Steps followed 

- Step 1 : Load data into Excel From dataset is CSV file.

![Image](https://github.com/user-attachments/assets/89ef98fb-2299-4dc5-aeed-9c65f15d1c99)

- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

![Image](https://github.com/user-attachments/assets/aa65d263-a94d-4b8f-8c8a-4d87ed53c818)

- Step 3 : Also Check Data Valid by use Captlize Each Word & Trim, detect Data type".

![Image](https://github.com/user-attachments/assets/02de6a41-0d75-497e-bb4b-6eb42ab69bf0)

- Step 4 :  Data Cleaning & Data Handling 
Since some accounts represented potential clients who had not yet become confirmed customers, they were not registered in the database and appeared as blanks. Therefore, we replaced the blank values with Lead

![Image](https://github.com/user-attachments/assets/39447387-b81a-43c2-8daa-b45bb069a771)


- Step 5 :  Merge Queries to denormalize Data.

![Image](https://github.com/user-attachments/assets/5189e24d-402f-4215-8f6c-56003ce8c2c6)





- Step 6 : load Data to Data model & make Caluclation by DAX .

![Image](https://github.com/user-attachments/assets/3fe7f681-6a2d-46ef-89e6-9ca8c80f9c51)


![Image](https://github.com/user-attachments/assets/717668cd-aab1-41c2-8c98-429f4862b0ba)



- step 7 : analysis By Pivot Table 

![Image](https://github.com/user-attachments/assets/4ca2544d-cfcb-4bb1-8292-97f6b8aa989b)



- Step 7 : Build opportunity analysis Dashboard 

Create Four Card (#opportunities,Win Rate,Close Value,Average Deal Size)
 insights

opportunities by sales agent
opportunities by accounts
opportunities by months
opportunities by product

 Visual filters (Slicers) were added for Three fields named "Sector","Manger" ,"Stage".


![Image](https://github.com/user-attachments/assets/e96f2b42-7ed5-4922-a760-033f19d79d73)
