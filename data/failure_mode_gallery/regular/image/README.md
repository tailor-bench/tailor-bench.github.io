# Failure Mode Definition

## f1: Physical Violation
The generated scene violates basic physical principles or produces interactions that are physically implausible. This includes cases where forces, object behaviors, or interaction dynamics contradict real-world physics (e.g., objects floating without support, tools failing to transfer force, or materials behaving inconsistently with their properties). Even if the scene appears visually plausible, the interaction itself cannot realistically occur.

## f2: Inaccurate Attributes
The generated object does not match the attributes specified in the prompt or required by the task. This may include incorrect shape, size, material, or functional properties of objects. For example, a prompt describing a metal coin may result in an object with incorrect thickness or material appearance, or a required rigid tool may be generated as soft or deformable. Such mismatches prevent the interaction from being evaluated correctly because the underlying object representation is inaccurate.

## f3: Incorret Outcome
The generated interaction fails to produce the expected result specified in the scenario. In these cases, the objects and attributes may be correctly depicted, but the resulting state change is wrong.

# Examples

## f1 (Descriptive). 
The ladle is positioned unrealistically across the pot and bowl, creating an implausible pouring configuration that violates normal physical interaction between the container and the utensil.

## f1 (Predictive). 
The liquid is transferred using an unrealistic geometry where the ladle orientation and flow direction do not follow gravity-consistent motion, indicating a violation of basic physical dynamics.

## f2 (Descriptive). 
The generated scene replaces the required screwdriver with an incorrect object (doorstop), failing to match the specified tool attributes needed for the interaction.

## f2 (Predictive). 
The object interacting with the screw does not correctly match the required tool structure, indicating incorrect object attributes or tool geometry.

## f3 (Descriptive). 
The box remains sealed even though scissors are used, showing that the expected outcome (opening the package) is not realized.

## f3 (Predictive). 
The scissors are present but the box is still unopened, indicating the model fails to produce the correct state change after the interaction.