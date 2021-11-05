# Plotly



[![](https://www.tensorflow.org/images/GitHub-Mark-32px.png)View source on GitHub](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/sdk/data_types.py#L2409-L2458)



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

[View source](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/sdk/data_types.py#L2419-L2427)

```python
@classmethod
make_plot_media(
    val: Union['plotly.Figure', 'matplotlib.artist.Artist']
) -> Union[Image, 'Plotly']
```






