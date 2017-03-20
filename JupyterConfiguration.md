
## [Jupyter Configuration](http://testnb.readthedocs.io/en/stable/examples/Notebook/Configuring%20the%20Notebook%20and%20Server.html)
```shell
jupyter notebook --generate-config
```

## Edit ~/.jupyter/jupyter_notebook_config.py:

 ## The IP address the notebook server will listen on.  
 ```shell
 #c.NotebookApp.ip = 'localhost'  
 ```
To: 
 ```shell
 c.NotebookApp.ip = '*'  
 ```
 
