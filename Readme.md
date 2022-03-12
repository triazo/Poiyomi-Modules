Poiyomi Modules
===========
A collection of modules I use with poiyomi pro.

## Sakura

A port of [Sakura Bliss](https://www.shadertoy.com/view/ts33DX),
featuring tiling and a mask.

## Chromatic

A port of [Chromatic
Resonance](https://www.shadertoy.com/view/tlySzm), featuring emission,
positioning, and audiolink.


# Installation

As poiyomi version 8 is in alpha, the installation and setup is a bit finnicky
at times, but steps are as follows:

1) Copy the module folder into your poiyomi folder at
	`Assets/_PoiyomiShaders/ModularShader/Editor/Poi_FeatureModules`.
2) Copy the poiPro shader
	`Assets/_PoiyomiShaders/ModularShader/Editor/PoiyomiPro.asset` to
	create a new one (or just modify this one, doesn't matter, in that
	case skip step 3).
3) Change the name and label of your new shader. This is important so
	you can actually select it in the shader selection drop down.
4) Add the new modules to the new shader template, by hitting new and
	selecting the module template.
5) Move the new modules up in the template. I think this affects
	execution order. I put them right after flipbook.
6) Select your new shader!

# Troubleshooting

- If you get an error about template removed or not found, try
  - redoing step 4 above
  - In the downloaded module folders under Poi_FeatureModules, select
    the template and drag the templates from the poiTemplateCollection
    file into the template asses.
