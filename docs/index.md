# ROS2 by Projects

This website aims to provide resources to steadily understand most concepts revolving around ROS2 by tackling them independantly and letting learners experience by writing themselves a dedicated package. To achieve this, the content will be sliced in several modules, each tackling the subject with several robot: from simple simulation robots to manipulate small bits of code, to real robots to slowly fade into industries actual tasks.

``` mermaid
classDiagram
  class `Core 0: Overview` {

  }
  class `Core 1: Basics concepts` {

  }
  `Core 0: Overview` --> `Core 1: Basics concepts`
  class `Core 2: Advanced concepts` {

  }
  `Core 1: Basics concepts` --> `Core 2: Advanced concepts`
  class `Core 3a: Manipulators` {

  }
  class `Core 3b: Mobile robots` {

  }
  `Core 2: Advanced concepts` --> `Core 3a: Manipulators`
  `Core 2: Advanced concepts` --> `Core 3b: Mobile robots`
  class `Core 4: Diverse topics` {

  }
  `Core 3a: Manipulators` --> `Core 4: Diverse topics`
  `Core 3b: Mobile robots` --> `Core 4: Diverse topics`
```
