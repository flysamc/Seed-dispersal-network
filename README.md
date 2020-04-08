# Seed-dispersal-network
 Netlogo implementation of downsizing effect on functional and structural decay in seed dispersal network

A modeling approach to quantify the consequences of downsizing—relative to random extinctions—for the number of interactions and secondary plant extinctions(as measures of structural robustness) and for long-distance seed dispersal (as a measure of ecosystem function)

Model: Here we create interaction network (Links) between bird and Plant species baesd on observation of real world interaction network.


References:
1. Donoso, Isabel, et al. "Downsizing of animal communities triggers stronger functional than structural decay in seed-dispersal networks." Nature Communications 11.1 (2020): 1-8.
2. Bender, Irene MA, et al. "Morphological trait matching shapes plant–frugivore networks across the Andes." Ecography 41.11 (2018): 1910-1919.


## Entities: 
1. Diffrent # of bird species (Breed)
2. Different # of plant species(Breed)
3. Links between bird and plants species (Links)
-------------------
Variables:
Bird_species: Different breed of to Turtles represent by different colors.
Mass: Each turtle has its own mass. 
Constant_mass: Each turtle of same breed has constant mass
Varying_mass: Each turtle of same breed has mass vary in certain range base of some distribution
Plant_species: Different color patches represent different plant species
Plant_species_weight: Color patches based on seed size
Interaction_network: (slider) Represent Link between Bird_species and Plant_species. Follow rule of Downsizing which means larger mass species have more interactions.
Extinction_percent_random: (slider) percentage of extinction (i.e. random network loss)
Extinction_percent_downsizing: (slider) percetage of extinction based on downsizing
LDD_patch: long distance dispersal results for each bird_species calculated from max_distance of Bird_species and Final_patch
LDD: Sum of all the LDD_patch
Plot_extinction_random_NOI: extinction plot based on extinction v/s no. of intraction loss
plot_extinction_downsizing_NOI: as above but for downsizing
plot_extinction_random_secondary: loss by secondary plant extinction
plot_extinction_downsizing_secondary: as above for downsizing
plot_extinction_random_LDD: ldd after extinction random
plot_extinction_downsizing_LDD: same as above for downsizing

