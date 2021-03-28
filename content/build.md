Build
=====

The primary function of an engineering organization is to create their product. There are a lot of roles and titled individuals involved in that process, but there is a fixed set of ingredients that go into the creation of a product.

Additionally, there are specific stages that the product passes through to become a final product. The death of the Waterfall model of development and subsequent rise of Agile has led to demise of the stage-wise thinking of the development of technological products. 

These stages still exist and we must reckon with them as distinct opportunities to guardrail the way we build the product. 

It's not what you build; it's how you build it.

## BMD Grid

We propose the following grid as a tool to design and define the ideals for building a software product:

|           | Planning | Development | Pre-push | Pre-merge | Post-merge | Integration |
|-----------|----------|-------------|----------|-----------|------------|-------------|
| **People**    |          |             |          |           |            |             |
| **Processes** |          |             |          |           |            |             |
| **Tools**     |          |             |          |           |            |             |

This can easily be represented either as a real-life or virtual whiteboard. With this board, individuals or teams can define
1. **People**: define the specific people or activities involving human roles that can be applied at a specific stage of the engineering journey
2. **Processes**: define the processes that should be applied at specific points in the progression from raw material to finished software product
3. **Tools**: identify tools that can be applied to the product as it moves along the assembly line of software engineering.

The motivation is to provide a visual, structured approach that will help with the timely identification of opportunities to improve the process of developing the product. It’s also particularly useful for collaborative purposes, where any number of individuals can contribute their ideas in a structured manner. 

An ideal representation of all the ingredients that go into a product will see more items to the left of the board than the right; a rough indication of higher preparedness, in line with the Shift-Left ideology.

Having this structure, ingredients and stages, an engineering culture should prioritize the following goals.

 ### 1. [De-risking](derisk.md)
 ### 2. [Engineer Comfort](comfort.md)


### Measurement
It should be possible to obtain metrics associated with how we build our products. These metrics can directly or indirectly provide a sense of what the Build pillar is contributing to the culture. It’s reasonable to expect that metrics associated with the tools and processes applied to the Build pillar will be useful as measurements of this aspect of the culture. For example:

- Your choice and use of build and static analysis tools and your organization’s interpretation of their associated metrics are a proxy for measuring the code aspect of your engineering culture.
- Your use (or lack of) monitoring and alerting tools, incident response times and Mean Times to Resolution would be an indicator of how your organization handles operations and support activities
- Your engineers’ perception of the state of the three ingredients (people, processes and tools) is an indicator of the health of the Build pillar of your engineering culture

All told, one can use metrics attached to specific build ingredients as proxies for the general state of the Build guardrail. 
