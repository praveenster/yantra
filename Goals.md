# Goals #
The main goal/objective of this project is:
  1. to develop a tool that allows the user to describe what functionality they want to implement by modeling the aspects rather than focus on how to implement it, thereby letting the the tool generate the code and handle the programing language/SDK intricacies.

The overall goals/objectives of this project are:
  1. code only visually. user would typically not modify the generated source, similar to how users typically don't modify the generated assembly language from a compiler.
  1. intermediate representation (possibly in xml) with bindings to any language, sdk, framework etc.
  1. components can either be white box or black box, allowing for connecting to closed source libraries.
  1. business logic description using a variety of techniques:
    * flowcharts
    * sequence diagrams
  1. this tool should be able to generate the code for the tool itself!
  1. support version control to merge models
  1. tool needs to abstract away a lot of the code level details, similar to how the compiler generates assembly language instructions and abstracts away the machine details from the user.
  1. tool will contain a huge library of template/patterns for domain specific and domain independent problems that have elegant solutions. for example, parsing of buffers, protocol implementations etc.
  1. tool to allow the user(s) to view the system from a variety of angles (ui, component view, hierarchical view etc.)