# Pathway Logic Model Builder

Requirements
install pear.phar and graphviz

The project is available on the following link
https://drive.google.com/file/d/1vYHvPwxjdlLaBl003K19CXq_NFz5Mz_Q/view?usp=sharing


## Introduction
Pathway Logic is essential for qualitative analysis and cross talk identification within large pathways. The modeling process
for such analysis requires many computational skills like software installation/ configuring
in Linux, programming etc.
The programming in MAUDE is a time consuming task even for computer professional
as it is not used for general application programming. It has very basic type of compiler
and no dedicated editor for code writing. Its code is usually written in notepad that do
not indicate any errors while writing the code. This kind of errors prevent the models to
execute. The process is also very prone to logical errors and detection of presence of such
errors is very difficult.
Apart from Knowledge base, transition knowledge base is also required. The both
kowledge bases must conform to each other to query the model and to display the results
in PLA. Transition knowledge base is the transformation of rules of knowledge base to
transitions of petri net. This transformation if subjected to error at any stage may corrupt
the integrity of whole process of modeling.
Another difficulty in this type of modeling is synonym/alias handling. Proteins and
other chemicals have many names in literature for single entity. One entity included in
model with different names leads to incorrect and partial analysis. One must be sure that
every entity is modeled with one name in the model.
A big problem arises when extending the present knowledge base to incorporate new
entities and their interactions in the knowledge base. New entities may have interactions
with already present entites so already present interactions needs modification. This is very
challenging and delicate process. This problem becomes worst when one wants to combine
the rule knowledge bases of two or more pathways for combined analysis.
To avoid all these problems extensive literature review and large documentation is required. Even then process is more likely to error prone. Extensive documentation is a
problem in itself. Moreover as the knowledge base grows, its documents also grow large.
New curator must have a good knowledge of existing knowledge base through its documentation.
The biologist usually lacks computational skills so they find the modeling process in
Pathway Logic even more challenging and difficult.
A computer application that may automate the whole process of modeling in pathway
logic can avoid all these problems and make the process very fast.
## Pathway Logic Model Builder
Pathway Logic Model Builder is a computer application that facilitate the process of modeling in pathway logic.
### Source of Chemical Interactions
pathways are available on many sites. These pathways are usually in graphical form and
provide a visual representation of interactions among chemical entities. Every website manage the information about chemical interaction differently. So the retrieval of information
about chemical interactions from these sites is a difficult task.
NCI interaction database is one of the most reliable and updated source of pathways.
PLMB retrieves the information from this website and represent it in interactive graphical
form for user editing and model file generation.

### Model File Generation
As described earlier multiple files are required for pathway logic Model building. PLMB
automatically generates the model files. It not only reduces the model generation time but
also makes it error free.
### Expanding Knowledge Base
Adding new information to existing knowledge base is a challenging task. PLMB allows
user to add single interaction or whole new pathway to existing knowledge base. This way
new individual interaction or entire pathway can be incorporated in existing knowledge
base. Hence the size of knowledge base increases.
### Intuitive GUI
PLMB has an elegant, intuitive GUI. The GUI is very user friendly and self explanatory.
It provide a convenient way to work with models and use the features of PLMB easily. The
self explanatory GUI makes the process of learning PMLB very easy and quick.
### Synonym Handling/Renaming
PLMB incorporates an efficient algorithm for synonym/alias handling and renaming. As
explained earlier, synonyms or aliases of single entity with separate entries in knowledge
base definitely leads to wrong results. PLMB efficiently handles this problem.
Sometimes names of proteins/chemicals used in NCI interaction database is too long or
contain characters that can not be used in PL model files. To counter this problem a built
in renaming facility is provided in PLMB. PLMB itself rename such instances. Moreover
it provides user the facility to rename any protein or chemical present in the model.

### User Editing
PLMB provides the user with editing facility. This includes addition of user specified
protein/ chemical, deletion of already present entity and renaming of some existing entity.
User has a full control to add some chemical entity of its own choice and the change is
reflected in model files. Similarly user can delete any number of protein/ chemical by a
mere click of mouse. These user editing facilities provide a full control of model and user
can gain any abstraction level suitable for its analysis purpose.

### Online Access and User Account Handling
PLMB is cuurently not accessible online. Before using it one must have a user account to use it. Every
registered user has its own customized settings in terms of previous usage of software.
All work done in previous sessions remains intact and available for further analysis and
modeling. In this way every user can work independently without interfering with someone
other’s models.



Develpoed by Muhammad Irfan Khan (RCMS, NUST), Usman Ali Sarwar, Dr. Jamil Ahmed (RCMS, NUST), Azmat Ali khan(RCMS, NUST)
