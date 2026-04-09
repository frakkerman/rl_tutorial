# A Tutorial on Reinforcement Learning for Maritime Logistics

This repository contains the code accompanying the paper *"A Tutorial on Reinforcement Learning for Maritime Logistics"*. It provides a complete, step-by-step implementation of the proposed framework, applied to a multi-modal container dispatching problem.

## Problem

A logistics service provider must decide each day how to dispatch containers across multiple destinations, choosing between a barge (fixed cost, higher capacity) and trucks (variable cost, unit capacity). Demand is stochastic and containers have release times and time windows. The goal is to minimize total dispatch costs over a finite horizon.

Run the full pipeline step by step via the notebooks.

## Framework Steps

| Step | Description |
|------|-------------|
| 1-2  | Problem formulation and MDP definition (see paper) |
| 3    | Simulation environment and baseline heuristic |
| 4    | Supervised ML on static data (value function approximation) |
| 5    | ML-guided one-step lookahead policy |
| 6    | REINFORCE and PPO agents |
| 7    | Hyperparameter tuning and ablation study |
| 8    | Policy analysis and visualization |

## Citation

If you use this code in your research, please cite:

```bibtex
@misc{akkerman_rl_tutorial,
    title={A Tutorial on Reinforcement Learning for Maritime Logistics},
    author={Fabian Akkerman and Eduardo Lalla-Ruiz and Martijn Mes},
    year={2026}}
```

## License

GNU GENERAL PUBLIC LICENSE version 3