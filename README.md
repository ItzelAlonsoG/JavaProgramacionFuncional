# JavaProgramacionFuncional

# Content
- Introduction
- Repository
- Install
- Use
- Information

# Introduction

It is a paradigm, it is a programming style focused on having specific cases to solve, when we talk about this it has a certain relationship with lambdas.
<br/>
<br/>

<div><img src="https://static.javatpoint.com/core/images/method-in-java.png" width ="70%"></div>

Exist two types of functions:
- **Pure function:** deterministic (predictable result). Easy to test. Its result will always be the same by always receiving the same parameters. They do not depend on the context, it will always generate the same result and it will not generate secondary effects, that is, it will not affect input data or other data related to other data flows. They do not depend on the state of the system.
- **Impure function:** Its result will change and generates secondary effects.

**Secondary effect**
<br/>
Any change observable from outside the system is a side effect.

- Read / Create / modify / delete files.
- Read / Write in a database.
- Send / Receive a net call.
- Alter an object / variable used by other functions.

**Lambdas** do come from the lambda calculus and are functions.They start from a mathematical concept from the 1930s and are anonymous functions.

<div><img src="https://image.slidesharecdn.com/java8lambda-lightningtalk-130419141727-phpapp02/95/java-8-lambda-expressions-4-638.jpg?cb=1366381194" width ="70%"></div>



**Streams** in java are a new data model that allows us to treat collections as if they were stages of an ETL (“Extract Transform and Load”) process. This allows us to use the Map and Reduce functions so common in these processes, especially in the transformation stage.

# Repository
This repository contains the project that was developed in the Functional Java course. The purpose is undestand concepts related to the paradigm of functional programming.

- Function
- Filter
- Predicate
- map
- flatMap
- Operators and BiFunction
- Single Abstract Method (SAM)
- Inference
- Lambda
- Deault methods
- Chaining
- Streams
- peek
- skip
- Collectors

# Install

- Install OpenJDK 11
- Install Intellj or another IDE thats supports OpenJDK 11 and contains gandler

To use this repository you need to have the dependencies installed, next clone or download in a .zip the projects.
- Open with your Terminal verified what is the java version you have with, just asegure that it says **openjdk version "11.0.11"**
  -command: java -version 
     <div><img src ="https://i.insider.com/5e2f46d55bc79c3214122a92?width=1000&format=jpeg&auto=webp" width ="800px">  </div>                                                                                                                                                                                                                                                                                  
 - Open Intellij IDE clic on Open project.
   <div><img src ="https://vaadin.com/docs/latest/static/44aa85798d7510627ce48c5b38738da1/03979/welcome-screen.png" width ="800px">  </div>    
  - Select the project to Start this travel in JAVA
# Use
Open the project **IntelliJ** or another IDE what support gradle, for job search you have to use the gradle and select application then run.

# Information
More info in [Platzi course](https://platzi.com/clases/java-funcional/)
