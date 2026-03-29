# Failure Mode Definition

## F1: Physical Violation
The generated scene violates basic physical principles or produces interactions that are physically implausible. This includes cases where forces, object behaviors, or interaction dynamics contradict real-world physics (e.g., objects floating without support, tools failing to transfer force, or materials behaving inconsistently with their properties). Even if the scene appears visually plausible, the interaction itself cannot realistically occur.

## F2: Instruction Adherence Failure
The generated image fails to follow the instruction or prompt specification. Key objects, attributes, or relationships described in the prompt are missing, incorrect, or substantially altered, resulting in a scene that does not match the intended interaction.

## F3: Incorrect Outcome
The generated interaction fails to produce the expected result specified in the scenario. In these cases, the objects and their attributes may be correctly depicted, but the resulting state change is incorrect or missing.

# Examples

## F1 (Descriptive)
A slice of bread is shown inserted around the neck of a wine bottle in an attempt to remove the cork. However, the cork remains fully inserted, and the soft bread appears incapable of generating sufficient force or leverage to extract it, making the interaction physically implausible.

## F1 (Predictive)
An ice cube is shown being used to pin a note to a board. Because ice lacks rigidity and melts over time, it cannot realistically function as a fastening object to secure the paper.

## F2 (Descriptive)
A cork is shown placed next to a sliced tomato instead of interacting with it as described in the instruction. Although both objects appear in the scene, the intended interaction specified by the prompt is not depicted.

## F2 (Predictive)
A cork and a tomato are shown side by side without any action being performed. The generated scene fails to follow the prompt describing how the cork should be used in the interaction.

## F3 (Descriptive)
A walnut is shown cracked open on a couch cushion, leaving debris scattered across the fabric. But using pillow should not be able to open it.

## F3 (Predictive)
A car window is shown shattered while a person inside the vehicle holds a lightweight plastic water bottle. Although the bottle is present, it is implausible that such an object could have caused the damage, indicating that the resulting state change is incorrect.