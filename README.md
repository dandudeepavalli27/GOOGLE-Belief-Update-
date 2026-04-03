# GOOGLE-Belief-Update-
SESSION 19 – GOOGLE (Belief Update)
Aim
To compute the updated belief using probabilistic reasoning.
General Objective
To explore probabilistic reasoning in autonomous agents and understand how Bayesian updates refine knowledge using new observations.
Specific Objective
To compute updated belief using:
Updated Belief
=
Prior
×
Observation
Updated Belief=Prior×Observation
Given:
Prior = 0.7
Observation = 0.6
Dataset
Bayesian Networks Dataset
Source: Bayesian Network Repository
Procedure
Input prior belief
Input observation likelihood
Apply multiplication rule
Compute updated belief
Display result
Algorithm
Start
Input prior and observation
Multiply values
Display result
Stop
Code Logic
belief = prior * observation
Python Code
# SESSION 19 – Belief Update (Bayesian)

# Step 1: Input values
prior = 0.7
observation = 0.6

# Step 2: Compute updated belief
belief = prior * observation

# Step 3: Display result
print("Updated Belief =", belief)

print("\nProgram Executed Successfully")
Output
Updated Belief = 0.42

Program Executed Successfully
Result
The updated belief is:
0.42
Industry Application
Bayesian belief updates are used in:
AI decision making
Robotics localization
Recommendation systems
Probabilistic modeling
Companies like Google use this in:
Search algorithms
AI systems
Predictive analytics
Conclusion
Bayesian updating improves decision-making by refining beliefs based on new evidence, making it essential for intelligent autonomous systems.
