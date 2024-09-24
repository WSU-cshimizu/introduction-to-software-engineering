# Requirements

## Basic Definitions

* Define what is to be built:
  * Functionality
  * Constraints

Corrolary: _Should not_ define how it is to be built. Which could lead to an implementation that prevents meeting performance or other requirements. Consider, locking in a specific framework, but also locking in specific requirements related to latency that the framework cannot meet.

* Define what it means to be done

-----

## Ambiguity in Language (2/2)

* What makes requirements hard? They may be:
  * Subject to various interpretations
  * Conflicting
  * Inconsistent level of specification
  * Impossible to implement
* Consider the differences:
  * **Shall**: is a contractually required item
  * **Will**: implies intent, not contractually required
  * **May**: a possibility, not contractually required

## Requirements: Subject to Interpretation (Examples)

* The Graphical User Interface (GUI) shall be user friendly.
  * User #1: I like the color scheme of the web page.
  * User #2: I have trouble distinguishing the various buttons on the screen due to their colors.
  * User #3: The average number of clicks to achieve tasks is low, and lower for common tasks.

-----

## Requirements: Conflicting (Examples)

* The GUI shall display a rainbow color background (red on the left to violet on the right) on which text is displayed.
  * All text displayed on a line shall be one color.
  * All text being displayed shall not fade into the background.

-----

## Requirements: Inconsistent Level of Specification (Examples)

* All valid requirements, but different levels of implementation.
  * The system shall allow the user to choose the background color of the screen.
  * The system shall allow the user to choose the color of text being displayed.
  * The system shall detect divide by zero.

-----

## Requirements: Impossible to Implement (Examples)

* Example Requirements:
  * The bootloader shall test all system memory prior to loading the system start up code.
  * The system shall boot within 1 seconds.

* What happens when?
  * Each memory location test takes 1 uS
  * The system has 2 MB of memory

-----

## Requirements: Verification vs Validation (Definitions)

* The verification process ensures that software meets specifications.
* Validation focuses on whether the software meets the expectations and requirements of the end user.
* Validation follows verification.

-----

## Requirements: Verification (Definitions)

* Four basic ways to verify requirements:
  * **Test**: Using controlled defined series of inputs and output to verify the requirement
  * **Demonstration**:  Manipulate the system to show the results meet the requirement
  * **Analysis**: Uses models and calculations to verify the requirement
  * **Inspection**: Examine a product or system for required feature

-----

## Requirements: Verification (Examples)

* Four basic ways to verify requirements:
  * **Test**: Verify that system start up displays initial screen in less than 5 seconds.
  * **Demonstration**:  Show that the displayed window scrolls as expected.
  * **Analysis**: Verify that the data output follows the performance curve of the test model.
  * **Inspection**: Visually examine the system GUIs to assure each screen has a cancel button.

-----

## Requirements: Validation (Example)

* When used by qualified maintenance personal, the diagnostic tool shall isolate 90% of faults to a single subsystem.

-----

## Requirements: Decomposition and Traceability (Definitions)

* **High-level**: system and user requirements
* **Mid-level**: subsystem to configuration items
* **Low-level**: component to unit level
* Trace requirements between the various levels:
  * A single lower-level requirements very seldom fully satisfy a single higher-level requirements
  * There is usually a one to several relationship

-----
