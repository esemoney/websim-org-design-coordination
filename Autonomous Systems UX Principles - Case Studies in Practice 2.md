source: https://websim.ai/c/cbUI2mOm81rdM7q26

# Autonomous Systems UX Principles: Case Studies in Practice

Let's look at how the [UX principles for autonomous systems](https://mcoai.dplmi.mit.edu/dept/resources/autonomous-systems-ux-principles) have been applied in real-world interface designs. These case studies demonstrate practical strategies for crafting effective user experiences in the context of AI and robotics applications, especially in high-stakes domains like the military.

## 1. Drone Fleet Control Interface

This interface was designed for military operators managing a swarm of autonomous surveillance drones. Key features include:

- **Autonomy Mode Indicators:** Each drone's card prominently displays whether it is in fully autonomous, semi-autonomous, or manual control mode, with color-coding.
- **Zoomable Map:** The central map allows operators to seamlessly zoom from a high-level fleet overview down to individual drone telemetry and video feeds.
- **Confidence Alerts:** When the system's object detection model has low confidence on a potential target, it raises an alert and prompts the user to review the imagery to confirm.

![Annotated screenshot of drone fleet control UI showcasing key features](https://mcoai.dplmi.mit.edu/images/drone-fleet-interface.png)

Drone fleet control interface with autonomy mode indicators, zoomable map, and AI confidence alerts.

## 2. Autonomous Driving Oversight Dashboard

Designed for the managers overseeing a fleet of autonomous transport vehicles on a military base, this dashboard focuses on fleet-wide insights while still allowing drilldown into individual AV performance. Notable elements include:

- **KPI Summary:** Key performance indicators like successful mission rate, manual intervention counts, and obstacle encounters provide an at-a-glance assessment of overall fleet status.
- **Filterable Mission Log:** A central mission feed can be filtered by vehicle, mission priority, and anomaly type to help users rapidly investigate emerging issues.
- **Telemetry Replay:** For post-mission analysis and training, any autonomy session can be replayed with synchronized visualizations of the perception outputs, decision making process, and control actions taken.

![Annotated screenshot of autonomous vehicle fleet management dashboard UI](https://mcoai.dplmi.mit.edu/images/av-oversight-dashboard.png)

Autonomous vehicle fleet oversight dashboard with high-level KPIs, filterable mission log, and integrated telemetry replay.

## 3. Collaborative Robot Mission Planning

This tablet interface allows soldiers in the field to quickly specify missions for a collaborative robot assistant, like scouting an area or carrying supplies, without needing to manage all the low-level task details. Key aspects include:

- **Graphical Mission Specification:** High-level tasks like "scout this area" or "deliver supplies here" can be rapidly laid out through taps and swipes on a map, with smart defaults for robot parameters.
- **Constraint Authoring:** Operators can add constraints to the mission, like "avoid this zone" or "move at this speed", through intuitive visual gestures and widgets.
- **Progressive Disclosure:** Mission specification starts simple, but additional customization options unfold progressively as needed, allowing novice and expert users to work at the level of detail they require.

![Annotated screenshot of collaborative robot mission planning interface on a tablet](https://mcoai.dplmi.mit.edu/images/cobot-mission-planning.png)

Collaborative robot mission planning interface with graphical task authoring, visual constraint specification, and progressive disclosure of options.

Through effective information architecture, interaction design, and visual storytelling, these interfaces make the complexities of autonomous systems more understandable and manageable for human operators under demanding real-world conditions. As designers, our goal should be to create experiences that enhance and complement the prodigious capabilities of AI, while keeping the human firmly in the loop.