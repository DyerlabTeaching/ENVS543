# ENVS 543: Environmental Data Literacy

<img align="right" src="dyer.png"> Hello.  My name is Dr. Rodney Dyer and this is a course I've developed to serve as the entry course for incoming Environmental Studies graduate students and advanced undergraduates.  

The rationale for this class is as follows.  

As both a student and instructor in statistics classes, I found I spent a vast amount of time and effort describing the characteristics of statistics (derivations, expectations, etc.).  This is perfectly fine, it is important on many levels to make sure that practitioners understand the basis and context of all the kinds of analyses they use.  However, the drawback here, in my experience, is that once you've spent a semester or year getting all this knowledge under your belt, and one can easily demonstrate their understanding of the parameters in a model, they cannot actually work with real data.  This class is designed to produce practitioners of data analysis.



## Workflow in Data Analysis

To understand data analytics, one needs to recognize the entire workflow.  Below is a brief graphical depiction of how analysis actually works—in the real world.  In this class, we will work on all of these components using the open-source R language.

- **Collect:** Getting data from an external source into a format that you can use is often the most time-consuming step in the analysis.  The content of this class will provide training in data import from local, online, and database sources.  
- **Visualize:** Visualizing data is key to understanding.  In the image below, notice that the variables X and Y in all the displayed data sets have equivalent means, standard deviations, and correlation up to 2 decimal places!  We will emphasize visualization, both static and dynamic, throughout this class.
- **Transform:** Pulling data into your analysis ecosystem is not sufficient.  Often the data need to be reformatted and reconfigured before it is actually usable.
- **Model:**  The application of models to subsets of data is often the step that takes the least amount of time and effort.  However, the application of a model to data is not the endpoint.  The model must be visualized and, many times, the underlying data or derivate data must be transformed and submitted to subsequent models.
- **Communicate:** The effort we put into research and analyses is meaningless without effective communication of your data and findings to a broad audience.  Here we will focus on how to develop effective data communication strategies and formats.

![Common data analysis workflow schematic.  Notice, it is not a linear process, but one that reticualtes back upon itself.](workflow.png)



## Learning Objectives

The purpose of this course is to help you build your data skills and to develop a foundational understanding upon which subsequent courses will build. The overarching goal here is to develop a working knowledge of the R statistical computing language and enough proficiency to import raw data and then iterate through the visualization, manipulation, and analysis steps in the creation of output that is easily communicated to a scientific audience.

The content of this course is built upon the following general student learning objectives (SLO):

- SLO 1: Identity, manipulate, and summarize numerical, categorical, ordinal, logical, date, string, and spatial data types.
- SLO 2: Create habits and took knowledge to support reproducible research.  
- SLO 3: Create an informative and effective graphical display of various data types of suitable quality for inclusion in published manuscripts.
- SLO 4: Effectively choose appropriate statistical models based upon the types of data at hand and the questions being addressed.
- SLO 5: Demonstrate a general understanding of spatial data types and the creation of both appropriate static and dynamic maps.

## Course Content & Assessment

This course is designed as a sequence of individual, stand-alone modules.  Each is self-contained and includes a lecture, slides, a larger narrative document, a video demonstration, and an assessment. 

Deliverable       | Details                                  | SLO  
------------------|------------------------------------------|-----------
Welcome & Logistics | Setting up the logistics for the class |  `NA`
Markdown | Learn to use markdown to mix data, analyses, output, graphics, and reserach narratives | 2
Git & Github | Establish a functional working knowledge of git as a collaborative tool for reproducable research | 2
Data Types | Understanding the fundamnetal data types within R and how to easily import, work with, and export raw data | 1, 2 
Data Containers | Creation, import, and export of vectors, matrices, data.tables, and lists for reliable data representation | 1, 2
Tidyverse | Data manipulation.  Like a boss. | 1, 2
Graphics that DON’T suck | Hello publication quality graphics, using the grammar of graphics approach | 2, 3.
Confidence on a Mean | Base understanding of statistical inferences and the properties of sampled data | 1, 2, 4
Biniomial Inferences | Analyses based upon expectations.  | 4
Categorical ~ f(Categorical) | Contingency table and categorical count data | 4
Continuous ~ f(Categorical) | Analysis of Variance (or equality of means) | 4
Continuous ~ f(Continuous) | Correlation & Regression approaches | 4
Categorical ~ f(Continuous) | Logistic regression | 4
Points, Lines, & Polygons | Spatial data as vectors | 3, 5 
Raster Data | Continuously distributed spatial data | 3, 5
Cartography | Creating usable and understandable maps and symbolic representation of spatial data | 3, 4
Census Data | Human data based upon the US census. | 3,4,5
Raytracing | Higher dimensional visualization of spatial extents.  | 3,5





