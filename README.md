# SQL_Murder_Mystery

### The Case
A crime has taken place and the detective needs our help. The detective has given the crime scene report, but it’s now lost.
We have information that the crime occurred sometime on Jan.15, 2018, and took place in SQL City. 

Here is the schema diagram to show us the available tables and their relationships within the database:
<img width="828" alt="SCHEMA" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/ce59ace6-5110-4794-a6e7-97baa66c17e3">

To get an overview of the crime scene report, I filtered the data based on the information given before, crime type, city, and date.

<img width="761" alt="Crime scene" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/a8a50cf2-a037-4e68-b6ce-aeb5bae9f94f">

There are 2 witnesses, to get the 1st witness I narrowed down houses at "Northwestern Dr" to get the last house number by searching the street name and using the DESC to get the highest number:

<img width="683" alt="1 witness" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/44fa98fe-cb33-4dac-9e8c-70118919af8f">

For the 2nd witness, Annabel, I ran this query to get Annabel's details from the "person" table:

<img width="635" alt="2ND witness" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/663dd231-8d23-442f-a0e9-e2191c3605a7">

Now that we have narrowed down information about the 2 witnesses, it is time to explore more about them by looking into the "interview" table searching by their ID:

<img width="675" alt="Witnesses interview" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/26014684-148f-4ad1-a2f0-5d11a439537c">

Based on the output, I know that the murderer is a Get Fit Now Gym gold member with a membership starting with "48Z" and with a car plate that includes "H42W", I used INNER JOIN to join between 3 tables to find the killer

<img width="722" alt="suspect" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/26d0e1bf-c5b8-429a-82b7-e0a8f8eeb70a">

And we found the killer it's...
*Jeremy Bowers!*
 I had to check the answer by inserting the killer name in the query below:
 <img width="697" alt="kill" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/3f2cb0ac-339f-4477-9447-9ad735c0c31a">

Based on the information provided by the killer, I need to narrow down the result to find who is behind this murder.
Jeremy said that she is a woman with a height between 65" to 67", red hair, driving a Tesla Model S, and attended SQL Symphony Concert 3 times in December 2017. This query is a bit complicated to be able to get the correct answer in one query.

<img width="723" alt="real murder" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/369eb290-c328-480e-b316-06ce58fa184e">

Let's check the result.

<img width="656" alt="result" src="https://github.com/Skyshalini/SQL_Murder_Mystery/assets/98145111/b24205e0-98f8-4ec2-b351-6f6263ca4fd3">

Here we go!
*Miranda Priestly* was behind that crime and She hired *Jeremy*.

### THE EXPERIENCE
I was thrilled by how helpful I found this challenge to be. I was able to practice some SQL queries, and after solving the crime I can say that it has become more intuitive to implement different statements and filtering criteria to retrieve the information needed from a database.
The experience set me up to keep learning about the different applications SQL has to offer in my journey as a data analyst.

