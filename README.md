## Simulation Environment for the Miniature-Vehicle Platform Kiwi

Welcome to the repository that contains the simulation environment for the miniature vehicle platform Kiwi.

### Prerequisites

* Have `docker` installed: [Ubuntu Linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/), [Windows](https://docs.docker.com/docker-for-windows/install/), [MacOS](https://docs.docker.com/docker-for-mac/install/)
* Have `docker-compose` installed: [Instructions](https://docs.docker.com/compose/install/)

### Getting Started

After having installed `docker` and `docker-compose`, clone this repository:

```
git clone https://github.com/se-research/kiwi-simulation.git
```

Start the simulation environment by running the `docker-compose.yml` file. Thus, change to the directory where you just cloned the repository and run:

```
docker-compose -f docker-compose.yml up
```

`docker` will download the necessary components of the simulation environment and start them immediately.

Next, start a web-browser and connect it to: http://localhost:8081  You should see the front-end as shown below:

![Code](https://raw.githubusercontent.com/se-research/kiwi-simulation/master/Code.png)

In the main window, you are seeing four tabs: `Overview`, `Messages`, `Plot`, and `Simulation`. In the center part, you see the spiderweb visualization of the readings from the simulated Kiwi's distance sensors, and on the right side, you see the messages being currently exchanged in the simulation. The area to enter your JavaScript code for steering, accelerating, or deceleration Kiwi is shown at the bottom.

Next, click on the tab `Simulation` and you will see the currently active scenario:

![Simulation](https://raw.githubusercontent.com/se-research/kiwi-simulation/master/Simulation.png)
