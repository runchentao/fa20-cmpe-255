# Oct 27, 2020 Meeting

## Tasks
1. Data preprocessing
2. 5.1.1 & 5.2

## Timeline
- Nov 3, 2020 -> Data preprocessing
- Nov 15 -> 5.1.1 & 5.2
- **DDL: Nov 20, 2020**

---

- Use case example:
User A purchase football, but A never purchase football before. Which item to be purchased next?

- Step 1: user A belongs to which user group? 
- Step 2: which item that the user in this user group will purchase with football?
		  output -> null
		  frequent item set: {football, banana}
		  output -> banana

---

1. Separate all users into customer groups
    - KNN	    
	- K-means 
	- output -> (Group A, Group B)
2. Find out the frequent item set in each group
	- Apriori Algo.
	    - each user x in Group A/B, purchase history -> {i,j}
	    - output: 
            - Group A -> {football, banana}, ...
			- Group B -> {banana, milk}, ...
3. User A purchase football 
    - -> User A belongs to Group A
	- -> Group A 
	- -> {football, banana}
    - -> User A will most likely to buy banana next