# newhabitats
# mod for Stellaris
#
# Unsatisfied with how habitats work in 2.2 in preparation for remaking Voidborne in the Origins Civics mod, I reworked the Habitat system.  This mod focuses on Habitats and Habitat Districts.  Habitats can now be customizable via Planetary Decisions.  Habitats now give jobs comparable to Tier2 buildings and provide some housing in each District. Now most buildings are available to be built on a habitat. You also have access to the new Foundry District, which provides metallurgist jobs and the Reactor District for non-gestalt empires.  Have fun living in the void!
#
#################################
#         New Features          #
#################################
# Reworks Habitats to focus on specialization
# Habitat Districts now have jobs comparable with tier2 buildings of the same type with the Voidborne AP, but only require energy upkeep (no special resources)
# Habitat Districts also have housing associated with them to balance with admin cap, and the Housing District now adds 4 clerk jobs (5 with Master Builders AP)
# Foundry District is a new Habitat District, providing foundry jobs (since space manufacturing should enable some innovative manufacturing techniques)
# Reactor Districts can be built by all empire types, produce 50% more energy then a planetary district and have an output reduction if built near a black holes or Dyson Sphere.
# Habitat District Types are now customizable, added to a Habitat via new Planetary Decisions.
# Up to a Max of 3 District Types can be added to a Habitat (Housing is always available by default)
# Districts Types can be removed via Planetary Decisions for the cost of influence (must have none of that district on habitat)
# Habitats are now specialized with unique colony types, with Research Habitat, Trade Habitat, Leisure Habitat, Reactor Habitat, Foundry Habitat, and Residential Habitat with their own specialization bonuses.
# Buildings have been reworked so that most building types can be constructed on a habitat

#################################
#         Compatibility         #
#################################
# Designed in Stellaris 2.2.*
# Available for all languages (only in English)
# Following files are overwritten:
# -03_habitat_districts
# Following assets in files are overwritten:
# -colony_hab (habitat colony type)
# -research_lab_1, commercial_zone, luxury_residences, holo_theatres, energy_grid (buildings)
# Planetary Decisions have no AI weighting, and AI has default habitat layout designs (should check Glavis AI if any help possible since AI was not smart enough to use decisions in limited testing)
# -AI Default layouts are: Reactor, Foundry, Research (Gestalt), Reactor, Research, Leisure (Regular), Reactor, Leisure, Trade (Megacorp)
# -AI Default layouts can be modified by planet flags (energy_habitat, foundry_habitat, research_habitat, cultural_habitat, trade_habitat)

#################################
#         Known Bugs            #
#################################
# When removing a Habitat District, Icon for District remains even though it cannot be built. If a new district is created on the habitat, it will disappear. Anyone know how to fix this?
