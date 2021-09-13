# Part 1 A
## 1. How can you isolate (or group) the transactions of each cardholder?
SELECT column1, column2, ...
FROM table_name
WHERE condition;


SELECT column_name(s)
FROM table_name
WHERE condition
GROUP BY column_name(s)
ORDER BY column_name(s);


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

