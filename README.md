# Apache Spark

```bash
sudo tar -xvzf spark-3.5.5-bin-hadoop3.tgz

nano ~/.zprofile
```

```bash
export SPARK_HOME="/Users/macos/tools/spark-3.5.5-bin-hadoop3"
export PATH="$SPARK_HOME/bin:$PATH"

export PYSPARK_SUBMIT_ARGS="pyspark-shell"
export PYSPARK_DRIVER_PYTHON=ipython
export PYSPARK_DRIVER_PYTHON_OPTS='notebook' pyspark
```


