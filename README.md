# Autonomous ODD Extraction PoC

Extracting and structuring Operational Design Domain (ODD) for autonomous driving systems from the NuScenes dataset using System Entity Structure (SES) to enable safe scenario generation.

---

## Definition and Scope

Operational Design Domain (ODD) are extracted and structured using System Entity Structure (SES) from real-world datasets like NuScenes to meet the safety and performance criteria of autonomous driving systems. ODDs define the environmental, operational, and geographical boundaries within which autonomous systems can operate safely.

The hierarchical modeling power of SES enables understanding and organizing complex, multidimensional real-world data, making it usable for automated scenario generation. Additionally, ODD data is stored in flexible and consistent formats such as Protocol Buffers (Protobuf) and YAML through data-driven methods.

---

## Fundamental Concepts and Theoretical Background

### Ontology  
An explicit and standardized definition of concepts, attributes, and relationships within the domain. Different environments, objects, and vehicle conditions in autonomous driving are ontologically modeled. Ontology ensures automation and consistency in scenarios and system interactions.

### System Entity Structure (SES)  
Defines complex systems through entities, aspects, specializations, and multi-aspects.  
- **Entities:** e.g., Environment, VehicleState, OperationalCondition  
- **Aspects:** e.g., Weather, Position, SensorTypes  
- **Specializations:** e.g., Clear, Rainy, Snowy (for Weather)  
- **Multi-Aspects:** e.g., Sensors on the vehicle (Lidar, Radar, Camera)  
SES manages system complexity and creates model-based structures for automation.

### Operational Domain (OD)  
The broad set of operational environments and conditions in which the system is expected to perform its functions, such as all road types, traffic conditions, and environmental factors where the vehicle can operate.

### Operational Design Domain (ODD)  
A subset of the OD that specifies the bounded and precise conditions where the system can operate safely and effectively. ODD includes environmental, operational, and geographical constraints and is critical for system safety. It is concretized hierarchically within the SES structure.

---

## Purpose and Contributions

- To reduce complexity and provide an analyzable structure by generating **SES-based ODDs from rich real-world datasets like NuScenes**.

- To enable realistic, diversified, and comprehensive automated scenario generation through ODDs, improving testing, simulation, and validation processes.
