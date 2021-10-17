# Medical-Insurance

## Analyzing the contributing factor that can lead a to person to pay a high insurance charge.


### the data record the person Age, Sex, BMI, Children, Smoker, Region, Charges.

#### Using csv I was able to store the data into a list, which I called medical_insurances
#### From there I separed the list by age group. By creating a for loop that trought the medical_insurances list add the coresponding list to the list bellow if met the requirement.
- age_group_18_to_25
- age_group_25_to_45 
- age_group_45_plus

##### I created a function call calculate_average that will loop to each each item on the and add all the insurance charges to a temporary variable and divide it by the lenght of the list.

##### I discorver that the older you are the higher your insurance bills will be, people in the group 18 to 25 pay an average of $9087.02, compares to 25yrs to 45yrs that pays $11983.05, and the people that's older than 45yrs pays a average of $17200.43 for insurance.

##### One can assume that as your age increases so does your insurance bills, which will be true. 

### Based on the data gathere what is the average price for medical insurance between male and female.

##### I separate the medical_insurances into two list female_group and a male_group.
###### I discover that on average a male will have a higher medical insurance price compare to a female.
- The average insurance cost for female is $12569.58
- The average insurance cost for male is $13956.75

### Let see if a with a high BMI value pays a high price for insurances. Body mass index (BMI) is a measure of body fat based on height and weight that applies to adult men and women.

##### Created three new list.
- underweight_group any list of a bmi value less than 18.5
- healthy_weight_group any list of a bmi value equal to 18.5 and less than 25
- overweight_group any list of a bmi value equal to 25.0 and less than 30
- obesity_group any list of a bmi value greater than 30

###### The average insurance cost for an underweight person is $8852.2
###### The average insurance cost for an healthy person is $4766.02
###### The average insurance cost for an overweight person is $10537.32
###### The average insurance cost for an obese person is $13348.24

#### On average a person with a higher BMI will always pays higher insurance price. 
#### From this data I discorver that there was only one person in the healthy list.
