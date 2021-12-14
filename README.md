# Part 1 A

<img width="886" alt="Screen Shot 2021-12-13 at 10 34 07 PM" src="https://user-images.githubusercontent.com/87039833/146070412-2c631340-a9a5-4fbc-bed8-466e38316b36.png">

## 2. Count the transactions that are less than $2.00 per cardholder.
SELECT count(amount)
FROM transaction
WHERE amount < 2; 

The total is 350 transactions less than $2.00


## 3. Is there any evidence to suggest that a credit card has been hacked? Explain your rationale.
Yes, because according to the argument above transactions less than $2 indicate hacking. 

# PART 1 B 

## 1. What are the top 100 highest transactions made between 7:00 am and 9:00 am?

## 2. Do you see any anomalous transactions that could be fraudulent?

## 3. Is there a higher number of fraudulent transactions made during this time frame versus the rest of the day?

## 4. If you answered yes to the previous question, explain why you think there might be fraudulent transactions during this time frame.

## 5. What are the top 5 merchants prone to being hacked using small transactions?
If you’re a bar, food truck, or restaurant you are prone to being hacked 

