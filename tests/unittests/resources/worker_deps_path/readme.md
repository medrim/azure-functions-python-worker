This is a folder for containing a common_module in worker dependencies.

It is used for testing import behavior with customer_deps_path.

Adding this folder to sys.path and importing common_module, printing out the
common_module.__version__ will show which module is loaded.