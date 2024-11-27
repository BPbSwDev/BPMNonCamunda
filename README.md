# BPMonCamunda
BPM implementations on the Camunda Engine (and the Camunda Modeller) using the BPMN 2.0 language; These example implementations are for academic purposes; initially for undergraduate level, but also for graduate level. 

## Index

1. [Description](#description)
2. [Prerequisites](#prerequisites)
    1. [Environment](#environment)
3. [Tool Usage](#Tool-usage)

## Description

The applications created in this implementation were developed using the Java programming language.

[Java](https://www.java.com/es/) is a versatile and widely used programming language known for its platform independence, robustness, and scalability. With its rich ecosystem of libraries and frameworks, Java enables developers to build complex enterprise-grade applications efficiently and reliably.

[Camunda Modeler](https://camunda.com/download/modeler/) is a desktop application that provides a graphical user interface for designing BPMN and DMN diagrams. It allows users to visually model their business processes and decision tables using drag-and-drop elements, making it easy to create, edit, and analyze process models.

[Camunda Run](https://camunda.com/download/platform-7/) is a lightweight, out-of-the-box distribution of the Camunda BPM process engine, designed to facilitate the implementation and execution of BPMN (Business Process Model and Notation) and DMN (Decision Model and Notation) based processes and decisions.

## Prerequisites

### Environment

To use this program you need the following:

1. **Java 21**: You can get help to download and install the java version by following [this link](https://www.youtube.com/watch?v=oAin-q1oTDw&pp=ygUXY29tbyBjb25maWd1cmFyIGphdmEgMTc%3D)

2. **Camunda Modeler**: you can download to install Camunda Modeler here [official website](https://camunda.com/download/modeler/)

3. **Camunda Run**: you can download to execute Camunda Run here [official website](https://camunda.com/download/platform-7/)

## Tool Usage

To use and deploy any implementation you must:

1. Open the folder ```camunda run``` and execute the field ```start.bat```. 
    ![comando de ejecucion](Img/CamundaRun.png)

2. Open any implementation with the ```camunda modeler```.
   ![comando de ejecucion](Img/OpenCamunda.png)

3. Deploy the BPMN, do not forget to add the FORMs or DMNs required by the model.
    ![comando de ejecucion](Img/DeployBPMN.png)

4. From your favorite browser go to ```localhost:8080``` and there log in with user: demo, password: demo.
    ![comando de ejecucion](Img/Engine.png)

5. After logging in, you can go to the cockpit to view the processes.
    ![comando de ejecucion](Img/Cockpit.png)

6. To create an instance of the process we must go to ```Tasklist```.
    ![comando de ejecucion](Img/Tasklist.png)

7. Here you can create instances of the process.
    ![comando de ejecucion](Img/StartInstance.png)

8. When you want to create an instance you must select which process you want to create.
    ![comando de ejecucion](Img/SelectProcess.png)

9. In order to be able to enter data in the forms, the instance must be claimed.
    ![comando de ejecucion](Img/ClaimInstance.png)

10. Finally, more than one instance of the same process can be created at the same time.
    ![comando de ejecucion](Img/MoreInstance.png)