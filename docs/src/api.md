# Solver Documentation

Documentation for the `POMDPs.jl` user interface. You can get help for any type or 
function in the module by typing `?` in the Julia REPL followed by the name of 
type or function. For example:

```julia
julia>using POMDPs
julia>?
help?>reward
search: reward

  reward{S,A,O}(pomdp::POMDP{S,A,O}, state::S, action::A, statep::S)

  Returns the immediate reward for the s-a-s triple

  reward{S,A,O}(pomdp::POMDP{S,A,O}, state::S, action::A)

  Returns the immediate reward for the s-a pair

```

    {meta}
    CurrentModule = POMDPs

## Contents
    
    {contents}
    Pages = ["api.md"]

## Index

    {index}
    Pages = ["api.md"]


## Types

    {docs}
    POMDP
    MDP
    AbstractSpace
    AbstractDistribution
    Solver
    Policy
    Belief
    BeliefUpdater

## Model Functions

    {docs}
    states
    actions
    observations
    reward
    transition
    observation
    isterminal
    isterminal_obs
    n_states
    n_actions
    n_observations
    state_index
    action_index
    obs_index
    discount

## Distribution/Space Functions

    {docs}
    rand
    pdf
    dimensions
    iterator
    create_transition_distribution
    create_observation_distribution

## Belief Functions

    {docs}
    initial_belief
    create_belief
    update
    convert_belief

## Policy and Solver Functions

    {docs}
    create_policy
    solve
    updater
    action
    value

## Simulator

    {docs}
    Simulator
    simulate

## Utility Tools

    {docs}
    add

## Constants
    
    {docs}
    REMOTE_URL
    SUPPORTED_SOLVERS