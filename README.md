# Deep Reinforcement Learning for Microgrid Energy Management
This repository contains an implementation of a Deep Reinforcement Learning (DRL) algorithm for managing the energy demand and supply of a microgrid. The implementation is built using Python and is based on the OpenAI Gym environment.

## Installation
Clone the repository and navigate to the directory <br>
Create a conda environment <br>
<code> conda env create -f conda.yaml </code> <br>
Activate the environment <br>
<code> conda activate tf2-gpu </code>
## Usage
To train the DRL agent, you can use the A3C_plusplus.py file. <br>
<code> python A3C_plusplus.py --train </code> <br>

To evaluate the performance of a trained model, you can use the same file with the option --test. <br>

<code> python A3C_plusplus.py --test </code> <br>

## Paper
Taha Abdelhalim Nakabi, Pekka Toivanen,
Deep reinforcement learning for energy management in a microgrid with flexible demand,
Sustainable Energy, Grids and Networks,
Volume 25,
2021,
100413,
ISSN 2352-4677,
https://doi.org/10.1016/j.segan.2020.100413.
(https://www.sciencedirect.com/science/article/pii/S2352467720303441) <br>
Abstract: In this paper, we study the performance of various deep reinforcement learning algorithms to enhance the energy management system of a microgrid. We propose a novel microgrid model that consists of a wind turbine generator, an energy storage system, a set of thermostatically controlled loads, a set of price-responsive loads, and a connection to the main grid. The proposed energy management system is designed to coordinate among the different flexible sources by defining the priority resources, direct demand control signals, and electricity prices. Seven deep reinforcement learning algorithms were implemented and are empirically compared in this paper. The numerical results show that the deep reinforcement learning algorithms differ widely in their ability to converge to optimal policies. By adding an experience replay and a semi-deterministic training phase to the well-known asynchronous advantage actor–critic​ algorithm, we achieved the highest model performance as well as convergence to near-optimal policies.
Keywords: Artificial intelligence; Deep reinforcement learning; Demand Response; Dynamic pricing; Energy management system; Microgrid; Neural networks; Price-responsive loads; Smart grid; Thermostatically controlled loads



## Contributing
Contributions to this repository are welcome! If you find a bug or have an idea for an improvement, please submit a pull request.<br>

## License
This code is released under the MIT License.
