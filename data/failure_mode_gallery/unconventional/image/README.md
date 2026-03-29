# Failure Mode Definition

## F1: Affordance Misgeneralization
The model fails to correctly apply the unconventional tool specified in the prompt and instead falls back to a biased, familiar tool–task association. Although the unconventional object may appear in the scene, the interaction still follows a memorized canonical pattern rather than reasoning about the substitute tool’s functional affordances.

## F2: Incorrect Outcome
The generated interaction fails to produce the expected result specified in the scenario. In these cases, the objects and their attributes may be correctly depicted, but the resulting state change is incorrect or missing.

## F3: Physical Violation
The generated scene violates basic physical principles or produces interactions that are physically implausible. This includes cases where forces, object behaviors, or interaction dynamics contradict real-world physics (e.g., objects floating without support, tools failing to transfer force, or materials behaving inconsistently with their properties). Even if the scene appears visually plausible, the interaction itself cannot realistically occur.

# Examples

## F1 (Descriptive)
The zipper is shown being operated using a paperclip instead of the intended tool. While the substitute object appears visually similar.

## F1 (Predictive)
A book is used to strike a nail, but the interaction mimics the canonical hammering pattern rather than adapting to the physical properties of the unconventional tool. This reflects reliance on memorized tool–task templates.

## F2 (Descriptive)
A knife is used to open a wine bottle, yet the cork remains inserted, indicating that the expected outcome (removing the cork) does not occur despite the interaction being depicted.

## F2 (Predictive)
A note is pinned using a thin stick, but the stick fails to properly secure the paper to the board, showing that the intended state change is not achieved.

## F3 (Descriptive)
A ladle is shown suspended above a bowl while pouring soup, with the utensil appearing unsupported and violating realistic physical positioning.

## F3 (Predictive)
A coin is inserted into a remote control battery compartment in an implausible way that does not correspond to the device’s physical structure, violating realistic object interaction constraints.