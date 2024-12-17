# Definition of Nodes

This document serves as the manual for various nodes in **Product ChemOrchestra™**. Each node performs specific functions within the computational workflows.

## Workflow Overview

![Screenshot](./img/Index_flow.png)

## Nodes

[Details to be added]

## Edges

[Details to be added]

## General Rules

- For **geometry optimization** and **MD simulation**:
  
  1. All results should be packaged in a list.
  2. The first item in the list must always be the final structure.
  3. The second item in the list must always be the trajectory. If the trajectory size exceeds 100 MB, the second item should also be the final structure.

- Front-end and back-end components are linked using a RESTful API.

- The back-end must:
  
  1. Have one-to-one corresponding node definitions. [**To Do**]
  2. Include validation functions to ensure workflows can execute properly and return the required resources. [**To Do**]


