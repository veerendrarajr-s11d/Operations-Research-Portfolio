**Operations Research & Mathematical Optimization**

**Executive Summary**
  * This repository bridges abstract M.Sc. Mathematics and industrial programming. It contains a suite of mathematical optimization engines built in Python, designed to solve critical business bottlenecks in manufacturing, supply chain logistics, human resource allocation, and competitive corporate strategy.
  * Using linear algebra, convex geometry, and the scipy.optimize library, these models translate complex, multi-variable business constraints into mathematically guaranteed maximum profits and minimum costs.
    
**Tech Stack & Mathematical Core**
  * Language: Python

  * Libraries: scipy (HiGHS solver, Hungarian Algorithm), numpy, pandas

  * Core Mathematics: Linear Programming, Convex Sets, Duality Theory, Integer Programming (Branch & Bound), Minimax Theorem, Matrix/Tensor Flattening.

**Repository Structure**

01_Factory_Optimization.ipynb (Manufacturing & Production)

  * Linear Programming: Maximized textile factory profits by optimizing the production volumes of Suiting, Shirting, and Woolen subject to strict machine-hour constraints.
  * Sensitivity Analysis (Duality): Extracted Shadow Prices to calculate the exact marginal monetary value of acquiring additional constrained resources.
  * Integer Programming: Enforced discrete mathematical boundaries (integrality) to solve an aerospace manufacturing bottleneck, ensuring decision variables remained physical whole numbers (e.g., preventing the allocation of fractional airplanes).
    
02_Supply_Chain_and_HR.ipynb (Logistics & Resource Allocation)

  * The Transportation Problem: Flattened a 3x4 geographical supply chain into a 12-variable equality matrix (A_eq) to route agricultural goods across India at the absolute mathematical minimum freight cost.
  * The Assignment Problem: Deployed the Hungarian Algorithm (linear_sum_assignment) to match distinct software engineers to specialized tasks, minimizing total project completion time using binary (1-to-1) assignment logic.

03_Competitive_Strategy.ipynb (Game Theory)

  * Minimax & Mixed Strategies: Built a probabilistic model simulating a corporate pricing war (Swiggy vs. Zomato). Maximized the "Value of the Game" (V) subject to absolute probability constraints (p_1 + p_2 = 1) to generate an unpredictable, mixed-percentage strategy that mathematically guarantees a baseline market share regardless of competitor actions.
