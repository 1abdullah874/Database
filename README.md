# Database
#exercise 2 Single table queries 

Q1. 
SELECT * FROM goal

<img width="885" alt="Q1" src="https://github.com/user-attachments/assets/c738de1e-ab33-4cca-b1b8-1ac5fdd071f1">

Q2.
SELECT name FROM airport WHERE iso_country = "FI";

<img width="548" alt="Q2" src="https://github.com/user-attachments/assets/cfb10c07-b1a7-4907-92e3-063012dbdb58">

Q3.
SELECT name FROM airport WHERE iso_country = "FI" order by name;

<img width="620" alt="Q3" src="https://github.com/user-attachments/assets/12fcc9cb-47ef-4048-b9f1-73d2bacc33ac">

Q4.
select name, type from airport where iso_country = "FI" order by name, type;

<img width="730" alt="Q4" src="https://github.com/user-attachments/assets/f8b61fac-6b92-4dac-ac23-0e613b3006a4">

Q5.
select name from country where name like "%F%";

<img width="517" alt="Q5" src="https://github.com/user-attachments/assets/0f52a854-7b9c-491c-aec9-83bd4b5a6abd">

Q6.
select name from country where name like "%f%";

<img width="513" alt="Q6" src="https://github.com/user-attachments/assets/1234b154-2d83-4ce0-aae5-d095d915b174">

Q7.
select location from game where screen_name = "vesa";

<img width="560" alt="Q7" src="https://github.com/user-attachments/assets/1994b36f-7b5a-4880-9b26-94933d9a5b8c">

Q8.
select co2_consumed from game where screen_name = "ilkka";

<img width="584" alt="Q8" src="https://github.com/user-attachments/assets/d428e088-97f2-4200-9769-473a9ca7d779">

Q9.
select distinct co2_budget from game;

<img width="448" alt="Q9" src="https://github.com/user-attachments/assets/4be668a7-dd99-4920-bac8-7b31d623cd8f">

Q10.
select screen_name, co2_budget, co2_consumed, (co2_budget - co2_consumed) As co2_difference from game where screen_game = "ilkka";

<img width="807" alt="Q10" src="https://github.com/user-attachments/assets/7e585daf-39fe-4cde-9e6a-e6859e164568">



#Exercise 3

Q1

<img width="693" alt="Screenshot 2024-09-27 at 10 35 00 AM" src="https://github.com/user-attachments/assets/4865de31-316a-4415-9472-dd8e924485d5">

Q2

<img width="720" alt="Screenshot 2024-09-27 at 10 37 28 AM" src="https://github.com/user-attachments/assets/d2ad3bd8-360f-4420-aa27-28ecbb7cef21">

Q3

<img width="665" alt="Screenshot 2024-09-27 at 10 40 32 AM" src="https://github.com/user-attachments/assets/58eb40b1-b40a-4d26-aeed-62bfdc84ec83">

Q4

<img width="425" alt="Screenshot 2024-09-27 at 10 44 50 AM" src="https://github.com/user-attachments/assets/1c29932e-aa93-4a82-aea8-e7dce91edb50">


Q5

<img width="496" alt="Screenshot 2024-09-27 at 10 46 36 AM" src="https://github.com/user-attachments/assets/69786749-cb60-461d-bb7d-5e558dde1bd9">


Q6

<img width="471" alt="Screenshot 2024-09-27 at 10 48 10 AM" src="https://github.com/user-attachments/assets/0aa18347-f572-4036-a89d-b8327a529837">

Q7

<img width="726" alt="Screenshot 2024-09-27 at 10 50 58 AM" src="https://github.com/user-attachments/assets/190c3bd0-773a-4838-bb04-dd788d35725d">

Q8

<img width="504" alt="Screenshot 2024-09-27 at 10 52 31 AM" src="https://github.com/user-attachments/assets/e3e8a24a-3b04-4bca-8603-c6b5aa1a0211">

Q9


<img width="725" alt="Screenshot 2024-09-27 at 10 53 07 AM" src="https://github.com/user-attachments/assets/f29c3ddd-c46d-4e45-8ebd-b0b18e55f7ee">


Q10

<img width="721" alt="Screenshot 2024-09-27 at 10 54 01 AM" src="https://github.com/user-attachments/assets/b78bfe38-211e-4b2a-a6c2-6060469aef81">



#exercise 4 


Q1

<img width="694" alt="Screenshot 2024-09-27 at 2 27 34 PM" src="https://github.com/user-attachments/assets/ef847687-21a8-4b58-80b8-454e6ddf7162">

Q2

