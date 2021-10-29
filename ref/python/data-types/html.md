# Html



[![](https://www.tensorflow.org/images/GitHub-Mark-32px.png)View source on GitHub](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/sdk/data_types.py#L954-L1044)



Wandb class for arbitrary html

```python
Html(
    data: Union[str, 'TextIO'],
    inject: bool = (True)
) -> None
```





| Arguments |  |
| :--- | :--- |
|  `data` |  (string or io object) HTML to display in wandb |
|  `inject` |  (boolean) Add a stylesheet to the HTML object. If set to False the HTML will pass through unchanged. |



## Methods

<h3 id="inject_head"><code>inject_head</code></h3>

[View source](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/sdk/data_types.py#L996-L1011)

```python
inject_head() -> None
```






