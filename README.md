# Basics-for-XML

# Behavior Trees & XML Basics
A personal learning repository documenting my progression from learning XML to understanding and creating Behavior Trees for robotics.
The goal is to build a strong understanding of how XML represents Behavior Trees and eventually connect that knowledge to the Python code used to implement the actual behaviors.

## Lessons

### Lesson 1 — XML Basics
Introduces the basic structure and syntax of XML, including:
* XML declarations
* Root elements
* Elements
* Element values/content
* Nesting and hierarchy
* Opening and closing tags
* Comments
* Indentation and formatting

### Lesson 2 — XML Attributes
Builds on the XML basics by introducing:
* Attributes
* Attribute values
* Multiple attributes
* Self-closing elements
* Elements with both attributes and content
  
### Lesson 3 — Introduction to Behavior Trees
Uses the XML knowledge from the first two lessons to begin working with Behavior Trees.
Topics include:
* Behavior Tree hierarchy
* Root nodes
* Sequence nodes
* Fallback nodes
* Parent and child nodes
* `SUCCESS`
* `FAILURE`
* How a Sequence handles its children
* How a Fallback chooses between children
* Creating a basic navigation and recovery Behavior Tree in XML

## Goal
The long-term goal of this repository is to progress from understanding basic XML syntax to being able to:
1. Read existing Behavior Trees.
2. Explain how they work.
3. Create Behavior Trees from scratch.
4. Modify existing Behavior Trees.
5. Understand how XML connects to the underlying Python implementation.
6. Eventually design more complex autonomous behaviors for robotics.

## Why XML?
XML is used to represent the structure and configuration of the Behavior Trees being studied in this project.
XML itself does not execute the behaviors. Instead, the Behavior Tree framework reads the XML and uses the information to construct the tree, while the underlying Python/C++ nodes contain the actual behavior.
## Repository Structure
s repository will continue to grow as new concepts and more advanced Behavior Trees are learned.
