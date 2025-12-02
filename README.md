# PP!Notes
An unreleased Obsidian plugin that serves as the sequel of my previous plugin: **Performium**

# What does it do?
This plugin adds ribbons that help you calculate the performance points of each note. It also aims to pair with other plugins whether possible.

This only adds the famous performance points (short for pp) system from the free-to-play rhythm game: **osu!**

# Why make a sequel?
I cannot maintain Performium anymore, so expect calculation bugs that occur on that plugin when attempting to use the systems.

As of Performium pre-1.7.0 (unreleased), the current, previous and upcoming systems are bugged to certain points. Because of this, the development of that plugin will be ceased.

Now with PP!Notes, this plugin will attempt to renew the performance points system inside it. Expect more bugs when calculating with this plugin.

# How would it be calculated?
This is one question that takes me a very long time to think about. Here are some following concepts and processes in calculating:

!. Variables and constants are prepared for calculation.

2. The following performance components are calculated:
  - Content: The notes, folders and other files inside the vault.
  - Accuracy: Words should be related and understandable.
  - Strain: The unique and complex words calculated in the vault.
  - Age: The age of the vault, which includes the time it was created.


3. Once they're all calculated, raw values will be outputted onto the console, and balancing is done to prevent outputting unusual values as results.

4. After the balancing, the value is outputted inside a modal used to display the contents.

# Suggestions?
While the plugin is in development, consider making a suggestion through the issues tab.

# Compiling?
Instructions will be provided here as soon as the first version comes out.
