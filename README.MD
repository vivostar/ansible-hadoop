# Ansible For Apache Hadoop

Ansible role for installing and configuring Apache Hadoop



##  Supported Platforms

- Centos 7.9

    

##  Requirements

* Java 8 / 11

    

##  Role Variables



| Variable            | Default                                                      |
| ------------------- | ------------------------------------------------------------ |
| hadoop_version      | 3.3.2                                                        |
| hadoop_download_url | {{ hadoop_mirror }}/hadoop-{{ hadoop_version }}/{{ hadoop_package }} |
| hadoop_mirror       | https://mirrors.tuna.tsinghua.edu.cn/apache/hadoop/common    |
|                     |                                                              |
|                     |                                                              |
|                     |                                                              |
|                     |                                                              |

