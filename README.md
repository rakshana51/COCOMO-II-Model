# COCOMO-II-Model
COCOMO II (Constructive Cost Model II) is a software cost estimation model developed by Barry Boehm in the 1990s as an extension of his earlier COCOMO model (COCOMO I). COCOMO II is designed to help project managers and software developers estimate the cost, effort, and duration required to develop a software project.

The estimation of effort is done by object points. The object point is an indirect software measure that is computed screens, reports, and components likely to be required to build the application. Object Points (OP) is a software estimation technique that focuses on the functional size of a software application. Each object instance is classified into one of three complexity levels. 

The object point count is calculated by multiplying the original number of object instances by the complexity weight. When component/software reuse to be applied,  percent of reuse is estimated and object point count is updated as: New object points = Object points * ((100-reuse%)/100). Productivity rate for different levels of developer experience and development environment maturity is given by the following table.
![Untitled-document-12](https://github.com/rakshana51/COCOMO-II-Model/assets/142418517/eb7dc144-9a85-4025-9dda-b2f4a143e725)

Once the productivity rate has been determined, an estimate of project effort is computer as: Estimated effort = New object points/Productivity rate.
