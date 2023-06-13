# bee_friendly_plants
Analise do dataset referente a escolha de plantas que são ideais para abelhas: Nativas ou não nativas

# Background
You work for the local government environment agency and have taken on a project about creating pollinator bee-friendly spaces. You can use both native and non-native plants to create these spaces and therefore need to ensure that you use the correct plants to optimize the environment for these bees.

The team has collected data on native and non-native plants and their effects on pollinator bees. Your task will be to analyze this data and provide recommendations on which plants create an optimized environment for pollinator bees.

# The Data
You have assembled information on the plants and bees research in a file called plants_and_bees.csv. Each row represents a sample that was taken from a patch of land where the plant species were being studied.

# Column	   Description

#sample_id	 The ID number of the sample taken.

species_num	The number of different bee species in the sample.

date	Date the sample was taken.

season	Season during sample collection ("early.season" or "late.season").

site	Name of collection site.

native_or_non	Whether the sample was from a native or non-native plant.

sampling	The sampling method.

plant_species	The name of the plant species the sample was taken from. None indicates the sample was taken from the air.

time	The time the sample was taken.

bee_species	The bee species in the sample.

sex	The gender of the bee species.

specialized_on	The plant genus the bee species preferred.

parasitic	Whether or not the bee is parasitic (0:no, 1:yes).

nesting	The bees nesting method.

status	The status of the bee species.

nonnative_bee	Whether the bee species is native or not (0:no, 1:yes).

# Source

https://datadryad.org/stash/dataset/doi:10.5061/dryad.pzgmsbcj8

# Challenge

Provide your agency with a report that covers the following:

Which plants are preferred by native vs non-native bee species?
A visualization of the distribution of bee and plant species across one of the samples.
Select the top three plant species you would recommend to the agency to support native bees.
