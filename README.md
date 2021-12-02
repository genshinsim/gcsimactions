# gsimactions
Community contributed action lists for [gcsim](https://www.gcsim.app/db), hosted on https://www.gcsim.app/db

# How to Contribute
Contributions are appreciated and encouraged from anyone interested in writing action lists so that the broader community may benefit from them. We would very much prefer submitting action lists as a pull request to this repo, but if you don't know how git works then please feel free to submit them in [our discord server](https://discord.gg/m7jvjdxx7q).

## Action List File Format
Submitted files must be in a TOML file format. Please refer to any of the existing configs in this repo for examples of what those look like, but below we detail the various fields in the configuration files.

### Required Fields
  * title - A short descriptive title for the action list. Use of team names (e.g., National) are discouraged to avoid confusion.
  * author - Your preferred name to be associated with the config.
  * characters - A list of all characters in your sim. Please use the same names that you would use in the action lists (lower case with no spaces).
  * config - Your action list.
  * description - A detailed description of your action list, along with any assumptions required so it runs smoothly. A video of the rotation would also be generally useful. Below are some examples of assumptions that you can add, though none of the below are required:
      * Recommended Rotation Duration - Useful for people who want to sim over a shorter duration so the sim doesn't cut off in the middle of the rotation.
      * Minimum ER requirements - Most rotations are built with some ER requirements in mind.
      * Weapon/Artifact Assumptions - Some weapons like Sac Sword or artifact sets like Instructors can have a pretty big impact on how rotations play out.
      * Recommended Enemy Count - Currently mostly applicable for Beidou, comps heavily reliant on swirls, or certain VV setups, where running the sim on 1 vs. 2 enemies can have a big impact.
      * Rotation specifics - Includes things like the expected ordering of skills, Beidou Q or Xingqiu Q procs, number of vapes, etc.

### Optional Fields
  * tags - A list of tags used to help the search feature on the website perform better. Add whatever you see fit.
  * version - You can use this to keep track of your action list version, if desired
  * Feel free to add any other fields as you feel would be useful into the TOML file, though the site is only currently configured to show a subset of those fields in the main view
