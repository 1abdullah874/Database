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

