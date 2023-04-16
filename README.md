# Myntra-Fashion-Product-Analysis

When it comes to shopping it goes without saying that girls are the best shoppers. Is it true or not ? I tried to find out the answer of this question through this project. 

In this Project I have taken dataset of Myntra Fashion Product Analysis.

I have First cleaned the data and then analysed the data using python libraries(numpy and pandas). After the analysis I did data visualisation using python libraries matplotlib and seaborn. And at last I have Created a Dashboard using PowerBI

## Importing libraries

<img width="447" alt="Screenshot 2023-04-12 154853" src="https://user-images.githubusercontent.com/129768950/232340268-b613c56c-663f-4f1c-a671-2fdd2eadb00a.png">

## Importing Dataset

<img width="352" alt="Screenshot 2023-04-12 154959" src="https://user-images.githubusercontent.com/129768950/232341375-72c4907b-e1cc-43d5-99f2-bd2e53af1573.png">

##  Dataset

<img width="399" alt="Screenshot 2023-04-12 155014" src="https://user-images.githubusercontent.com/129768950/232342186-1fdd65d7-683d-4181-9493-d919f188df0f.png">

<img width="337" alt="Screenshot 2023-04-12 155034" src="https://user-images.githubusercontent.com/129768950/232342269-8862290e-36b0-433c-b912-ac2c87b67f50.png">

## Null value present in our dataset

<img width="264" alt="Screenshot 2023-04-12 155048" src="https://user-images.githubusercontent.com/129768950/232342351-07d980d0-f4bc-4bfe-b0c6-e7c126c5712c.png">

<img width="267" alt="Screenshot 2023-04-12 155101" src="https://user-images.githubusercontent.com/129768950/232342366-6d01d125-df21-4a40-b352-d97d1ddf91ec.png">

PrimaryColor is the only column with null values. We can fill these null values with 'others'

df['PrimaryColor'] = df['PrimaryColor'].fillna('Other')

## Various brands available

<img width="381" alt="Screenshot 2023-04-12 155356" src="https://user-images.githubusercontent.com/129768950/232343765-8ada66b5-6db3-48b5-9547-fcc8220aa5bd.png">

<img width="496" alt="Screenshot 2023-04-12 155420" src="https://user-images.githubusercontent.com/129768950/232343771-95b5ded6-3f46-4a73-bac2-15368ae27b97.png">


## Price range available on myntra

<img width="291" alt="Screenshot 2023-04-12 155614" src="https://user-images.githubusercontent.com/129768950/232342517-2ea7e475-50c6-4f73-8aa7-a725d3718a2a.png">
<img width="282" alt="Screenshot 2023-04-12 155631" src="https://user-images.githubusercontent.com/129768950/232342534-11e13d83-0772-4a85-b49e-a4bcf7851496.png">
<img width="301" alt="Screenshot 2023-04-12 155653" src="https://user-images.githubusercontent.com/129768950/232342562-89178645-5a89-417c-bb99-b90c8ab96313.png">

##### Max Price :  63090, 
##### Min Price :  90, 
##### Mean Price :  1452.6609558882396

## Data Visualisation

#### Top 10 brands
<img width="618" alt="Screenshot 2023-04-12 155721" src="https://user-images.githubusercontent.com/129768950/232343246-a4a668f5-a453-4584-a317-1c99b4b85a61.png">

<img width="438" alt="Screenshot 2023-04-12 155736" src="https://user-images.githubusercontent.com/129768950/232343155-42743311-ac91-415a-a958-eba9c7b72dc9.png">

#### Top 10 Expensive Brand

<img width="571" alt="Screenshot 2023-04-12 160409" src="https://user-images.githubusercontent.com/129768950/232343557-e84541dc-be40-4ad5-8e7b-ea4b1483eca7.png">

<img width="431" alt="Screenshot 2023-04-12 160433" src="https://user-images.githubusercontent.com/129768950/232343564-cf02551b-7aa6-4bfd-9d00-ae036727d499.png">

 ## Dashboard using PowerBI
 
 <img width="604" alt="Screenshot 2023-04-12 154712" src="https://user-images.githubusercontent.com/129768950/232343659-56e1bc19-6ad7-4d39-9881-8f113b09104d.png">

