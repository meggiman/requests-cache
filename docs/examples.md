# Examples
This section contains some complete examples that demonstrate the main features of requests-cache.

## Articles
Some articles and blog posts that discuss requests-cache:

* PyBites: [Module of the Week: requests-cache for repeated API calls](https://pybit.es/articles/requests-cache/)
* Real Python: [Caching External API Requests](https://realpython.com/blog/python/caching-external-api-requests)
* Thomas Gorham: [Faster Backtesting with requests-cache](https://www.mntn.dev/blog/requests-cache)
* Valdir Stumm Jr: [Tips for boosting your Python scripts](https://stummjr.org/post/building-scripts-in-python/)

## Scripts
The following scripts can also be found in the
[examples/](https://github.com/reclosedev/requests-cache/tree/master/examples) folder on GitHub.

### Basic usage (with sessions)
```{include} ../examples/basic_usage.py
:start-line: 3
:end-line: 4
```

:::{admonition} Example code
:class: toggle
```{literalinclude} ../examples/basic_usage.py
:lines: 1,6-
```
:::

### Basic usage (with patching)
```{include} ../examples/session_patch.py
:start-line: 3
:end-line: 4
```

:::{admonition} Example code
:class: toggle
```{literalinclude} ../examples/session_patch.py
:lines: 1,6-
```
:::

### Cache expiration
```{include} ../examples/expiration.py
:start-line: 2
:end-line: 3
```

:::{admonition} Example code
:class: toggle
```{literalinclude} ../examples/expiration.py
:lines: 1,5-
```
:::

### Logging requests
```{include} ../examples/log_requests.py
:start-line: 2
:end-line: 3
```

:::{admonition} Example code
:class: toggle
```{literalinclude} ../examples/log_requests.py
:lines: 1,5-
```
:::

### Cache speed test
```{include} ../examples/benchmark.py
:start-line: 2
:end-line: 3
```

:::{admonition} Example code
:class: toggle
```{literalinclude} ../examples/benchmark.py
:lines: 1,5-
```
:::

### Converting an old cache
```{include} ../examples/convert_cache.py
:start-line: 2
:end-line: 4
```

:::{admonition} Example code
:class: toggle
```{literalinclude} ../examples/convert_cache.py
:lines: 1,6-
```
:::

(custom_keys)=
### Custom cache key function
```{include} ../examples/custom_cache_keys.py
:start-line: 2
:end-line: 15
```

:::{admonition} Example code
:class: toggle
```{literalinclude} ../examples/custom_cache_keys.py
:lines: 1,17-
```
:::