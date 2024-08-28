# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:
A customer is planning to buy a product online. They have three websites to choose from: Option A, Option B, and Option C. The customer wants to select the best website based on their preferences and the associated rewards.

### Problem Description
choosing the best website to buy

### State Space

```
State 0: Website A
State 1: Website B
State 2: Website C
```

### Sample State
A sample state could be the customer currently considering website B.

### Sample Action
A sample action could be the customer deciding to switch from Website A to Website B.

### Action Space 
```
Action 0: Stay with the current option
Action 1: Switch to the next option
```

### Reward Function
The customer receives a reward of 0 for staying with the current option.
If the customer switches to the last option (Website C), they receive a reward of 1.
There are no intermediate rewards for other actions or states.

## Graphical Representation:
![WhatsApp Image 2024-08-28 at 09 21 21_d9219a4a](https://github.com/user-attachments/assets/30b9ac99-baf2-4798-9693-ed0c9231d97c)


## PYTHON REPRESENTATION:
```
Developed By:
Name : Bala murugan P
Reg No : 212222230017


## PYTHON REPRESENTATION:
```py
P = {
    0:{
        0: [(1.0, 0, 0.0, True)],  
        1: [(1.0, 1, 0.0, True)]   
    },
    1:{
        0: [(1.0, 1, 0.0, True)],  
        1: [(1.0, 2, 1.0, True)]   
    },
    2:{
        0: [(1.0, 2, 0.0, True)],  
        1: [(1.0, 2, 0.0, True)]   
    }
}
```
## OUTPUT:

![Screenshot 2024-08-28 092505](https://github.com/user-attachments/assets/e05540f6-8871-4eda-bb5a-121fecdae75e)


![Screenshot 2024-08-28 092536](https://github.com/user-attachments/assets/9d2ec514-1b5f-49cf-83df-89d2a571ae50)


## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

