A template for Sycamore with TailwindCSS
========================================

Requirements:

 - Sycamore: https://sycamore-rs.netlify.app/docs/getting_started/installation
 - Tailwind: https://tailwindcss.com/docs/installation 

This example requires TailwindCSS executable to be in the path.
If you have Node/NPM, use the installation procedure described on TailWindCSS site.
Otherwise, you can simply download the standalone executable provided by TailwindCSS here: https://github.com/tailwindlabs/tailwindcss/releases/latest and add the executable to the path.

Currently this example will only work on Linux/Mac because it requires `sh`.
If you run on Windows and don't use WSL/Docker then you need to adapt Trunk.toml.
The adaptation should be trivial, two commands need to be altered:
 - create an empty `tailwind.css`. This is a workaround for pre-hook file copy
 - run `tailwindcss -mo tailwind.css` to generate the proper `tailwind.css`
