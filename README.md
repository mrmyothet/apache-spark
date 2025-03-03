# Apache Spark

```bash
sudo tar -xvzf spark-3.5.5-bin-hadoop3.tgz

nano ~/.zprofile
```

### Update ./zprofile

```bash
export PATH="/opt/anaconda3/bin:$PATH"

export SPARK_HOME="/Users/macos/tools/spark-3.5.5-bin-hadoop3"
export PATH="$SPARK_HOME/bin:$PATH"

alias notebook='jupyter-notebook'

export PYSPARK_SUBMIT_ARGS="pyspark-shell"
export PYSPARK_DRIVER_PYTHON="jupyter"
export PYSPARK_DRIVER_PYTHON_OPTS="notebook"

export JAVA_HOME="/Library/Internet Plug-Ins/JavaAppletPlugin.plugin/Contents/Home"
```


