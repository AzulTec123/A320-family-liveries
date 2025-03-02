1. Liveries will be stored in a separate repository. A small number of liveries will be selected to be included with the aircraft.

2. All liveries should be as accurate as possible, within reason, particularly in terms of logos and colours.

3. All liveries must have historically or currently been used on the A320. No fictional liveries will be accepted to the main livery repository. Virtual Airline liveries are one exception, and may be stored in a dedicated part of the repository.

4. The livery should have the correct engine variant and options (wifi antenna, sharklets and so on) of the aircraft which it represents.

5. We will only have one example of each distinct livery of an airline for each different model. Liveries with only small distinctions such as registration number or options will not be accepted. Historical liveries which are clearly distinct (e.g. Landor / Utopia / Union Flag for British Airways) are acceptable.

6. Each livery must be created in 4096*4096 resolution of the paintkit or higher.

7. The livery should be of reasonable quality, particularly, the livery should match up at UV boundaries with no mismatching.

8. The description should be in this format: "Airline Name (Registration, Extra Info). For instance, "Qatar Airways (A7-AHW)"

9. Liveries will be reviewed before being added by a contributor. If you disagree with a rejection, please speak to another contributor. 
10. By asking to publish your livery on our repository, you agree to release your livery under the GNU GPL 2.0 license. You may not port liveries from another simulator without written permission to release under the GNU GPL 2.0 license from the author of the livery.

11. Please also provide the .xcf paintkit, so the livery may be updated in future easily, and therefore does not get lost if any changes happen. 

12. Source files for engines and fuselage have to end on -engine.xcf and -fuselage.xcf respectively


# Installation 
Drag + drop the Liveries folder into your copy of the A320-family

# Repo structure
The .xcf source files live under `Sources/<variant>/<livery>/`.

The final liveries are under `Liveries/<variant>/<resolution>/`.

The .xml files belong into `Liveries/<variant>/`.

## Notes on the canvas livery system.

The A320 is the first to use the improved canvas livery system.

Changes compared to the old livery system:
* The .xml files only reference the file name, no longer the whole file path.
* Each texture goes in the directory according to its size.
* There may be multiple resolutions of the same texture. It gets picked by the system automatically.
