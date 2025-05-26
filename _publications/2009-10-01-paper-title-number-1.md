---
title: "NTP Transient Reactor Modeling and Uncertainty Propagation"
collection: publications
category: manuscripts
permalink: /publication/NETS2025
excerpt: 'Paper presented as a conference talk at NETS 2025, held at NASA MSFC. Work carried out as a summer/fall intern with AMA.'
date: 2025-05-05
venue: 'Conference: Nuclear and Emerging Technologies for Space (NETS 2025)'
paperurl: 'https://www.researchgate.net/publication/391670154_NTP_Transient_Reactor_Modeling_and_Uncertainty_Propagation'
citation: 'Mowery, E., Stonehill, J., Smith, C., &amp; Duchek, M. (2025). &quot;NTP Transient Reactor Modeling and Uncertainty Propagation.&quot; <i>Nuclear and Emerging Technologies for Space (NETS 2025)</i>. May 2025, Huntsville, AL.'

---
This was the basis for my first full-length conference talk. Transient modeling of NTP engines, with a focus on the reactor subsystem, is not a widely-explored topic. Abstract here:

The successful design and operation of a nuclear thermal propulsion (NTP) system requires a means of predicting reactor performance through demanding full-system transients. A transient modeling methodology based on the point reactor kinetics (PRK) approximation provides a simple means of evaluating reactor response to reactivity insertions, but its accuracy depends heavily on the quality of kinetic parameters and reactivity coefficients initially supplied as inputs. An open-source Monte Carlo neutron transport code (OpenMC) can determine these inputs on a reactor-dependent basis, but with measurable uncertainty inherent to its stochastic process. When propagated through the over the course of a simulated transient, this uncertainty can result in unacceptably large error bounds on anticipated system performance.

This report details a flexible, two-stage methodology for both utilizing OpenMC to generate reactor-dependent input data for a simple PRK-based transient model and the utilization of this model to measure the impact of the uncertainty associated with the input data on transient reactor performance. The Testing Reference Design is then used to demonstrate the relative impact of different sources of uncertainty on the system performance and establish minimum OpenMC particle counts needed to generate useable input data. Ultimately, this development of this methodology aims to serve as a foundation for informing the reactor-specific input data accuracy needed to produce useful transient results with the higher fidelity models.
