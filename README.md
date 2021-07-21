# glow_worm_optimization_algorithm

Assumptions of the Glowworm Swarm Optimization.
The Assumption:
This algorithm is derived from natural glowworm’s activities in the night, the glow worm exercise in groups, they interact with each other by one’s luciferin. If the glowworm emits more light, it can attract more glowworms towards it.
The GSO algorithm makes the agents glow at intensities approximately proportional to the function value being optimized 
• Glowworms of brighter intensities attract glow worms that have lower intensity 
• A dynamic decision range by which the effect of distant glow worms are discounted when a glow worm has sufficient number of neighbours or the range goes beyond the range of perception of the glowworms
Difference from FA: – no "sufficient number of neighbours" limit – no perception limit based on distance 
• „Cognitive limits" allows swarms of glowworms to split into sub-groups and converge to high function value points 
• Identification of multiple peaks of a multimodal function.

Answer:
A neighborhood as a local-decision domain 
Variable neighborhood range bounded by a radial sensor range i d r s r ( 0 ) s i d radial sensor range < r ≤ r 
A glowworm i considers another glowworm j as its neighbor if j is within the neighborhood range of i and the luciferin level of j is higher than that of i
The decision domain enables selective neighbor interactions and aids in formation of disjoint sub-swarms 
Each glowworm is attracted by the brighter glow of other glowworms in the neighborhood 
Agents in GSO depend only on information available in their neighborhood to make decisions

Luciferin and how it is modified by agents?
Luciferin is a light-emitting compound, used for the firefly is a value that is used in GLOWworm swarm optimization Each glowworm selects, using a probabilistic mechanism, a neighbor that has a luciferin value higher than its own and moves toward it.. which is responsible for the characteristic yellow light emission from many firefly species.
Each glowworm selects, using a probabilistic mechanism, a neighbor that has a luciferin value higher than its own and moves toward it • These movements (based only on local information and selective neighbor interactions) enable the swarm of glowworms to partition into disjoint subgroups that steer toward, and meet at, multiple optima of a given multimodal function
GSO starts by placing a population of n glow worms randomly in the search space so that they are well dispersed 
• Initially, all the glowworms contain an equal quantity of luciferin...
