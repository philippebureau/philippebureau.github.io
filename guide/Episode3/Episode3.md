# Episode 3 - Underlay






3. Spanning-tree

We want our spines to be the spanning-tree roots and use MSTP.  We will use the `spanning_tree_mode` and `spanning_tree_priority` from the [Node type L2 and MLAG configuration](https://avd.arista.com/6.1/ansible_collections/arista/avd/roles/eos_designs/docs/data-models.html#node-type-l2-and-mlag-configuration) data-model.

```yaml
l3spine:
  defaults:
    spanning_tree_mode: mstp
    spanning_tree_priority: 4096
```