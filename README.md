# sourmash_plugin_xyz: a template for sourmash plugins

This is a good place to start if you're writing a plugin for
[sourmash (sourmash-bio/sourmash/)](https://github.com/sourmash-bio/sourmash/).

Note: for now, depends on
[sourmash#2428](https://github.com/sourmash-bio/sourmash/pull/2428).

## Instructions

Use this repo as a template repo to create a new plugin.

Next, search for all places where 'xyz' is present, and replace
'xyz' with the name of your plugin.

Edit the code in `src/sourmash_plugin_xyz.py` to write the plugin
(you'll probably want to change the name of that file, too.)

Then run `pip install .` to install and test your plugin! You can also
run `pip install -e .` to install it in editable mode, which is more
convenient for development.
