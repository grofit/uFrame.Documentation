# Event Handler Nodes
Event handlers allow you to listen to a specific event and execute a sequence of actions (Visual Scripting) whenever an event occurs.

In uFrame you can listen to custom events defined in a library, all the standard unity messages, events defined in code tagged with the [uFrameEvent] attribute, or some other useful built-in events such as property-changes, and component/group created or removed events.

![](http://i.imgur.com/umx2Nzs.png)
## Scripting
- [Events](uframe-documentation/blob/master/tutorials/AddComponent.md)
- [Component Add/Remove Handlers](uframe-documentation/blob/master/tutorials/RemoveComponent.md)
- [Subscribing To Properties]()

# Entity Group Mappings
Entities are identifiable by a number, it is often the case where you want to signal an event for an entity and allow the handler to determine what group it should process the event with.  For this reasons, any integer property defined on an event will be available for mapping a group or component to it on the handler.

A good example of this is OnCollisionEnter, any component could process this type of event, but it must belong to an entity.  So therefore it has two properties:
- EntityId - The Source Id
  > By default "EntityId" appears as group on handler nodes
- ColliderId -The id of the entity that collided with

# Important! Event Dispatchers
Because components that belong to an entity can live on different game-objects, uFrame doesn't have a way to determine where the event should be dispatched from.  These types of events are a subset (Unity Messages).  In this case, uFrame will display a button on the component to ensure that you've added the dispatcher to the game-object.

![](http://i.imgur.com/p8TYcWd.png)

See: [Entities]()

# API Documentation

## F.A.Q
