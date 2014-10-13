# Feedback
Score: 95
* How many developers are involved? To what degree?
* The number of files seems very large. I don't believe that those are all source
* It is "src2srcml" and "srcml2src". In the clients, the ML is not capitalized
* The "srcML" application, is "srcml". Use "srcML" for the format and general toolkit, framework, etc., and "srcml" in the tool names
* 
### srcML - Software Stage Profile

#### What is srcML?
srcML is an XML markup format that encompasses source code for the purposes of providing exploration, analysis, and manipulation opportunities on source code. Since srcML is based on standard XML, all existing XML  tools and technologies are supported by default. In addition, an application called srcML was developed to facilitate the parsing of source code both to the srcML markup and back to the original source code. Along with the parsing, the srcML application also allows for the execution of queries or transformations of source code in the srcML format natively in the application as well. The project is rooted in research based applications, but the markup format and application have proven to be useful in multiple industrial applications for practical software development.

#### Initial Development
Originally, the srcML application was comprised of two forward facing command line applications named src2srcML and srcML2src. Each application would perform the respective tasks of parsing source into srcML and back from srcML to source respectively as well as additional options and features associated with the source code or srcML format. According to the change logs online, the initial trunk version 7481 was released on 8/18/2011. While the next four subsequent releases were focused on bug fixes, additional features were added to the majority of all subsequent releases of the srcML application starting with trunk version 13925 released on 05-17-2012 and continuing to the present.

#### Present Development Stage
 In addition to features and enhancements, the project is the the process of large restructuring that began in 2013. The intent of this new approach to srcML development is to split srcML from being only a command line application to a full fledged platform complete with a library API called libsrcml and a new unified command line interface simply called srcML to provide the functionality of both of the previous src2srcML and srcML2src clients. This large development shift places the srcML project cleanly into the evolutionary stage of development, and a roadmap of potential features including additional projects based on libsrcml and the additional of supporting more source code languages or domain specific languages via a plug-in architecture help to ensure that the project will remain on an evolutionary path so long as project resources remain available (funding, staff, etc.). In it's present state the srcML project has 12,430 commits and 1,092 files totaling 324,277 LOC. The previous version of srcML is now considered legacy and is in the phase out stage, which will most likely shift to close down once the new client leaves beta and is publicly released.

#### Driving Factors
The srcML project was born from academic research, and was initially featured in the 2002 paper "Source Code Files as Structured Documents" featured in the IWPC '02 Proceedings of the 10th International Workshop on Program Comprehension. One year later, another research paper "An XML-Based Lightweight C++ Fact Extractor" featured in the 2003 11th IEEE International Workshop on Program Comprehension Conference would go on to be awarded most influential paper at the  2013 21st IEEE International Conference on Program Comprehension (ICPC'13) May 20-21. The high quality research potential of the project has earned a three year $800K grant from the National Science Foundation (NSF)  which has been a large factor in the continued and increased development activity of the srcML project.
