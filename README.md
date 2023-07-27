

![](https://media2.giphy.com/media/eljCVpMrhepUSgZaVP/giphy.gif)

# Analysis of Epidemiological Models

This project aims to create a simulator that recreates the events of an epidemic in a close-knit community of 1000 people. Utilizing epidemic models, specifically the SEIR model, we simulate the progression of a virus within the community, observing its spread, recovery rates, and eventual decline.

## Project Overview
A few members of our hypothetical community have contracted a virus. We explore how this virus spreads, how long it takes for individuals to recover, and the duration until the virus ultimately dies down.

Our approach involves using the SEIR model, an extension of the commonly used SIR model. In this model, a population is divided into four compartments: Susceptible, Exposed, Infectious, and Removed. Over time, individuals transition between these compartments, representing the course of the epidemic.

Our model includes the concept of "exposure" to the virus, meaning individuals can be exposed without being infectious. We consider alpha as the exposure rate and beta as the infection transmission rate. We also make the assumption that once a person is infected, they remain so for 5 days, after which they gain permanent immunity.

