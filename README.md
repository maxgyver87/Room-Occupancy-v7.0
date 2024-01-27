# Room-Occupancy-v7.0
HA Room Occupancy with timers. surviving a ha restart

this automation needs two things to set up:
- a single binary_sensor (for example: binary_sensor.office_occupancy)
  that contains all motion sensors in a room
- a timer entity (for example: timer.office_occupancy)
