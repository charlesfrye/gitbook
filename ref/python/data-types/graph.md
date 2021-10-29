# Graph



[![](https://www.tensorflow.org/images/GitHub-Mark-32px.png)View source on GitHub](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/data_types.py#L1281-L1441)



Wandb class for graphs

```python
Graph(
    format="keras"
)
```




This class is typically used for saving and diplaying neural net models.  It
represents the graph as an array of nodes and edges.  The nodes can have
labels that can be visualized by wandb.

#### Examples:

Import a keras model:
```
    Graph.from_keras(keras_model)
```



## Methods

<h3 id="add_edge"><code>add_edge</code></h3>

[View source](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/data_types.py#L1367-L1371)

```python
add_edge(
    from_node, to_node
)
```




<h3 id="add_node"><code>add_node</code></h3>

[View source](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/data_types.py#L1353-L1365)

```python
add_node(
    node=None, **node_kwargs
)
```




<h3 id="from_keras"><code>from_keras</code></h3>

[View source](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/data_types.py#L1373-L1402)

```python
@classmethod
from_keras(
    model
)
```




<h3 id="pprint"><code>pprint</code></h3>

[View source](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/data_types.py#L1347-L1351)

```python
pprint()
```




<h3 id="__getitem__"><code>__getitem__</code></h3>

[View source](https://www.github.com/wandb/client/tree/ae78783f1c183faca3c2a866b2aa25dbe4219ad7/wandb/data_types.py#L1344-L1345)

```python
__getitem__(
    nid
)
```






