CSS Event Queue
===============

CSS Event Queue - Synchronous / Asynchronous Javascript event queue for CSS Classes


## How it works

Allows you to both ADD and REMOVE CSS classes from DOM elements, synchronously and asynchronously.  This plugin allows us to bind classes to DOM elements (HTML Tags) based on '4' common types of events. These events include:
  
  • On Click - An element is clicked and the task scheduler initiates its queue.
  
  • On Hover - An element is hovered over and the task scheduler initiates its queue.
  
  • On Dom Ready - When the page has fully loaded the task scheduler initiates its queue.
  
  • On Active Class - When the class name "active" is detected, the task scheduler initiates its queue.
  
  
## Task Scheduler
'Task Schedulers' are a set of instructions for executing your animations. Each Task Scheduler accepts '4' paramaters per line, each 'line' within a task scheduler represents an instance (a moment in time where an object is targeted, a class is ethier added or removed, and a duration after which the event line will occur or begin.): The '4' Parameters per line are as follow:

  • Specify: Object being targeted
  
  • Specify: Whether a class is to be Added or Removed (+,-)
  
  • Specify: The class name to be added
  
  • Secify: The duration (If your duration is '300' then your class will be either Added or Removed after '300' milliseconds)


## Sample Task Scheduler (Sample 'Line')

***{'task_onDomLd_animation3': '+lightSpeedIn_200'}***

  • task_onDomLd_animation3

    • Object being targeted
    
  • +
  
    • Whether a class is to be Added or Removed (class is being added is this example)

  • lightSpeedIn
  
    • The class name to be added
  
  • 200
  
    • The duration: (in this example the class 'lightSpeedIn' will be added to 'task_onDomLd_animation3' after '200' milliseconds has elapsed)
