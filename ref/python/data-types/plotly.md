# Plotly



[![](https://www.tensorflow.org/images/GitHub-Mark-32px.png)View source on GitHub](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/sdk/data_types.py#L2409-L2458)



Wandb class for plotly plots.

```python
Plotly(
    val: Union['plotly.Figure', 'matplotlib.artist.Artist']
)
```





| Arguments |  |
| :--- | :--- |
|  `val` |  matplotlib or plotly figure |



## Methods

<h3 id="make_plot_media"><code>make_plot_media</code></h3>

[View source](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/sdk/data_types.py#L2419-L2427)

```python
@classmethod
make_plot_media(
    val: Union['plotly.Figure', 'matplotlib.artist.Artist']
) -> Union[Image, 'Plotly']
```






