# Experiment: Multi-step Reasoning Sensitivity

## Prompt
A train travels 60 km in 1 hour and then 120 km in 2 hours. What is the average speed?

## AI Response
The average speed is 90 km/h because (60 + 120) / 2 = 90.

## Prompt Intent
To test whether the model correctly applies multi-step reasoning instead of relying on shortcuts.

## Observations
- Uses an incorrect method for calculating average speed  
- Divides by number of segments instead of total time  
- The answer appears reasonable but is logically incorrect  

## Issue
- Relies on pattern-based calculation  
- Fails to apply proper reasoning  

## Insight
- The model tends to default to familiar patterns in multi-step problems, even when they lead to incorrect conclusions.

- Errors like this can affect real-world use cases such as financial calculations, planning, or decision-making where small mistakes can lead to incorrect outcomes.
