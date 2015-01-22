**Unit 5: Software Requirements Analysis** <span id="5"></span> 
*Requirements elicitation requires the software engineer to interact
with the stakeholder including customer users,to gather information
about what the software system needs to do. In this unit, we examine the
software engineer’s activities to elicit, to analyze (or translate), to
validate and to manage this phase of the life cycle in working with the*
*customerto achieve a common understanding of the* *customer’s goals.
This set of activities is referred to as analysis and focuses on what
the application will do, whereas design describes how the application
will work (*Unit 6: Software Design*). There are many ways to elicit and
analyze* *customerrequirements. As introduced in subunit 1.2, the three
most commonly used methodologies are data-oriented, process-oriented,
and object-oriented. In this unit, we will drive deeper and examine the
conceptual foundations, activities, and deliverables underlying each of
these methodologies applicable to software requirements and analysis.*  
    
 *As you review the material in this unit, spend some time on the
object-oriented methodology as it applies to software requirements and
analysis. You will be applying this in a later unit to put it all
together in a case study.*

**Unit 5 Time Advisory**  
Completing this unit will take you approximately 21 hours.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 5.1: 3 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 5.2: 1.5 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 5.3.1: 5 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 5.3.2: 7 hours  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px;">☐
   </span>Subunit 5.3.3: 4.5 hours

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   define fundamental software requirements and analysis terms;
-   list the four activities of software requirements and analysis;
-   list and discuss the context of use of various requirements
    elicitation techniques;
-   describe the conceptual foundation underlying data-oriented,
    process-oriented, and object-oriented methodologies; and
-   list the analysis activities and their major representations in
    data-oriented, process-oriented, and object-oriented methodologies.

