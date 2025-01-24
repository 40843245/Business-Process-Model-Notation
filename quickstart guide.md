# quickstart guide
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

> Features
> 
> A pool can be open (i.e., showing internal detail) when it is depicted as a large rectangle showing one or more lanes,
>
> or be collapsed (i.e., hiding internal detail) when it is depicted as an empty rectangle stretching the width or height of the diagram.
