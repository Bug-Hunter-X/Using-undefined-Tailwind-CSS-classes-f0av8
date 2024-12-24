# Using Undefined Tailwind CSS Classes

This repository demonstrates a common error in Tailwind CSS: using classes that are not defined in your configuration.

## Problem

If you use a Tailwind CSS class that doesn't exist (either because you misspelled it, forgot to include the plugin, or it's not included in your `tailwind.config.js` file's `content` array), your CSS will not apply correctly.

## Solution

1. Double-check the class name for typos.
2. Ensure the class is defined in your Tailwind configuration. You need to include the necessary plugin or add the class name to `content` array in the `tailwind.config.js` file. 
3. Clear your browser's cache or restart your development server after making changes to `tailwind.config.js`. 
4. If using a custom plugin, make sure it's correctly configured and imported.

This repository illustrates how such errors occur and how they can be solved.