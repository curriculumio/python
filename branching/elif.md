Notice how in the example on the right, the condition `eggs >= 1` was `True`, so it performed the indented block and did not check any of the subsequent `elif` conditions. If the condition is `False`, then the next `elif` condition is evaluated, and its indented block performed if the condition is `True`.

For example, we could rewrite the example on the right as:

```python
if eggs >= 6:
	print("You can bake a cake.")
elif eggs >= 2:
	print("You can cook an omelette.")
elif eggs >= 1:
	print("You can cook it sunny side up.")
```
