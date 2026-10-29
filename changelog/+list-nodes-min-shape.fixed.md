Return `{name: {"id": ..., "state": ...}}` from `list_nodes_min`, so `salt-cloud -m <map>` no longer crashes with "string indices must be integers" when a VM in the map already exists.
