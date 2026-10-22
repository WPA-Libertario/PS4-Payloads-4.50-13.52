These binary files, located within the `fan-thresholds` folder, are used to modify the target temperature profile (threshold) for the PlayStation 4's APU. They control the exact temperature at which the console begins to ramp up the fan speed to dissipate heat.

A lower temperature setting results in more aggressive and louder fan operation to keep the console cool; a higher temperature setting makes the console quieter, but causes the components to run hotter.

Here is a detailed description of each file:

---

- `ps4-fan-threshold60.bin`
- Function: Sets the temperature threshold to 60°C.
- Effect: This is the maximum cooling profile. The fan will run at very high speeds almost constantly to prevent the console from exceeding 60°C.
- Recommended use: Ideal for very hot climates or rooms without air conditioning, or if you want to maximize the lifespan of the internal components—at the cost of significant fan noise.

- `ps4-fan-threshold70.bin`
- Function: Sets the temperature threshold to 70°C.
- Effect: This is a balanced profile. It allows the console to reach a moderate temperature before the fan begins to spin at higher speeds.
- Recommended use: Well-suited for everyday use, as it offers a reasonable middle ground between the console's thermal health and an acceptable noise level during gaming sessions.


- Function: Sets the temperature threshold to 80°C.
- Effect: This profile prioritizes silence. It allows the APU to get quite hot (up to 80°C) before the system triggers more aggressive cooling. This is similar to the default, factory-set behavior found on many PS4/PS4 Pro models.
- Recommended use: Useful if you play using headphones and find the fan noise bothersome—provided the console has adequate external ventilation.
  
- `ps4-fan-threshold85.bin`
- Function: Sets the temperature threshold to 85°C.
- Effect: This is the most permissive and quietest profile. The console will allow its components to reach up to 85°C before the fan ramps up to its maximum speed.
- Recommended use: *Use with caution.* If the thermal paste in your console is dried out or in poor condition, this profile could cause the PS4 to approach the thermal protection limit (thermal throttling) dangerously closely. Therefore, it is only recommended if the console has recently been cleaned and had its thermal paste replaced.