<img width="428" alt="Screenshot 2024-09-27 at 2 29 48 PM" src="https://github.com/user-attachments/assets/ecc53a7c-1721-4f64-a493-37031fc7581f">


Q3

<img width="725" alt="Screenshot 2024-09-27 at 2 32 01 PM" src="https://github.com/user-attachments/assets/09f1359d-d6bd-484b-8d30-d0d6cb516e26">

Q4

<img width="650" alt="Screenshot 2024-09-27 at 2 33 02 PM" src="https://github.com/user-attachments/assets/84a459b9-75a5-4c5f-9949-a5d76cf116c8">



Q5

<img width="702" alt="Screenshot 2024-09-27 at 2 33 46 PM" src="https://github.com/user-attachments/assets/49e2d55d-7c3b-41df-9b32-35d2277c859a">

#exercise 5

Q1

<img width="289" alt="Screenshot 2024-09-28 at 12 47 58 PM" src="https://github.com/user-attachments/assets/fd5f5398-48d3-464b-b57b-67c593412766">

Q2

<img width="776" alt="Screenshot 2024-09-28 at 12 50 04 PM" src="https://github.com/user-attachments/assets/f0d88103-1c29-4b08-81af-e17130f05c07">

Q3

<img width="328" alt="Screenshot 2024-09-28 at 12 51 00 PM" src="https://github.com/user-attachments/assets/a0393a0a-908c-4ddb-945e-f2b452eb8526">


Q4

<img width="331" alt="Screenshot 2024-09-28 at 12 51 33 PM" src="https://github.com/user-attachments/assets/be2d9ec6-2583-4910-8c35-0bc2a630008f">



Q5

<img width="557" alt="Screenshot 2024-09-28 at 12 52 05 PM" src="https://github.com/user-attachments/assets/aebbe57a-d2a5-4169-89ed-004890047700">


#exercise 6

Q1

<img width="444" alt="Screenshot 2024-09-28 at 1 00 17 PM" src="https://github.com/user-attachments/assets/5906b63e-3e1b-483d-b3a7-3d0f4747443a">


Q2




<img width="598" alt="Screenshot 2024-09-28 at 1 03 42 PM" src="https://github.com/user-attachments/assets/48c6aa1e-9f43-4c52-a606-704255f18507">



Q3

<img width="776" alt="Screenshot 2024-09-28 at 1 05 43 PM" src="https://github.com/user-attachments/assets/0ccf8ffa-eddf-455c-8f93-9c6738c396f2">





Q4


<img width="299" alt="Screenshot 2024-09-28 at 1 06 27 PM" src="https://github.com/user-attachments/assets/9da5c44d-af7c-4ea3-9f81-2aa37ad1232e">





Q5


<img width="776" alt="Screenshot 2024-09-28 at 1 09 59 PM" src="https://github.com/user-attachments/assets/5631e354-0b1d-44c4-9024-35f906270cb4">





Q6


<img width="774" alt="Screenshot 2024-09-28 at 1 12 07 PM" src="https://github.com/user-attachments/assets/102934a0-2dce-46aa-8e44-f43d61c3e2d5">





Q7



<img width="775" alt="Screenshot 2024-09-28 at 1 13 51 PM" src="https://github.com/user-attachments/assets/6814c672-cd24-447e-b69c-c2801f1b98d1">






Q8

<img width="266" alt="Screenshot 2024-09-28 at 1 16 01 PM" src="https://github.com/user-attachments/assets/733f9b06-6e83-4b1d-a89c-3b5eec4c647a">






Q9


<img width="766" alt="Screenshot 2024-09-28 at 1 18 00 PM" src="https://github.com/user-attachments/assets/eb2914bc-5871-45ef-ab43-0117780791e9">







Q10



<img width="259" alt="Screenshot 2024-09-28 at 1 36 25 PM" src="https://github.com/user-attachments/assets/96248d68-167b-45ea-a980-dc81d3a9ea2f">

#exercise 7

Q1

<img width="771" alt="Screenshot 2024-09-28 at 11 13 50 PM" src="https://github.com/user-attachments/assets/6f7c383d-c0c7-4d98-a034-af2fd7dd8f1b">





Q2


A. goal_reached




Q3

<img width="363" alt="Screenshot 2024-09-28 at 11 18 29 PM" src="https://github.com/user-attachments/assets/27a3601d-1594-44b4-88f4-eb0b40fd1f4a">




Q4

<img width="339" alt="Screenshot 2024-09-28 at 11 18 39 PM" src="https://github.com/user-attachments/assets/aa92dab6-895d-4d5f-8b9e-fee9cab7d701">

















