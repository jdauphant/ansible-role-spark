ansible-role-spark
==================

Ansible role to manage Spark

```
spark_repository: "https://github.com/apache/spark.git"
spark_version: "v1.1.0" #can be git tags/commit/branch
spark_install_dir: "/opt/spark-{{spark_version}}"
spark_link_dir: "/opt/spark"
spark_compile_options: "-Phive -Pyarn"
spark_user: "spark"
spark_group: "{{spark_user}}"
```
