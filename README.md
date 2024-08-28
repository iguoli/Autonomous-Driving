# Autonomous-Driving
Knowledge related to the field of autonomous driving 

## Concepts

### [SOP](What does start of production in the automotive industry mean?)

The **Start Of Production** in the automotive industry refers to the beginning of manufacturing of a new vehicle model or a significant update to an existing model. This typically involves the setup and calibration of production lines, testing of manufacturing processes, and the actual assembly of the first units of the vehicle. It marks a critical milestone in the development of a new product and is often accompanied by media announcements and celebrations within the company.

During the vehicle development several vehicle builds take place in parallel with the design process

Initially there are rough prototypes, in which new bits and pieces(say the engine) are installed in old bodies. These are built in a workshop. The results of the tests on these are analysed and used to improve the new design.

Then at some point we build cars off soft tooling. These look and behave much like real cars, but because the tooling is cheap we can still make big changes (not so true nowadays). These are often built in a pilot plant.

Then the big money gets spent on hard tooling, and the first real cars to the final design roll off either a pilot plant or the production plant. This could be several hundred vehicles. This is often done in two batches, the first batch will be missing a few parts and have handmade bridging parts.

The tail end of that batch will be used as long lead press cars. The others will be used for checks on homologation and some other tests, and lots of drives. After testing or whatever they’ll be used as the basis of prototypes for the next program, or scrapped.

Finally, most factories close for a couple of months and the assembly line is re-tooled to build the new model efficiently. It is started up, and after a few days of fine tuning, will be brought up to full line speed, which can be 80 cars per hour. All those cars are theoretically saleable units but some will be taken off for testing.

Different companies have different terminology for each build, and it changes over time, so I am hesitant to name them. Anyway start of production is Job #1 is the first saleable units.

### CP60

- **Commute Pilot 60 (CP60)** offers Level3 (L3) automation up to 60 km/h following a lead vehicle in dense traffic or traffic jams. The function keeps its lane and distance to leading vehicle without necessity of driver's supervision.

- CP60 automation is only possible within a pre-defined **Operational Design Domain** (ODD), e.g. only on highways with specific layout and function-usage approval by BMW.

- The function is optimized for traffic jams in daily commuting use cases, especially for the Chinese market where traffic jams during daily commuting are frequent.

- During CP60 operation, secondary driver activities and permanent hands-off / eyes-off are permitted.

- Typical customer use cases are:

  - Activities like e-mails, movies, working, etc.
  - Relaxing, driving pleasure / enjoying the ride.

### Safety Related Scenario (SRS)

- Ego/Host Vehicle: current vehicle

- Leading Vehicle: other vehicle driving in front of Ego

- Object: object in the scene which is not the Ego vehicle (could also be the leading vehicle)

## Autonomous Driving levels

### 0 级驾驶自动化（应急辅助）

驾驶员具有绝对控制权的阶段，FCW前部碰撞预警和LDW车道偏离预警功能都可归类于0级自动驾驶。

### 1 级驾驶自动化（辅助驾驶 Driver Assistance）

1级自动驾驶可具备ACC自适应巡航或者LKA车道保持辅助功能。

### 2 级驾驶自动化（半自动化 Partial Automation）

2级驾驶自动化将在1级驾驶自动化的基础上，拥有ICC集成式巡航辅助功能（即同时具备自适应巡航控制功能和车道保持辅助功能）。

### 3 级驾驶自动化（有条件自动驾驶 Conditional Automation）

可谓是驾驶自动化的分水岭，在3级之前的驾驶自动化，都只能算作驾驶辅助系统。

具备3级自动驾驶系统的汽车，将有条件实现TJP (Traffic Jam Pilot) 交通拥堵辅助功能（指在拥堵的高速公路或城市快速路上，驾驶员可以放开双手双脚，同时注意力可在较长时间内从驾驶环境中转移，做一些诸如看手机、接电话、看风景等活动）。

### 4 级驾驶自动化（高度自动驾驶 High Automation）

4级驾驶自动化虽然仍属于有限制条件的自动驾驶，但驾驶员的角色在驾驶自动化系统被激活后，已经转变为乘客或调度员，不再是后援用户。因此无论汽车的方向和加减速控制，路况观测和反应，以及汽车遇到故障时的接管任务，自动驾驶系统都能够且应该完成，不需要人类参与。除非在请求驾驶自动化系统退出后，驾驶员的角色才能恢复。

### 5 级驾驶自动化（完全自动驾驶）

## Terms

| Term   | Explanation                                   |
| ------ | --------------------------------------------- |
| ADAS   | Advanced Driver Assistance Systems            |
| ADCAM  | Autonomous Driving Camera                     |
| BN     | Boardnet                                      |
| CAN    | Controller Area Network                       |
| DDD    | Data Driven Development                       |
| DQ     | Data Quality                                  |
| ECU    | Eletronic Control Unit                        |
| FRR    | Far Range Radar                               |
| HDmap  | High Definition Map                           |
| HiL    | Hardware in the Loop                          |
| KPI    | Framework Key Performance Indicator Framework |
| LIDAR  | Light detection and ranging                   |
| MF4    | /MDF4 Measurement (Data) Format 4             |
| mPAD   | Modular Package for Autonomous Driving        |
| RaaS   | Reprocessing as a Service                     |
| RDIFF  | Reprocessing Diff Tool                        |
| RPU    | Reprocessing Unit                             |
| SiL    | Software in the loop                          |
| SRepro | SiL Reprocessing                              |
| SRR    | Short Range Radar                             |
| SuT    | System under Test                             |
| ViL    | Vehicle in the Loop                           |

### ADFT

**ADTF**（AUTOMOTIVE DATA & TIME-TRIGGERED FRAMEWORK）是一款汽车数据与时间触发框架，可用于开发车辆驾驶辅助系统。提供一系列功能和工具来支持车辆自动化和驾驶辅助系统的开发和测试。ADTF能用于快速原型设计、仿真、数据记录和验证（后处理）。
