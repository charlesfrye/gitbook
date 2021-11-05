# File



[![](https://www.tensorflow.org/images/GitHub-Mark-32px.png)View source on GitHub](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L2224-L2327)



File is a class associated with a file saved by wandb.

```python
File(
    client, attrs
)
```







| Attributes |  |
| :--- | :--- |



## Methods

<h3 id="delete"><code>delete</code></h3>

[View source](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L2307-L2320)

```python
delete()
```




<h3 id="download"><code>download</code></h3>

[View source](https://www.github.com/wandb/client/tree/341e249f17302703b79544d82bd382af88498cb9/wandb/apis/public.py#L2284-L2305)

```python
download(
    root=".", replace=(False)
)
```

Downloads a file previously saved by a run from the wandb server.


| Arguments |  |
| :--- | :--- |
|  replace (boolean): If `True`, download will overwrite a local file if it exists. Defaults to `False`. root (str): Local directory to save the file. Defaults to ".". |



| Raises |  |
| :--- | :--- |
|  `ValueError` if file already exists and replace=False |





