# newhabitats
# mod for Stellaris
#
#################################
#         New Features          #
#################################
# Reworks Habitats to be more useful, focusing on specialization
# Habitat Districts now have jobs comparable with tier2 buildings of the same type but only require energy upkeep
# Habitat Districts also have housing associated with them to balance with admin cap, and the Housing District now adds 4 clerk jobs
# Foundry District is a new Habitat District, providing foundry jobs (since space manufacturing should enable some innovative manufacturing techniques)
# Reactor Districts can only be built in systems with a sun (no black holes or Dyson Spheres) and have output modifiers related to the number of Districts built.
# District Types are now added to a Habitat after it is created via Planetary Decisions
# Up to a Max of 3 District Types can be added to a Habitat (Housing is always available by default)
# Districts Types can be removed via Planetary Decisions for the cost of influence (must have none of that district on habitat)
# Habitats are now specialized with unique colony types, with Research Habitat, Trade Habitat, Leisure Habitat, Reactor Habitat, Foundry Habitat, and Residential Habitat with their own specialization bonuses.
# Buildings have been reworked so that most building types can be constructed on a habitat (exception is luxury housing)

#################################
#         Compatibility         #
#################################
# Designed in Stellaris 2.2
# Available for all languages (only in English)
# Following files are overwritten:
# -03_habitat_districts
# Following assets are overwritten:
# -colony_hab (habitat colony type)
# -research_lab_1, commercial_zone, holo_theatres, energy_grid buildings
# Planetary Decisions have no AI weighting, and AI has default habitat layout designs (should check Glavis AI if any help possible)
# -AI Default layouts are: Reactor, Foundry, Research (Gestalt), Reactor, Research, Leisure (Regular), Reactor, Leisure, Trade (Megacorp)
# -AI Default layouts can be modified by planet flags (energy_habitat, foundry_habitat, research_habitat, cultural_habitat, trade_habitat)

#################################
#         Known Bugs            #
#################################
# When removing a Habitat District, Icon for District remains even though it cannot be built. If a district is created on habitat, it will disappear. Anyone know how to fix this?
