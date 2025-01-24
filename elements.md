# BPMN
## Elements
Elements in BPMN is a small unit of an enitity. It behaves like entities in ERD.

It includes 

+ Flow objects
+ Connecting objects
+ Swim lanes
  
## Flow objects
+ events
+ activities
+ gateways

### Connecting objects
+ sequence flow
+ message flow
+ association

## Swim lanes
+ pool
+ lane
+ dark pool

## Events
Events represents something that is happening.

It includes

+ start event (or start)
+ intermediate event (or intermediate)
+ end event (or end)

<img width="118" alt="image" src="https://github.com/user-attachments/assets/584f639a-fe0d-4e84-abc5-f3fbe60b21f8" />

## Activities
Activity represents something that is done.

It includes

+ Task (process)
+ Subprocess
+ Transaction
+ Activity

<img width="122" alt="image" src="https://github.com/user-attachments/assets/062c2251-c4d8-4081-8380-7a311489f678" />

## Gateways
Gateways forks one path into two different paths. It behaves like gateway in airplane port.

It includes

+ Exclusive
+ Event Based
+ Parallel
+ Inclusive
+ Exclusive Event Based
+ Complex
+ Parallel Event Based

<img width="128" alt="image" src="https://github.com/user-attachments/assets/5cf232f6-70e3-4db5-8e40-72480f493369" />

## Connections
Connections connects two object together.

It includes

+ Sequence Flow
+ Message Flow
+ Association

<img width="127" alt="image" src="https://github.com/user-attachments/assets/e5f2f8de-91cc-4994-a494-a77b284c8fff" />

## Pools
Pools represent major participants in a task (or process).

<img width="119" alt="image" src="https://github.com/user-attachments/assets/2df6b9b3-32ae-4357-8a72-e977f588b48c" />

Features
 
+ be open (i.e., showing internal detail) when it is depicted as a large rectangle showing one or more lanes,

+ be collapsed (i.e., hiding internal detail) when it is depicted as an empty rectangle stretching the width or height of the diagram.

## Lanes
Used to organise and categorise activities within a pool according to function or role.

It includes

+ flow objects
+ connecting objects
+ artifacts.

## Artifacts
Used to bring some more information into the model or diagram.

There are three pre-defined artifacts:

+ data objects
+ group
+ annotation

## Data objects
Illustrate which data is required or which data is produced during activities.

<img width="121" alt="image" src="https://github.com/user-attachments/assets/ad42092b-8eaa-4a5e-a83c-2d32c5a9ae5f" />

## Groups
Used to group many same or similar activities, that not affect to flow, into one group.

<img width="122" alt="image" src="https://github.com/user-attachments/assets/ddef269d-1640-4bce-9763-bdfbb8992700" />

## Annotations
Used to annotate important part of activities that make the model or diagram more readable.

<img width="133" alt="image" src="https://github.com/user-attachments/assets/eb652dcd-37d2-47a0-a4c6-be5e0b1fd640" />

## Reference
+ [`BPMN (Wiki)`](https://en.wikipedia.org/wiki/Business_Process_Model_and_Notation)
