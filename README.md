# Using the Pandas On Spark API in CML

## Objective

A quick tutorial showing you how to use the Pandas on Spark API in CML.

## Requirements

* A CML Workspace on CML Public or Private Cloud or CDSW
* Basic Python and PySpark knowledge

## Getting Started

#### Step 1:
Crete a new CML Project cloning this GitHub Repository.

#### Step 2:
Launch a CML Session with the following configurations:

```
* Editor: Jupyter Notebook
* Kernel: Python 3.7 or above.
* Edition: Standard
* Enable Sparl: Spark 3.2 or above.
* Resource Profile: 1 CPU / 2 GiB Mem Minimum. No GPU Required.
```

#### Step 3:
Run through the Notebook cells. Detailed instructions explaining each command are included in the comments.

## Conclusion

The Pandas on Spark API offers the following benefits:

* You can run your Pandas code faster.
* You can use the Pandas API with the distributed horsepower of Spark.
* You can have a single codebase for everything: small data and big data.
* The same Pandas syntax is compatible with Dask so you can even more easily choose the engine to run it on now.

When deployed on CML, the Pandas on Spark API is easy to use:

* CML Sessions allow you to easily deploy resources in Kubernetes to execute ML workloads.
* CML Runtimes allow you to switch between programming languages, editors, and preloaded libraries with agility.
* Among these benefits, you can pick which version of Spark to use on the fly. In this example we used Spark 3.2.

If you have any questions about CML or would like to see a demo, please reach out to your Cloudera Account Team or send a message [through this portal](https://www.cloudera.com/contact-sales.html) and we will be in contact with you soon.
