# Qurator_manual
This manual is suitable to the Qurator, which can guide how to get the software, how to install and use it.

# Build Issues
## 1. If you have your own conf.py file, it overrides Read the Doc's default conf.py. By default, Sphinx expects the master doc to be contents. Read the Docs will set master doc to index instead (or whatever it is you have specified in your settings). Try adding this to your conf.py:

   ### master_doc = 'index'
