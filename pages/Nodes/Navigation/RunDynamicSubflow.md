# Run dynamic subflow
Execute a runtime decided flow inside the current flow. Unlike the Run subflow node, it can overwrite which flow to run.

### Node properties
##### FlowId
The identifier of the standard flow to be executed
##### DynamicFlowId
The target flows to run. This overwrites the flowId. Syntax: `Nodes.NodeName`, the node NodeName should be an [Expression](https://github.com/conneqtDocumentation/connectDocumentation/blob/main/Nodes/Expressions/Expression.md) or similar node that contains the identifier for the flow to be executed.
##### Flow.inputs.values
Add input values
##### Outputs
Outputs the output of the executed flow.

# Example:
[Run other flow](https://github.com/conneqtDocumentation/connectDocumentation/blob/main/Nodes/Examples/RunOtherFlow.md)
