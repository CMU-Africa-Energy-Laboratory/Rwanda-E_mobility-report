## Rwanda E-mobility report
# This report is categorized in 5 categories including
- Types of EVs
An electric vehicle is a vehicle that is powered by electric power - The powering can be partial or total. 
Many studies do not mention electric motorbikes/ 2 wheelers when they are referring to electric vehicles.
Here are the types of EVs: Battery Electric Vehicles (BEVs), Hybrid Electric Vehicles (HEVs), Plug-In Hybrid Electric Vehicles (PHEVs), Range Extenders (REXs), and Fuel Cell Vehicles (FCVs) [1].

- Business models in SSA


- Utility death spiral
Article: Utility pricing death spiral by A.J. Hutchinson, E. Gibson, and T. Phawen [2].
Factors that determine how quickly the utility will lose customers to alternative energy sources:
- strength of the economy
- minimum threshold of the price of the alternative energy
- rate of change - how are customers shifting from the utility to alternative energy

Article: Assessing the impact of residential load profile changes on electricity distribution utility revenues under alternative rate structures [3]. This one discusses the impact of PV rooftops and EVs on utility revenues, they find that EVs and PVs decouple peak load and energy consumption, which is problematic with volumetric rates for distribution utilities. They suggest that charges may be applied to consumers to recover from these capacity-related costs. Interesting fact: **The adoption of both PV and EV leads to decreasing energy consumption while significantly increasing maximum power demand.** 
ToU is hence better than volumetric rates in this case.
This reading was quite interesting. I highlighted the compelling parts- uploaded on Github.
Article: Structures tarifaires et spirale de la mort : État des lieux des pratiques de tarification dans la distribution d’électricité résidentielle [4].
It studies the impact of PV, EV and both on the load profile even though for the moment they’re relatively new technologies.
PVs don’t have a significant impact on consumption, especially during off-peak periods.
A scenario of decentralization of PVs corresponds to a death spiral phenomenon - again for a volumetric tariff base.
EVs significantly impact the load profile of its consumers - home charging.
Charging during peak hours causes the power factor to be multiplied by 1.5. This could possibly cause additional costs for the distributor.
Both PV  and EVs have the potential to substantially modify the load profiles of residential users.
Two points to note are:
- The utility’s revenue growth is equal to the growth of the amount paid by the user- hence if we consumer bill is increased 
- Distributors’ revenue is increased and this influences utility investments.
This study only focuses on the cost of the distribution side.
Article: Electric Utilities’ ‘Death Spiral’: Hyperbole or Reality? [5]
“Once losing sales to DG, utilities will try to recover lost revenues by increasing their rates to a fewer number of customers. This attempt to regain lost profits will aggravate the problem of yet more customers leaving the utility system for DG.”
DG = solar rooftops.
Reasons as to why certain entities face financial disasters such as a death spiral are inertia and complacency, poor management strategies, and unstoppable market trends (e.g. inexorably falling demand for a firm's product or service).
The term utility death spiral appeared in the 1980s.
They also highlight events that are conducive to a death spiral such as:
The recent growth of DG and their continued improved prospects for increased market share in the electric retail market
Permanent slowdown in demand growth
Public policies providing subsidies and incentives for less electricity usage and non-utility generation,
Rising costs placing pressure on utilities to increase their rates
Free riding by rooftop PV solar generation when they pay less than their fair share of utilities’ fixed costs
Increased customer demands for reliability and higher quality service; and
Higher ratio of fixed to variable costs that limits short-term cost savings from reduced sales.
They share that it’s important of a  rate design to avoid facing a death spiral.
“Finally, this article warns regulators that overprotecting utilities from the inevitable competition are not in the public interest. ”

- Models for EV Integration
Technical studies have been done to identify and solve EV grid integration issues-particularly in sub-Saharan Africa:
Article: Planning for variable renewable energy and electric vehicle integration under varying degrees of decentralization: A case study in Lusaka, Zambia [6]. 
The paper explores the potential benefits and disadvantages of EVs on the grid. One of them being Vehicle to Grid charging but it's too costly. Another interesting thing was this " a smart EV participation policy can reduce electricity costs for EV owners". The opportunities and challenges of large-scale electric vehicle adoption depend on their grid integration framework, of which there are several options: vehicle-to-home (V2H) charges through a home-based control scheme, vehicle-to-vehicle bidirectionally charges with the local grid according to a local aggregator's schedule, and vehicle-to-grid (V2G) bidirectionally charges with the power grid according to a system aggregator's schedule.
However, there are also potential negatives impacts from EV integration such as increased system load, increased peak demand, power quality issues, increased power loss, and transformer overloading as stated by [6].
Economic analyses have concluded that the current costs of V2Gs outweigh the benefits.
This model framework is then applied to explore three emerging trends: decentralization, increasing VRE penetrations, and the adoption of electric vehicles.
SILVER MODEL:
Inputs:
resulting grid configuration and demand profile
Charging EV profiles are constructed using a national household travel survey and a census of the population. The number of electric vehicles within each group is estimated using the forecasted 2050 Lusaka population, the current employment rate and school attendance, the share of urban/metro workers, and the students who travel by either urban/metro workers and students who travel by taxi, school bus or personal car, and a 10% EV penetration assumption.
 4 options are tested to explore the impacts of EV charging on electricity system planning and operation:
Unmanaged charging (intensive)
Nighttime off-peak time-of-use (TOU) charging
Daytime solar-correlated time-of-use (TOU_2) charging
Optimized vehicle to grid (V2G) charging
The choice of EV charging paradigm is the next most impactful parameter in terms of integration costs, due to the high peaking generator and storage capital costs; by eliminating the need for storage infrastructure, V2G charging reduces system infrastructure costs significantly.
However, mobility patterns and electric vehicles charging/discharging constraints are uncertain, as demonstrated by the diverse range of EV algorithms within the literature.

Another paper [7] presents a review of the many simulation tools that have been reported for modeling and managing the impact of electric vehicles on power distribution networks and associated applications. 
On this link is a vehicle to grid simulator.
The objective of this review is to provide a comprehensive guide to facilitate the selection of the most appropriate tools for integrating EVs into electricity distribution networks.
The energy usage of a vehicle is largely determined by the route taken, road congestion, traffic conditions, topology, etc. Any well planned route with optimized traffic systems and signaling will improve energy efficiency
EMCAS -  EMCAS can simulate all electric vehicle technologies, renewable energy generation subsystems and their integration.
ORCED -  is also used to analyze the PHEV and its impact on the grid and electricity generation according to a demand calculation on power distribution systems. It identifies the economical aspects of the grid integration of PHEV along with other renewable energy generation. 

Additionally [7] highlights that different researchers revealed that the utility grid must be innovative and upgraded and with Supervisory Control and Data Acquisition (SCADA) software package integration in order to shift from the traditional grid to the smart grid, so that it will be able to cooperate with future demand.
The solar energy system (integrating a solar PV system to a grid for the EV charging) as proposed in this research can lead to an efficient increase of national energy resource exploitation in the Rwanda, resulting in reliable, affordable, and sustainable energy access to all the citizens, and is known to be reliable and affordable and to have pillar sustainable development.

- Barriers and challenges
According to [8], here are some potential barriers and challenges to EV integration:
Requires strong enabling policies, including tax incentives and subsidies
Competing priorities for limited government funding in Sub-Saharan Africa
High initial investment costs upfront compared to internal combustion engine vehicles
Unavailable investment capital for smallscale local businesses & entrepreneurs
Current lack of charging infrastructure
Unfinished supply chains 
Lack of local technical skills & knowledge
“Range anxiety” and EV limitations 
Long recharging times and high costs for batteries
 Another barrier is that even with adequate policies put in place, consumers are not aware of EV technologies.
In Sacramento, California few consumers are engaged with PEVs, few have considered purchasing one, many cannot name a single BEV or PHEV presently for sale, and many are not aware of incentives to buy or advertising of them. Something REG or other stakeholders could look into [9].
[10] poses physical/operational constraint on the distribution infrastructure. The first highlighted case is when several electric vehicles are charging on a single transformer or branch that was initially designated for a number of residences - this could affect power stability in terms of voltage and current phase imbalances. The second case is charging of electric vehicles at peak times of electricity consumption - this could overload the service dropervice drop, the local distribution transformer, feeders or substation transformer. The recommendation are then an upgrade of the power system to prevent the above mentioned and the use of incentives for off-peak charging.
 
References:

<p>[1] Ajanovic, A. (2015), The future of electric vehicles: prospects and impediments. WIREs Energy Environ, 4: 521-536. https://doi.org/10.1002/wene.160.<br> 
[2] Hutchinson, J and Gibson, Emma and Phaweni, Thembani and Snyman, Dillon and Schmidt, Jeroen and Newman, Despina and Fhulufhelo, Ramphabana and Sam, Shalotte and Leope, Masilo and Makobela, Shireen et al. (2016), Utility Pricing Death Spiral. Mathematics in Industry Study Group, p. 53--71.<br>

[3] T. Beaufils, P. Pineau, Assessing the impact of residential load profile changes on electricity distribution utility revenues under alternative rate structures, Utilities Policy,Volume 61, 2019, 100959, ISSN 0957-1787, https://doi.org/10.1016/j.jup.2019.100959.<br>
 [4] T. Beaufils, P. Pineaun, et al., Structures tarifaires et spirale de la mort: Etat des lieux des pratiques de tarification dans la distribution d'electricite residentielle, 2018, CIRANO, Centre interuniversitaire de recherche en analyse des organisation.<br>
[5] Kenneth W. Costello, Ross C. Hemphill, Electric Utilities’ ‘Death Spiral’: Hyperbole or Reality?, The Electricity Journal, Volume 27, Issue 10, 2014, Pages 7-26, ISSN 1040-6190,https://doi.org/10.1016/j.tej.2014.09.011.<br>
[6] M. McPherson, M. Ismail, D. Hoornweg, M. Metcalfe, Planning for variable renewable energy and electric vehicle integration under varying degrees of decentralization: A case study in Lusaka, Zambia, Energy, Volume 151, 2018, Pages 332-346, ISSN 0360-5442,https://doi.org/10.1016/j.energy.2018.03.073.<br>
[7] Mahmud, Khizir and Town, Graham E, A review of computer tools for modeling electric vehicle energy requirements and their impact on power distribution networks, Applied Energy, 172, p.337--359, 2016, Elsevier.<br>
[8] E-Mobility Solutions for Rural Sub-Saharan Africa: Leveraging Economic, Social and Environmental Change, https://www.siemens-stiftung.org/<br>
[9] S.Hardman, K.S. Kurani, and D. Chakrabar "The usual policy levers are not engaging consumers in the transition to electric vehicles: a case of Sacramento, California," Environmental Research Communications, vol. 2, Aug 2020.Available: IOPSCIENCE, https://iopscience.iop.org/article/10.1088/2515-7620/aba943.<br>
[10] National Research Council, 2015a. Overcoming barriers to deployment of plug-in electric vehicles, Overcoming Barriers to Deployment of Plug-in Electric Vehicles. https://doi.org/10.17226/21725.
</p>











