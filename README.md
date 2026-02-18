-This program categorizes resource requests based on demand levels.

It first asks the user to enter the size of the list (number of requests).

A fixed name "siddardha reddy" is used to calculate the PLI value.

The program counts the number of characters in the name excluding spaces.

The length of the name is stored in variable l.

PLI (Pr=ersonalised rule ) is calculated as l % 3.

The program prints the length of the name and the PLI value.

Empty lists are created for low, moderate, high, invalid, and no demand requests.

A list named resources is created to store user inputs.

The user enters each request value one by one.

If a request is less than 0, it is marked as invalid.

If a request is equal to 0, it is categorized as no demand.

If a request is between 1 and 20, it is categorized as low demand.

If a request is between 21 and 50, it is categorized as moderate demand.

If a request is greater than 50, it is categorized as high demand.

The program calculates total valid requests (low + moderate + high).

Based on the PLI value, some categories are removed.

If PLI is 0, all low demand requests are removed.

If PLI is 1, all high demand requests are removed.

If PLI is 2, both low and high demand requests are removed.

The removed request count is stored in removed_due_to_PLI.

The program prints the list of invalid requests.

It prints the final low, moderate, and high demand lists.

It displays the total number of valid requests.

Finally, it shows how many requests were removed due to PLI


<img width="674" height="872" alt="image" src="https://github.com/user-attachments/assets/6778238b-65b7-4dd0-a69d-e8fc9dcc9f7f" />

