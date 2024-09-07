This is an embedded project using STM32CubeIDE. It is a C project.  It features a timer driven interrupt with handler and callback.  
The main "thread" (its bare metal, no OS) and the interrupt callback share atomic access to a shared data structure, right now
just an array.  I checked in all the project files, so you should be able to clone it and open it as a project from STM32CubeIDE.

If you get it to build, then debug (F8).  No worries about breakpoints, after it runs a bit, just "pause" the debugger
and add shared_array to "Expressions" and it will expand displaying its data.

The type of data and data structures will become become more complex in the upcoming days.