## about this project
We want to study air-sea fluxes by modelling the marine atmospheric boundary layer (MABL) using [Oceananigans](https://clima.github.io/OceananigansDocumentation/stable/). This is a 21st Century Weather + Greg + Callum project.  

## science goals
Our short/medium term goal is to understand the aggregate effect of submesoscale ocean features on atmospheric boundary layer structure and air-sea fluxes. We are working towards air-sea flux parameterisations that are robust to changes in model resolution. 

## approach
Idealised model of the MABL with prescribed SST (& u, v?) variability at submeso-scales $\mathcal{O}$(0.1-1km), focusing on (convectively) unstable conditions.
- domain $\mathcal{O}(10\mathrm{km})$ long/wide and $\mathcal{O}(500\mathrm{m})$ high
- consider relative changes rather than absolute. Since, even in our LES, there is some uncertainty about how to best calculate turbulent fluxes, we will contrast cases with and without SST structure, but with same air-sea temp difference

## development
Navid and Greg are currently working on _AquaSkyLES_ here: https://github.com/navidcy/AquaSkyLES.jl

Some of the development steps are:
- Moist buoyancy: model carries humidity $q$ which affects buoyancy (implemented)
- ...

## about this repo
Trialing this repo as a project management tool. It's private at the moment. I envisage that we will invite the other collaborators when there's something for them to look at and, at some point, make it public. 
