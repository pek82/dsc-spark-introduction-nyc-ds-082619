
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 38 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

## Big Data in PySpark

Big Data is undoubtedly one of the most hyped terms in data science these days. Big Data Analytics involves dealing with data that is big in volume and high in variety and velocity, making it challenging for data scientists to run their routine analysis activities. In this section you learn the basics of dealing with big data through parallel and distributed computing. In particular, you will be introduced to Apache Spark, an an open-source distributed cluster-computing framework. You'll learn how to use the popular Apache Spark Python API, **PySpark**.

### Parallel and Distributed Computing with Map-Reduce

Before diving into PySpark, we start this section by providing more context on the ideas of parallel and distributed computing and Map-Reduce. When talking about distributed and parallel computing, we refer to the fact that complex (and big) data science tasks can be executed over a cluster of interconnected computers instead of on just one machine. You'll learn that Map-Reduce allows us to convert these big datasets into sets of Tuples as key:value pairs, as we'll cover in more detail in this section.


### Apache Spark

As mentioned before, Apache Spark makes the use of huge amounts of data easier (and feasible)! You'll read a scientific article on the advantages of Apache Spark to understand its use and benefits better.

### Installing and Configuring PySpark with Docker

A big part of PySpark is actually getting PySpark up and running on your machine. You'll get an overview of how to do this so you can get started exploring distributed computing!

### PySpark

You'll quickly learn that working with PySpark goes along with some new concepts that haven't been introduced yet. You need to start with creating a Spark Session (also known as a Spark Context), and will learn about the context attributes and methods. 


### RDDs (Resilient Distributed Datasets)
Resilient Distributed Datasets (RDDs) are the core concept in PySpark. RDDs are immutable distributed collections of data objects. Each dataset in RDD is divided into logical partitions, which may be computed on different computers (so-called "nodes") in the spark cluster. In this section, you'll learn how RDDs in Spark work. Additionally, you'll learn that RDD operations can be split into actions and transformations. 

### Word Count with Map-Reduce

At the end of the day, you'll use Map-Reduce to solve a basic NLP task: counting stop words, and keeping word frequency.

## Summary

In this section, you'll learn the foundations of NLP and different technicues to make a computer understand text!
