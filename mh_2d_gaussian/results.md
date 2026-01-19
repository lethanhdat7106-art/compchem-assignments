# (1.6) Metropolis–Hastings: 2D Gaussian
## Target distribution
* For the first graph:
- Mean: (0, 0)
- Covariance: 
  [[1.0, 0.0]
  [0.0, 1.0]]
* For the second graph:
- Mean: (0,0)
- Covariance: 
  [[0.8,0.4]
  [0.6,1.0]]
## Simulation setup
- Number of steps: 500000
- Burn-in: 2000
- Proposal step size: 0.5
## Results:
* For the first graph:
- Acceptance rate of graph 1: 0.7579701195219124
- Sample mean of graph 1: [ 0.01043034 -0.01305972]
- Sample covariance of graph 1:
 [[0.99860222 0.00787115]
 [0.00787115 0.98607737]]
* For the second graph:
- Acceptance rate of graph 2: 0.7059581673306773
- Sample mean of graph 2: [-0.00143485 -0.01195481]
- Sample covariance of graph 2:
 [[0.81911955 0.51937503]
 [0.51937503 1.0196123 ]]

