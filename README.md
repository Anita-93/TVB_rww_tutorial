**Modeling resting state with TVB**

Anita Monteverdi, Fulvia Palesi, Marta Gaviraghi, and Roberta Maria Lorenzi

**What can I find here?**

**Context**


A current topic in system neuroscience literature is the presence of brain activity in the absence of a task condition. These task-negative, spontaneous fluctuations occur in the so-called rest state, and a recurring theme of these fluctuations is that they have a network structure. Because TVB uses the structural connectivity of the brain as the backbone for simulating spontaneous activity, resting state activity and its network structure is a prime candidate for modeling in TVB.

**Objectives**


In this notebook, we will start from Zimmerman et al, 2018 to:

Build a brain network model using subject-specific structural connectivity,

Globally optimize parameters of the models,

Define and simulate dynamics of the whole brain at rest,

Characterize the resting-state activity using the functional connectivity (FC).


**References**


If you want to see more details about this model, its extended version and its application to neurodegenerative diseases please check the following papers:

(Wong & Wang, 2006): Wong, K.-F. & Wang, X.-J. A recurrent network mechanism of time integration in perceptual decision. J. Neurosci., 2006, 26, 1314-1328.

(Deco et al., 2013): Deco, G., Ponce-Alvarez, A., Mantini, D., Romani, G.L., Hagmann, P. & Corbetta, M. Resting-state functional connectivity emerges from structurally and dynamically shaped slow linear fluctuations. J. Neurosci., 32(27), 11239-11252, 2013.

(Hansen et al., 2015): Hansen, E.C., Battaglia, D., Spiegler, A., Deco, G. & Jirsa V.K. Functional connectivity dynamics: modeling the switching behavior of the resting-state. NeuroImage, 105(2015), 525-535.

Zimmermann, J., Perry, A., Breakspeare, M. et al. Differentiation of Alzheimer's disease based on local and global parameters in personalized Virtual Brain models. NeuroImage:Clinical, 2018, 19, 240-251.

(Palesi et al., 2020): Palesi, F., Lorenzi, R. M., Casellato, C., Ritter, P., Jirsa, V., Wheeler- kingshott, C. A. M. G., and Angelo, E. D. (2020). The importance of cerebellar connectivity on simulated brain dynamics. Frontiers in Cellular Neuroscience, 14,1–11.

(Monteverdi et al., 2022): Monteverdi A, Palesi F, Costa A, Vitali P, Pichiecchio A, Cotta Ramusino M, Bernini S, Jirsa V, Gandini Wheeler-Kingshott CAM and D’Angelo E (2022) Subject-specific features of excitation/inhibition profiles in neurodegenerative diseases. Front. Aging Neurosci. 14:868342. doi: 10.3389/fnagi.2022.868342

(Monteverdi et al., 2022): Monteverdi A, Palesi F, Schirner M, Argentino F, Merante M, Redolfi A, Conca F, Mazzocchi L, Cappa SF, Cotta Ramusino M, Costa A, Pichiecchio A, Farina LM, Jirsa V, Ritter P, Gandini Wheeler-Kingshott CAM and D’Angelo E (2023) Virtual brain simulations reveal network-specific parameters in neurodegenerative dementias. Front. Aging Neurosci. 15:1204134. doi: 10.3389/fnagi.2023.1204134


Brain dynamics simulations with TheVirtualBrain can be performed online after free registration and login on Ebrains platform at https://wiki.ebrains.eu/bin/view/Collabs/tvb-ww-tutorial/Lab.
