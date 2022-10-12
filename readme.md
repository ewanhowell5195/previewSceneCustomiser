# Preview Scene Customiser

Plugin: https://www.blockbench.net/plugins/preview_scene_customiser

## Installing preview scenes

You can install preview scenes from this repository by opening Blockbench, installing the plugin, going to `View > Preview Scene Customiser`, and then clicking `Download Preview Scenes`.

## Submitting your own preview scenes

You can submit your own preview scenes to this repository so that anyone can download them.

1. Create your preview scene, add a texture, and export it through `File > Export > Export Preview Scene`. The texture will be included in the `bbscene` file, it will not be separate.
2. Create a thumbnail image for your preview scene. The image must be `240 x 90` and be in the `webp` format. You can use [this website](https://ezgif.com/png-to-webp) to convert images to `webp`.
3. Create a fork of this repository.
4. Inside the fork, open the `scenes.json` and add your scene, including the `id`, `name`, and `author`. If your scene doesn't fit into one of the existing categories, you can make your own. The icons you can use for categories are listed on [this page](https://www.blockbench.net/wiki/api/blockbench).
5. Inside the `scenes` folder, create a folder with your scenes `id`. If you are using the GitHub website, this can be done by creating a new file and adding it into the file name field along with a file name. Example: `player/scene.bbscene`.
6. Once you are inside your scene folder, upload your `.bbscene` file, and `.webp` file. They must be named `scene.bbscene` and `scene.webp`.
7. Open a pull request and wait for me to review it.
