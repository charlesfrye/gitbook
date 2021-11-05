# Project



[![](https://www.tensorflow.org/images/GitHub-Mark-32px.png)View source on GitHub](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L1178-L1213)



A project is a namespace for runs.

```python
Project(
    client, entity, project, attrs
)
```







| Attributes |  |
| :--- | :--- |



## Methods

<h3 id="artifacts_types"><code>artifacts_types</code></h3>

[View source](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L1211-L1213)

```python
artifacts_types(
    per_page=50
)
```




<h3 id="display"><code>display</code></h3>

[View source](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L748-L759)

```python
display(
    height=420, hidden=(False)
) -> bool
```

Display this object in jupyter


<h3 id="snake_to_camel"><code>snake_to_camel</code></h3>

[View source](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L744-L746)

```python
snake_to_camel(
    string
)
```




<h3 id="to_html"><code>to_html</code></h3>

[View source](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L1195-L1203)

```python
to_html(
    height=420, hidden=(False)
)
```

Generate HTML containing an iframe displaying this project




