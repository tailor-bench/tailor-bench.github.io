# Failure Mode Definition

## F1: Affordance Misgeneralization
The model incorrectly transfers the affordances of one object class to another, resulting in interactions that are semantically recognizable but physically or logically impossible. This manifests as objects being used in ways that disregard their structural integrity, surface geometry, or intended utility.

## F2: Implausible Dynamics
The generated interaction violates realistic physical motion or state transitions. Although the correct objects may be present, their movements or responses do not follow plausible physical dynamics. For example, forces may not propagate correctly, motion trajectories may appear unnatural, or the interaction fails to produce the expected physical effect.

## F3: Interaction Misexecution
The generated video fails to correctly execute the intended interaction described in the prompt. While the relevant objects may appear in the scene, the action is performed incorrectly, incompletely, or in an unintended manner. As a result, the interaction does not lead to the expected outcome or state change.

# Examples

## f1 (Descriptive). 
The prompt specifies using a coin to loosen the screw, but the model fails to execute this affordance; instead of using the coin as a tool to engage the screw head, the interaction is misgeneralized and the intended mechanical operation is not performed.

## f1 (Predictive). 
The book is slammed toward the walnut, but the interaction demonstrates a failure in spatial affordance and contact logic; the hand is seen touching the walnut directly rather than using the book as the intended impact tool, violating the structural requirements of the task.

## f2 (Descriptive).
After the plunger is lifted, a stack of plates suddenly appears in the sink. This is a major object emergence error; the plates were not present under the plunger and appear instantly out of thin air, violating the basic laws of physics and volume.

## f2 (Predictive).
The wine opener's serrated edge never actually penetrates or grips the cork. Instead, the cork magically adheres to the side of the tool and is lifted out. This demonstrates a failure in collision physics and a misunderstanding of how a lever-action tool actually interacts with an object.

## f3 (Descriptive).
This shows a failure in tool-use logic. While the prompt asked to squeeze the lemon with two spoons, the video shows the person holding the spoons under the lemon while squeezing the fruit with their fingers. The spoons act as a redundant platform rather than the active tool for extraction

## f3 (Predictive).
The prompt ask to illustate human attempts to use a paperclip to fix or pull a zipper, but the paperclip never physically attaches to the zipper slider. It merely hovers or slides over the surface without any mechanical connection, failing to perform the intended action.