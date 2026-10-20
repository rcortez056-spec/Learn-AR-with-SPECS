# FocusFlow: Minimalist AR HUD

FocusFlow is a minimalist, non-intrusive heads-up display (HUD) configuration designed for smart eyewear to maximize deep work, reduce cognitive load, and provide real-time ambient micro-guidance without obstructing the natural field of view.

## Repository Structure

* `focusflow.yaml`: Contains the core configuration parameters for the HUD, including normalized display boundaries, safe bounds, dynamic brightness scaling, and peripheral UI layout specs.

## Features

* **Normalized Safe Bounds:** Keeps the central field of view completely clear while placing ambient indicators in the user's peripheral vision.
* **Ambient Adaptability:** Automatically scales brightness parameters based on real-world lighting conditions.
* **Non-Intrusive Design:** Focuses on minimal, high-contrast layouts to minimize cognitive fatigue during deep work sessions.

## Built With

* Lens Studio
* CLAD Plugin
* Relevance AI (for configuration architecture)
## Technical Architecture & State Logic

* **Micro-Guidance State Logic:** Dynamically updates peripheral UI cues based on active workload state, ensuring indicators provide subtle feedback without fracturing deep work concentration.
* **Dynamic Scaling Parameters:** Leverages `focusflow.yaml` to govern real-world lighting adaptations, maintaining high-contrast readability across variable environments without visual clipping.

## Quick Start & Integration

1. Initialize the Lens Studio project using the base SPECS template.
2. Load the configuration parameters defined in `focusflow.yaml` to map normalized display boundaries and safe bounds[cite: 3].
3. Run local validation tests to verify non-intrusive peripheral placement.
