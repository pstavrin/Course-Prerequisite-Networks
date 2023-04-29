# Course-Prerequisite-Networks
This repository contains the dataset used to run all numerical experiments and visualizations of the following paper on Course Prerequisite Networks (CPNs): https://doi.org/10.1007/s41109-023-00543-w#


All data is contained in the file: <code>2021-22-course-prereqs - clean.csv</code>.
 The spreadsheet contains the following columns:
* <code>department_name</code>: The area (department) that offers the respective course
* <code>acronym</code>: The shorthand name for the respective department used by the university
* <code>course_number</code>: The course number as listed in the university catalog
* <code>node_name</code>: The name of the node, as it appears in our network, corresponding to the course name and number as found in the university catalog
* <code>course_title</code>: The course title as it appears in the university catalog
* <code>prerequisites</code>: The course prerequisites as they appear in the university catalog
* <code>prerequisites_clean</code>: The course prerequisites listed as nodes in our network
