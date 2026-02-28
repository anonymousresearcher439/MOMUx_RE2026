# SAGAT Overview

We employed SAGAT probing technique to evaluate the objective Situational Awareness (SA) of participants during our MOMUx simulation study. 
The participants filled SAGAT questionnaires at four timepoints within the simulation, referred to as freezes. 
Each SAGAT freeze lasted for 3 min during which participants were prompted 10 questions. 
SAGAT questionnaires across freezes were not identical, however, some questions repeated between freezes. 
In total we had 17 unique questions with an equal distribution of SA level-specific questions (L1: 6, L2: 6, L3: 5).
The questions were multiple-option questions, rather than open-ended.

For analysis, we computed SA level-specific and overall SA scores for each participant, 
which we used as input to mixed-design ANOVAs and pairwise post-hoc analyses to identify statistically significant differences across roles and mission episodes. 
The raw computed data can be found [here](./sagat_scores.csv).

## SAGAT Questions

### L1: Perception (n=6)

- How many UAVs are currently in the air?
- What are the current locations of all UAVs in the air?
- Has there been an emergency alert displayed for any UAV?
- What is the current location and heading of UAV<sub>i</sub>?
- Which UAVs are currently hovering?
- Is UAV<sub>i</sub> currently descending, ascending, maintaining current altitude, or landed?

### L2: Comprehension (n=6)

- Which UAV in the air is farthest from the Takeoff Location?
- Which UAVs in the air are closest to each other?
- Which UAV in the air is closest to the ground?
- Where is UAV<sub>i</sub> relative to UAV<sub>j</sub>?
- Which UAV is moving the fastest?
- Is any UAV in the air close to an immediate obstacle?

### L3: Projection (n=5)

- Which UAVs in the air will be closest to each other next?
- How will the relative position of UAV<sub>i</sub> in relation to UAV<sub>j</sub> change next?
- How will the altitude of UAV<sub>i</sub> change next based on its current movement patters?
- Will any UAV collide with any obstacle based on its current path/status?
- Will any UAVs collide with each other based on their current movement patterns?
