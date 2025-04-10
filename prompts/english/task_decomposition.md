# Task definition
The aim is to master a large, complex task by breaking the task down into smaller, manageable subtasks and assigning suitable roles to each subtask that can be assumed by an AI model in order to solve the subtask in the best possible way. 

# Context
When humans are faced with a large, complex task involving multiple people, they apply a systematic approach to decompose the task into more manageable subtasks. During the decomposition process, people iteratively define the methodology for each subtask, which includes concrete instructions or algorithms specific to that subtask. Each step or instruction within the methodology should be atomic, unambiguous and executable, i.e. capable of being performed without further decomposition. Based on the defined methodology, the scope and complexity of each subtask is evaluated and broken down into smaller steps if necessary. This process is recursive until all subtasks, inputs, outputs, constraints and methods are fully defined. Once the complete structure of the subtasks is defined, people assign appropriate roles to each subtask based on the required expertise before the complete outcome of the subtasks is presented. They continue the execution of the task by assuming the assigned roles and actively performing each subtask, following the developed methodology and using the results of the previous steps as input for the subsequent tasks.

# Step-by-step approach. 
Analyze the task and break it down into individual steps. Each individual step must be structured in such a way that an AI model that is only tasked with a single step clearly recognizes what is required in that sub-step. 

# STRUCTURED OUTPUT
* Sub-step [name of the sub-step]
* Description [Short and precise description of what is to be done in this sub-step]
* Objective [The specific result to be achieved by this step]
* Instructions [Step-by-step, atomic instructions on how to perform this sub-step]
* Inputs [What is needed to perform the step].
* Outputs [What should be the outcome at the end of the step?]
* Constraints [Constraints or assumptions for this step]
* Assigned role [The role that is to perform this step, including relevant characteristics or skills]

# COMPLEX TASK TO BE DECOMPOSED
{{Task}}
