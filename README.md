# hashmap
Implementations of hash maps without using built-in Python data structures.

1. `hash_map_sc.py` handles collisions using linked lists with separate chaining.
2. `hash_map_oa.py` handles collisions using open addressing with quadratic probing.

Guaranteed O(1) time complexities of the following methods:
- `get()`
- `put()`
- `contains()`
- `remove()`
- `clear()`

Additional helper methods include `resize_table()`, `table_load()`, `get_keys_and_values()` and more.