**5.1 Requirements Fundamentals** <span id="5.1"></span> 
**5.1.1 Characteristics of Good Requirements** <span id="5.1.1"></span> 
-   **Reading: Institute of Electrical and Electronics Engineers, Inc.:
    IEEE Std 830-1998, IEEE Recommended Practice for Software
    Requirements Specifications**
    Link: Institute of Electrical and Electronics Engineers, Inc.:
    *[IEEE Std 830-1998, IEEE Recommended Practice for Software
    Requirements
    Specifications](http://www.math.uaa.alaska.edu/~afkjm/cs401/IEEE830.pdf) *(PDF)  
        
     Instructions: Read section “4.3: Characteristics of a good SRS,” on
    pages 4–8. The IEEE considers good software requirement
    specifications (SRS) as having eight qualities, or characteristics.
    These qualities define good SRS regardless of the content or type of
    requirements. The eight qualities are correct, unambiguous,
    complete, consistent, stable, verifiable, modifiable, and traceable.
    Take your time in reading and jot down any ideas or notes that stand
    out to you as particularly useful (or, conversely, confusing).  
        
     Reading this selection, taking notes, and taking time to comprehend
    should take approximately 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.1.2 Content of Good requirements: Functional and Non-functional**
<span id="5.1.2"></span> 
-   **Reading: Institute of Electrical and Electronics Engineers, Inc.:
    IEEE Std 830-1998, IEEE Recommended Practice for Software
    Requirements Specifications**
    Link: Institute of Electrical and Electronics Engineers, Inc.:
    *[IEEE Std 830-1998, IEEE Recommended Practice for Software
    Requirements
    Specifications](http://www.math.uaa.alaska.edu/~afkjm/cs401/IEEE830.pdf) *(PDF)  
        
     Instructions: Read sub-sections 5.3.1 through 5.3.6 in section
    “5.3: Specific Requirements,” on pages 15–18. In addition to the
    eight characteristics of good SRS, the IEEE recommends both
    functional and non-functional requirements for good SRS. Functional
    requirements represent *what the system will* *do* to accept and
    process inputs and generate outputs. For example, for an accounting
    system, this may be customer statement preparation at the end of the
    month. Non-functional requirements represent *how the system has to
    be* to satisfy system constraints. For example, this may be to
    prepare all customer statements within a five-hour batch window. As
    you read the text, note that sub-sections 5.3.1, 5.3.2, and 5.3.4
    are classified as functional requirements, whereas sub-sections
    5.3.3, 5.3.5, and 5.3.6 are classified as non-functional
    requirements.  
        
     Reading this selection, taking notes, and taking time to comprehend
    should take approximately 2 hours and 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2 Requirements Activities** <span id="5.2"></span> 
-   **Reading: Carnegie Mellon’s Software Engineering Institute: *A
    Framework for Software Product Line Practice*, Version 5.0:
    “Requirements Engineering”**
    Link: Carnegie Mellon’s Software Engineering Institute: *A Framework
    for Software Product Line Practice, Version 5.0*: [“Requirements
    Engineering”](http://www.sei.cmu.edu/productlines/frame_report/req_eng.htm) (HTML)  
        
     Instructions: Read this article. According to Carnegie Mellon’s
    Software Engineering Institute SEI, there are five
    techniques—requirements elicitation, requirements analysis,
    requirements specification, requirements verification, and
    requirements management—that can be applied systematically in the
    requirements process. Take your time in reading and jot down any
    ideas or notes that stand out to you as particularly useful (or,
    conversely, confusing).  
        
     Reading this selection, taking notes, and taking time to comprehend
    should take approximately 1 hour and 30 minutes.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3 Requirements Analysis Methodologies** <span id="5.3"></span> 
**5.3.1 Process-Oriented Analysis** <span id="5.3.1"></span> 
-   **Reading: The Global Text Project: Sue Conger’s *The New Software
    Engineering*: “Chapter 7: Process-Oriented Analysis”**
    Link: The Global Text Project: Sue Conger’s [*The New Software
    Engineering*](http://dl.dropbox.com/u/31779972/The%20New%20Software%20Engineering.pdf):
    “Chapter 7: Process-Oriented Analysis” (PDF)  
        
     Instructions: Read “Chapter 7: Process-Oriented Analysis” (pages
    227–278). Process-oriented analysis originated with the work of
    Yourdon-DeMarco and Gane-Sarson. The analysis follows a top-down
    approach to progressively more detailed levels of process analysis,
    resulting in context diagrams, data flow diagrams, and data
    dictionary entities. Take your time in reading and jot down any
    ideas or notes that stand out to you as particularly useful (or,
    conversely, confusing).  
        
     Reading this selection, taking notes, and taking time to
    comprehendshould take approximately 5 hours.  
        
     Terms of Use: This resource is available under a [Creative Commons
    Attribution 3.0 Unported
    License](http://creativecommons.org/licenses/by/3.0/). It is
    attributed to Sue Conger and The Global Text Project, and it may be
    found in its original form
    [here](http://dl.dropbox.com/u/31779972/The%20New%20Software%20Engineering.pdf).

**5.3.2 Data-Oriented Analysis** <span id="5.3.2"></span> 
-   **Reading: The Global Text Project: Sue Conger’s *The New Software
    Engineering*: “Chapter 9 Data-Oriented Analysis”**
    Link: The Global Text Project: Sue Conger’s [*The New Software
    Engineering*](http://dl.dropbox.com/u/31779972/The%20New%20Software%20Engineering.pdf):
    “Chapter 9 Data-Oriented Analysis” (PDF)  
        
     Instructions: Read “Chapter 9: Data-Oriented Analysis” (pages
    328–390). Information engineering (IE) is the methodology used to
    illustrate data-oriented analysis. In the data-oriented approach,
    there is the notion that data are more stable than processes.
    Business area analysis (BAA), which is the IE term for analysis,
    begins with an analysis of data followed by business function
    processes resulting in entity-relationship diagrams (ERDs), data
    flow diagrams (DFDs), and the entity/process matrix called CRUD
    matrix (create, retrieve, update, delete).Take your time in reading
    and jot down any ideas or notes that stand out to you as
    particularly useful (or, conversely, confusing).  
        
     Reading this selection, taking notes, and taking time to comprehend
    should take approximately 7 hours.  
        
     Terms of Use: This resource is available under a [Creative Commons
    Attribution 3.0 Unported
    License](http://creativecommons.org/licenses/by/3.0/). It is
    attributed to Sue Conger and The Global Text Project, and it may be
    found in its original
    form [here](http://dl.dropbox.com/u/31779972/The%20New%20Software%20Engineering.pdf).

**5.3.3 Object-Oriented Analysis (OOA)** <span id="5.3.3"></span> 
-   **Reading: The Global Text Project: Sue Conger’s *The New Software
    Engineering*: “Chapter 11: Object-Oriented Analysis”**
    Link: The Global Text Project: Sue Conger’s [*The New Software
    Engineering*](http://dl.dropbox.com/u/31779972/The%20New%20Software%20Engineering.pdf):
    “Chapter 11: Object-Oriented Analysis<span
    style="font-family: Arial, sans-serif; color: black;">”</span> (PDF)  
        
     Instructions: Read the sections beginning with “Object-Oriented
    Analysis Activities” in “Chapter 11: Object-Oriented Analysis”
    (pages 463–500). Unlike process-oriented (which is focused
    on *functional* thinking) and data-oriented (which is focused
    on *entity* thinking) analyses, objected-oriented analysis is
    focused on *object* thinking. Data and processes are married early
    in the process and encapsulated into classes/objects.
    Object-oriented analysis (and design) represents a paradigm shift in
    software development. As you read this material, bear in mind that
    the text illustrates this approach using the Booch notation, which
    has been supplanted by the Unified Modeling Language (UML). However,
    much of the Booch notation has been *unified* in UML (and is
    therefore still valid)—especially the class diagrams— and classified
    into whole/part or generalization/specialization classes. Take your
    time in reading and jot down any ideas or notes that stand out to
    you as particularly useful (or, conversely, confusing).  
        
     Reading this this selection, taking notes, and taking time to
    comprehend should take approximately 4 hours.  
        
     Terms of Use: This resource is available under a [Creative Commons
    Attribution 3.0 Unported
    License](http://creativecommons.org/licenses/by/3.0/). It is
    attributed to Sue Conger and The Global Text Project, and it may be
    found in its original
    form [here](http://dl.dropbox.com/u/31779972/The%20New%20Software%20Engineering.pdf).

-   **Assessment: The Saylor Foundation’s “Unit 5 Checkpoint”**
    Link: The Saylor Foundation’s [“Unit 5
    Checkpoint”](http://www.saylor.org/site/wp-content/uploads/2013/10/CS302-OC-Unit-5-PRVFINAL.pdf) (PDF)  
        
     Instructions: Complete this assessment. When you have completed the
    assessment, check your answers against the [“Unit 5 Checkpoint Guide
    to
    Responding”](http://www.saylor.org/site/wp-content/uploads/2013/10/CS302-OC-Unit-5-Answer_Key-PRVFINAL.pdf).  
        
     Completing this assignment should take approximately 30 minutes.


