# MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1.Text representation

2.Graphical representation

3.Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
To Develop an environment contain some dirt and the agent is going to detect and clean the environment using vaccum. The aim is to clean the dirty place.

### State Space

{Location A,Location B,Location C}


### Sample State
Location A

### Sample Action
Moving Right

### Action Space 
```
1.Moving Right

2.Moving Left

3.Suck Dirt
```

### Reward Function
1.+1 - when an agent move to the right side and the dirt is cleaned using vaccum

2.0 - Otherwise

## Graphical Representation:

![305734451-c9c5fc75-92d5-4db0-a372-212edbb438c1](https://github.com/user-attachments/assets/276d9565-f3d1-4e91-b79b-9d806b607891)


## PYTHON REPRESENTATION:
```
# Developed by: Bala murugan
# Register Number: 212222230017

P = {
    0:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,0,0.0,True)]
    },
    1:{
        0: [(1.0,0,0.0,True)],
        1: [(1.0,2,1.0,True)]
    },
    2:{
        0: [(1.0,2,0.0,True)],
        1: [(1.0,2,0.0,True)]
    }
}

```
## OUTPUT:


![305734147-6eba07da-65b4-497d-92fd-426e48a17985](https://github.com/user-attachments/assets/150166d4-abda-4109-b397-026f3e0f52d6)


## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

