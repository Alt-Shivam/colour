Utilities
=========

Common
------

``colour``

.. currentmodule:: colour

.. autosummary::
    :toctree: generated/

    domain_range_scale
    get_domain_range_scale
    set_domain_range_scale


``colour.utilities``

.. currentmodule:: colour.utilities

.. autosummary::
    :toctree: generated/
    :template: class.rst

    CacheRegistry

.. currentmodule:: colour.utilities

.. autosummary::
    :toctree: generated/

    CACHE_REGISTRY
    handle_numpy_errors
    ignore_numpy_errors
    raise_numpy_errors
    print_numpy_errors
    warn_numpy_errors
    ignore_python_warnings
    attest
    batch
    disable_multiprocessing
    multiprocessing_pool
    is_matplotlib_installed
    is_networkx_installed
    is_opencolorio_installed
    is_openimageio_installed
    is_pandas_installed
    is_sklearn_installed
    is_tqdm_installed
    is_trimesh_installed
    required
    is_iterable
    is_string
    is_numeric
    is_integer
    is_sibling
    filter_kwargs
    filter_mapping
    first_item
    copy_definition
    validate_method
    optional

Array
-----

``colour.utilities``

.. currentmodule:: colour.utilities

.. autosummary::
    :toctree: generated/
    :template: class.rst

    MixinDataclassFields
    MixinDataclassIterable
    MixinDataclassArray
    MixinDataclassArithmetic

.. autosummary::
    :toctree: generated/

    as_array
    as_int
    as_float
    as_int_array
    as_float_array
    as_int_scalar
    as_float_scalar
    set_default_int_dtype
    set_default_float_dtype
    to_domain_1
    to_domain_10
    to_domain_100
    to_domain_degrees
    to_domain_int
    from_range_1
    from_range_10
    from_range_100
    from_range_degrees
    from_range_int
    closest_indexes
    closest
    interval
    is_uniform
    has_only_nan
    in_array
    tstack
    tsplit
    row_as_diagonal
    orient
    centroid
    fill_nan
    ndarray_write
    zeros
    ones
    full
    index_along_last_axis

Metrics
-------

``colour.utilities``

.. currentmodule:: colour.utilities

.. autosummary::
    :toctree: generated/

    metric_mse
    metric_psnr

Data Structures
---------------

``colour.utilities``

.. currentmodule:: colour.utilities

.. autosummary::
    :toctree: generated/
    :template: class.rst

    CaseInsensitiveMapping
    LazyCaseInsensitiveMapping
    Lookup
    Node
    Structure

Verbose
-------

``colour.utilities``

.. currentmodule:: colour.utilities

.. autosummary::
    :toctree: generated/

    message_box
    show_warning
    warning
    filter_warnings
    suppress_warnings
    numpy_print_options
    describe_environment

**Ancillary Objects**

``colour.utilities``

.. currentmodule:: colour.utilities

.. autosummary::
    :toctree: generated/
    :template: class.rst

    ColourWarning
    ColourUsageWarning
    ColourRuntimeWarning
