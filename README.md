- S. Teerapittayanon, B. McDanel and H. T. Kung, "Distributed Deep Neural Networks Over the Cloud, the Edge and End Devices," 2017 IEEE 37th International Conference on Distributed Computing Systems (ICDCS), Atlanta, GA, USA, 2017, pp. 328-339, doi: 10.1109/ICDCS.2017.226.
  Link: https://ieeexplore.ieee.org/document/7979979
  Takeaways

*     proposes distributed deep neural networks (DDNNs) over distributed computing hierarchies, consisting of the cloud, the edge (fog) and end devices.
*     Using DDNN, lowered response latency and minimized communication can be achieved.
*     Run layers locally, at edge, and at cloud.
*     Experiment: Used multi-view multi-camera dataset to simulate multiple end devices. Different accuracy measures used for exit points in a DDNN are local accuracy, edge accuracy, cloud accuracy, overall accuracy, and individual accuracy.
*     Fault tolerance: Dicusses entropy threshold for an exit point, T,  VS the overall accuracy of DDNN. T = 0.8 gives the best accuracy and exits 60.82% of samples locally.
*      DDNNs improve accuracy by offloading difficult samples to the cloud while using NN layers that require under 2 KB of memory on end devices

- Xue, Yanfen & Fan, Guisheng & Yu, Huiqun & Sun, Huaiying. (2019). Energy-Aware Resource Scheduling with Fault-Tolerance in Edge Computing. 10.1007/978-3-030-30709-7_28.
  Link:https://inria.hal.science/hal-03770567v1/document
  Takeaways
-     allocate resources by reliability and energy-aware resource scheduling method
-     proactive scheme: jointly consider the CPU temperature and time between fail- ures (TBF) of the host to achieve fault prediction AND propose an energy-aware fault-tolerant resource scheduling algorithm
-     Specifically, we use the reliability and energy- aware resource scheduling [2] to allocate resources for tasks firstly.
-     CPU temperature prediction and time between failures prediction are used to achieve fault tolerance.

- Sharma, Yogesh & Javadi, Bahman & Si, Weisheng & Sun, Daniel. (2016). Reliability and Energy Efficiency in Cloud Computing Systems: Survey and Taxonomy. Journal of Network and Computer Applications. 74. 10.1016/j.jnca.2016.08.010.
  Link: https://www.researchgate.net/publication/306140052_Reliability_and_Energy_Efficiency_in_Cloud_Computing_Systems_Survey_and_Taxonomy
  Takeaways
-     Cloud failues causes: software failure, hardware failure, scheduling, service failure, power outage, network connectivity, cyber attacks, and human erros.
-     Usually, there are two types of failues managements in cloud computing: reactive and proactive.
-     Levels of energy efficiency enhancement: Energy-Efficiency applications, power aware resource management (energy aware task scheduling and reousrec provisioning policies), and hardware energy efficiency (clock frequency, voltage supply, etc).
-     Power management methods: static/offline (circuitry systems) and dynamic (softare based policies).
-     Defining the relationshinp between failures and energy efficiency will help to simultaneously increase the reliablity and energy efficiency of cloud computing systems.
-     Inverse trade-off between reliablity and energy efficiency (figure 11).
