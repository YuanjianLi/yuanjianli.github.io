---
title: "Radio Resource Management for Cellular-Connected UAV: A Learning Approach"
collection: publications
permalink: /publication/2022-RRM-TCom-MajorRevision
date: 2022-10-04
venue: 'IEEE Transactions on Communications (TCom)'
paperurl: '/files/pdf/research/2022-RRM-UAV-DRL-MR-TC.pdf'
link: 'https://www.researchgate.net/publication/355043974_Radio_Resource_Management_for_Cellular-Connected_UAV_A_Learning_Approach'
citation: '<strong>Minor revision for IEEE Transactions on Communications (TCom), Oct. 2023.</strong>
<br>
<br>
Integrating unmanned aerial vehicles (UAVs) into existing cellular networks encounters lots of challenges, among which one of the most striking concerns is how to achieve harmonious coexistence of aerial transceivers, inter alia, UAVs, and terrestrial user equipments (UEs). In this paper, a cellular-connected UAV network is focused, where multiple UAVs receive messages from base stations (BSs) in the down-link, while BSs are serving ground UEs in their cells. For effectively managing inter-cell interferences (ICIs) among UEs due to intense reuse of time-frequency resource block (RB) resource, a first $p$-tier based RB coordination criterion is proposed and adopted. Then, to enhance wireless transmission quality for UAVs while protecting terrestrial UEs from being interfered by ground-to-air (G2A) transmissions, a radio resource management (RRM) problem of joint dynamic RB coordination and time-varying beamforming design minimizing UAV’s ergodic outage duration (EOD) is investigated. To cope with conventional optimization techniques’ inefficiency in solving the formulated RRM problem, a deep reinforcement learning (DRL)-aided solution is initiated, where deep double duelling Q network (D3QN) and twin delayed deep deterministic policy gradient (TD3) are invoked to deal with RB coordination in discrete action domain and beamforming design in continuous action regime, respectively. The hybrid D3QN-TD3 solution is trained via interacting with the considered outer and inner environments in an online centralized manner so that it can then help achieve the suboptimal EOD minimization performance during its offline decentralized exploitation phase. Simulation results have illustrated the effectiveness of the proposed hybrid D3QN-TD3 algorithm, compared to several representative baselines.'
---