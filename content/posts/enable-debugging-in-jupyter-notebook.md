---
title: "Enable Debugging in Jupyter Notebook"
date: 2021-05-05T14:15:13+08:00
draft: false
---

If you have Jupyter Lab 3.x, the extension is shipped by default. 

Install xeus-python with :

```python
conda install -c conda-forge xeus-python
```

You may need to install Nodejs if required :

`conda install -c conda-forge nodejs`

When you start Jupyter Lab, you should see XPython :

![Launcher](/images/jupyter/Launcher.png)

## Change Kernel to XPython

Use XPython from here on if you want to use the Debugger.  For old notebook, open it up

Kernel --> Change Kernel --> Select Kernel --> Python 3.8 (XPython)

![](/images/jupyter/Kernel.png)

## Turn on Debugger

Once you are in a notebook running in Xpython, you should see the Debugger icon :

![](/Users/Chuky/Documents/Hugo/hugoblog/static/images/jupyter/Enable.png)

Once you turn it on, you should see the Debugger Panel open up on the right hand side :

![Panel](/images/jupyter/Panel.png)

You are all set and ready to go. 