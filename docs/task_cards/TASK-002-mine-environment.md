# TASK-002 — Open-Cast Mine Environment

## Objective

Create a modular open-cast mining environment for Mine-ADAS simulation.

The environment must support haul-truck operation, perception testing,
collision-risk testing and adverse-visibility scenarios.

## Environment Components

### Terrain

- Open-pit geometry
- Mine benches
- Slopes
- Ramps
- Flat haul-road sections
- Inclined haul-road sections
- Ground surface
- Excavated areas

### Road Network

- Main haul road
- Curved sections
- Intersections
- Blind curves
- Inclines
- Declines
- Loading area
- Dumping area
- Parking/staging area

### Static Objects

- Rocks
- Barriers
- Warning signs
- Road markers
- Mine structures
- Lighting poles
- Safety infrastructure

### Dynamic Objects

The environment should eventually support:

- Other haul trucks
- Light vehicles
- Personnel placeholders
- Construction/mining equipment

## Environmental Conditions

The simulation should eventually support:

- Clear weather
- Fog
- Dust
- Low visibility
- Night
- Variable lighting

## Gazebo Requirements

Target:

- Gazebo Harmonic
- SDF world
- Physics enabled
- Collision geometry
- Visual geometry
- Modular model insertion

## ROS 2 Requirements

The world should support:

- Vehicle spawning
- Sensor simulation
- TF integration
- ROS 2 sensor topics
- RViz2 visualization

## Terrain Requirements

Prefer:

1. Existing Gazebo terrain
2. Existing open terrain mesh
3. Heightmap
4. DEM/DTM
5. Custom procedural terrain

## Deliverables

- [ ] Mine terrain
- [ ] Haul-road network
- [ ] Mine benches
- [ ] Slopes
- [ ] Static obstacles
- [ ] Mine structures
- [ ] Weather/visibility variants
- [ ] Gazebo world file
- [ ] Screenshot
- [ ] License information
- [ ] Source information

## Acceptance Test

The environment must:

1. Load in Gazebo Harmonic.
2. Allow the haul truck to drive through the environment.
3. Contain realistic mining-road geometry.
4. Support static obstacles.
5. Provide collision geometry.
6. Allow sensors to operate correctly.
7. Support future fog/dust/night scenarios.

## Status

NOT STARTED

## Assigned To

Sharvaesh
