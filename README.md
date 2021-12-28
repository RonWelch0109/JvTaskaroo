taskaroo
========
A Java library that handles execution of tasks. Tasks can be executed sequentially, in parallel, or in any order.

**Features**
- Tasks are completely thread safe
- Tasks can be canceled before they are ran and even while (if supported).
- Tasks can be invoked synchronously (blocks until result is returned) and can have a timeout.
- Tasks can be invoked asynchronously (non-blocking)
- Tasks can be grouped and executed in any order (TaskSet)
- Tasks can be grouped and executed in insertion order (TaskList)
- Tasks can be grouped and executed simultaneously (TaskGroup)
- Tasks can be forked to be ran in a separate context
