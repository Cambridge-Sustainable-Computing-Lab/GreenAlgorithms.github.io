---
permalink: /dashboard/

title: "Green Algorithms Dashboard"
excerpt: "Enabling users to monitor the energy usage and carbon footprint of their HPC use."



toc: true
toc_sticky: true

header:
  overlay_image: assets/images/stripes_banner_1.png
  overlay_filter: linear-gradient(rgba(255, 255,255, 0), 20%, rgba(255, 255, 255, 1))
  text_color: rgb(80, 80, 80)
  actions:
  - label: "Check out on GitHub"
    url: https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-HPCdashboard
---

# Green Algorithms Dashboard 
![Version: Gamma (pre-release)](https://img.shields.io/badge/version-Gamma_(pre--release)-orange)
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/purple?icon=github)](https://github.com/Naereen/badges/)

The Green Algorithms Dashboard helps to make visible the environmental impacts of high performance computing (HPC) workloads. By connecting to workload managers such as SLURM, the dashboard automatically captures job-level information and translates it into meaningful insights into energy use, carbon emissions, and more. Users can see how their work contributes to overall resource consumption and emissions, whether at the level of individual users or across teams and institutions.

An intuitive, interactive Grafana interface combines high-level summaries—including easy-to-digest, relatable equivalences of carbon emissions expressed in terms of flights, car travel, or tree sequestration—with detailed breakdowns of resource usage at individual, team and organisation level

![GA dashboard screenshot](/assets/images/dashboard/user.png "GA dashboard")

__Try it out yourself!__ \\
Check out our [demo website](https://dashboard.green-algorithms.org/) set up with mock data for visualising a running dashboard. _(Make sure to set the date range between May 2023 - June 2023 to see the data)_ \\
 Log in details: Username: `uid_1` | Password: `user1`
{: .notice--success}

### Key Features
- Open-source 
- Multi-level data aggregation across users, groups, departments, and institutions
- Cluster-informed emissions estimation built into the system
- Real-time carbon intensity via the Carbon Intensity API (for UK-based clusters only)
- Grafana-based dashboard with interactive visualisations and plots
- Visibility into carbon emissions from failed jobs
- Data processed and stored locally on the HPC system for privacy and control

### Who is it for?
The dashboard is intended for users of research computing infrastructure, including researchers running computational workloads. System administrators and research software engineers play a key role in installing, configuring, and maintaining the dashboard on HPC systems.

### Quick walkthrough
The dashboard is divided into four sections—your activity, your group's, your department's, and your institution's—each providing a progressively broader view of carbon emissions and resource usage. 

Users are greeted with key plots and metrics summarising the carbon footprint and energy consumption of their work. At a glance, they can track their carbon footprint over time, see how it correlates with energy consumption, and understand how that energy is distributed across CPU, GPU, and memory. This makes it easy to spot whether one component dominates and how that contributes to their total energy consumption—and in turn, their carbon footprint.

![User's energy usage and carbon emission](/assets/images/dashboard/user_walkthrough_1.png "User's energy usage and carbon emission")

The section that follows focuses on resource wastage, particularly from failed jobs. While failed jobs are sometimes intentional—testing scripts, for example—understanding their energy cost encourages better habits, like running tests on small datasets with minimal processing.

![User's failed job vs successful jobs](/assets/images/dashboard/user_walkthrough_2.png "User's failed job vs successful jobs")

Aggregations at group, department, and institution level then reveal how resources are distributed across members, enabling high-level insights that can drive collective impact beyond what individual action alone can achieve.

![Deptarment's carbon emissions](/assets/images/dashboard/dept_walkthrough.png "Deptarment's carbon emissions")

### How does it work?

The dashboard estimates the energy usage and carbon footprint of all jobs based on logs from the workload manager using the same [methodology](https://doi.org/10.1002/advs.202100707) as the other Green Algorithms tools. It uses information about the computing infrastructure used, for example hardware used, energy efficiency of the building, and location, to provide tailored estimates.This data collection, aggregated per user, is done daily by the dashboard’s backend.

![GA Dashboard flowchart](/assets/images/dashboard/GADashboard_vertical.png "GA Dashboard flowchart")

### Getting started
For installation instructions, configuration details, and deployment guidance, please refer to the [GitHub repository](https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-HPCdashboard/tree/main).

### Getting help
If you have questions, run into issues, or want to share feedback, please open a thread in [GitHub Discussions](https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-HPCdashboard/discussions). This is the best place to get support from the development team and the wider community.

### Licence
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This work is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0).