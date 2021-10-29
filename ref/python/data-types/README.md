# data-types

<!-- Insert buttons and diff -->


[![](https://www.tensorflow.org/images/GitHub-Mark-32px.png)View source on GitHub](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/__init__.py)



Wandb has special data types for logging rich visualizations.


All of the special data types are subclasses of WBValue. All of the data types
serialize to JSON, since that is what wandb uses to save the objects locally
and upload them to the W&B server.

## Classes

[`class Audio`](./audio.md): Wandb class for audio clips.

[`class BoundingBoxes2D`](./boundingboxes2d.md): Format images with 2D bounding box overlays for logging to W&B.

[`class Graph`](./graph.md): Wandb class for graphs

[`class Histogram`](./histogram.md): wandb class for histograms.

[`class Html`](./html.md): Wandb class for arbitrary html

[`class Image`](./image.md): Format images for logging to W&B.

[`class ImageMask`](./imagemask.md): Format image masks or overlays for logging to W&B.

[`class Molecule`](./molecule.md): Wandb class for Molecular data

[`class Object3D`](./object3d.md): Wandb class for 3D point clouds.

[`class Plotly`](./plotly.md): Wandb class for plotly plots.

[`class Table`](./table.md): The Table class is used to display and analyze tabular data.

[`class Video`](./video.md): Format a video for logging to W&B.

