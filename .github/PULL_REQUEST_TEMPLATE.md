## Addon submission

- Addon name and repository:
- Author approval for inclusion in Reborn:
- Tested Reborn client / result:
- Release ZIP and expected folders:

Add one manifest as addons/<id>.toml. Optional icon field:

~~~toml
icon = "assets/icon.png"
~~~

Use a path in the addon repository, with forward slashes. Omit icon or use
icon = "" if no icon is available. See examples/addon.toml.
