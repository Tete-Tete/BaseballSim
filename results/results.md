# Results

The MLB simulation project successfully implemented and executed three levels of Monte Carlo-based models comparing the Chicago Cubs and the Chicago White Sox. Each model incrementally increased in realism and complexity, simulating 9-inning games using real-world batting and pitching data. Below is a summary of the simulation outcomes.

## Level 1: Team-Level Batting Average Model

This simple model simulated scoring based on overall team batting average without individual player breakdown. The average batting averages were:

- **Cubs**: 0.254  
- **White Sox**: 0.217

**Sample Output:** 
Cubs Score: 5
White Sox Score: 4


**Observation:**  
As expected, the Cubs consistently outperformed the White Sox due to a higher team batting average.

---

## Level 2: Player-Level Batting Average with Rotation

This model introduced batting lineups, simulating at-bats based on each player's average and preserving order through innings.

**Sample Output:**
Cubs Score: 10
White Sox Score: 11


**Observation:**  
Despite the Cubs having a slightly stronger lineup, randomness in simulation occasionally led to White Sox outperforming. The added complexity yielded more varied results and reflected realistic lineup dynamics.

---

## Level 3: Pitcher-Adjusted Batting + Hit-Type Simulation

This most advanced model factored in opposing pitcher ERA to adjust batting averages and introduced hit types (singles, doubles, home runs).

Pitchers used:
- Cubs: ERA = 4.23
- White Sox: ERA = 3.93

**Sample Output:**
Cubs Score: 1
White Sox Score: 1


**Observation:**  
This model produced lower and more balanced scores, indicating the impact of pitcher quality and hit-type probability. Adjusting batting average based on league ERA created more nuanced and statistically grounded outcomes.

---

## Comparative Summary

| Model Level | Cubs Avg Score | White Sox Avg Score | Realism Level |
|-------------|----------------|---------------------|----------------|
| Level 1     | Higher          | Lower               | Basic          |
| Level 2     | Varied          | Varied              | Moderate       |
| Level 3     | Balanced        | Balanced            | High           |

---

## Conclusion

The simulations demonstrated how increasing model complexity improves realism and variability. Level 1 served as a baseline, Level 2 added lineup dynamics, and Level 3 realistically modeled pitcher-batter interactions and hit outcomes. While Cubs generally had a statistical edge, outcomes varied in higher-level models, emphasizing the importance of simulation fidelity in sports analytics.

All outputs were saved under the `results/` directory and support reproducibility with a fixed seed. Further iterations could explore multi-game averages, score distributions, and visualization charts as planned in the roadmap.




