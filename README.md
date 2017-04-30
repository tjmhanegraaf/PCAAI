# PCAAI
AI to learn Python
Programming by deduction

---Design choices---
Python: TensorFlow/Available on Codecadamy

---Capabilities---
1. Learn Coding/Syntax
2. Solve Problems using code

---input---
Entities: 
- Language / Words
- Python
  - Keyword
  - Indentation (~10)
  - Data Structure
  - Literal
  - Operator
  - Function 
  ? Variable
  - Object
  ? Decorator
  ? Exception
  
  ---output---
  ?Language
  - Python source code
  - Result Python code


---Intermediary Evaluation---
- Chess solves this by rating pieces 
- DeepQ (atari) by score
- AlphaGo "Solved this" https://www.youtube.com/watch?v=b9H9AtbxpPM @ 29:00, tree search
  - Action Value: Monte Carlo Rollout + Value Network
  - Prior probability: Supervised Learning probability network
  - Visit Count
  -> Expansion
    - Prior Probability 
    - Select highest probability with 2 evaluations:
      - Monte Carlo rollout (Fast version) * 0.5
      - Value Network * 0.5


---AlphaGo---
Rollout Policy + SL Policy Network -> Classification of Human Expert Positions
-> Policy Gradient
RL Policy Network -> Play self 
-> Value Network (Regression)

---Sources---
https://medium.com/jim-fleming/running-tensorflow-on-kubernetes-ca00d0e67539
https://www.tensorflow.org/get_started/

