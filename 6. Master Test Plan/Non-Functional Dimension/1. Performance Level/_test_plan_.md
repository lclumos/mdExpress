### PERFORMANCE TEST

###### INTRODUCTION
This test is to determine how system performs in terms of responsiveness and stability under particular workload. Serve purposes of investigating, measuring, validating or verifying other quality attributes of the system, such as scalability, reliability and resource usage. Determine operability, stability, resource consumption and other attributes of app quality. Ensure app performs acceptably under certain performance requirements such as huge number of users


###### TEST CASE TO RTM
Provide a table that maps all of the requirements contained within the Requirements Document to their corresponding test cases/scripts. Reference the Appendices section of this document for a sample template for a Test Case-to-Requirements Traceability Matrix. The completed traceability matrix should be inserted here or a reference made to its inclusion as a separate appendix. If test case/script information is maintained in an automated tool, the matrix may be exported or printed from the tool for inclusion in this document.


###### TEST CASE IDENTIFIER
> **1. Test Objective**  
Describe the purpose of the test case/script and provide a brief description. Also, identify if the test case/script may be used by multiple test functions.

> **2. Inter-Case Dependencies**  
List any prerequisite test cases/scripts that would create the test environment or input data in order to run this test case/script. Also, list any post-requisite test cases/scripts for which the running of this test case/script would create the test environment or input data.

> **3. Test Items**  
Describe the items or features (e.g., requirements, design specifications, and code) to be tested by the test case/script. Keep in mind the level for which the test case/script is written and describe the items/features accordingly. The item description and definition can be referenced from any one of several sources, depending on the level of the test case/script. It may be a good idea to reference the source document as well (e.g., Requirements Document, System Design Document, User Manual, Operations & Maintenance Manual, Installation Instructions from Version Description Document, etc.)

> **4. Prerequisite Conditions**  
Identify any prerequisite conditions that must be established prior to performing the test case/script. The following considerations should be discussed, as applicable:
* Environmental needs (e.g., hardware configurations, system software (e.g., operating systems, tools), other software applications, facilities, training);  
* Stubs, drivers, flags, initial breakpoints, pointers, control parameters, or initial data to be set/reset prior to test commencement;  
* Preset hardware conditions or states necessary to run the test case/script;  
* Initial conditions to be used in making timing measurements;  
* Conditioning of the simulated environment; and  
* Other special conditions (e.g., interfaces) peculiar to the test case/script

> **5. Input specification**  
Describe all inputs required to execute the test case/script. Keep in mind the level for which the test case/script is written and describe the inputs accordingly. Be sure to identify all required inputs (e.g., data (values, ranges, sets), tables, human actions, conditions (states), files (databases, control files, transaction files), and relationships (timing)). The input can be described using text, a picture of a properly completed screen, a file identifier, or an interface to another system. It is also acceptable to simplify the documentation by using tables for data elements and values. Include, as applicable, the following:  
* Name, purpose, and description (e.g., range of values, accuracy) of each test input;  
* Source of the test input and the method to be used for selecting the test input;  
* Whether the test input is real or simulated;  
* Time or event sequence of test input; and  
* The manner in which the input data will be controlled to:  
* Test the item(s) with a minimum/reasonable number of data types and values.  
* Exercise the item(s) with a range of valid data types and values that test for overload, saturation, and other “worst case” effects.  
* Exercise the item(s) with invalid data types and values to test for appropriate handling of irregular inputs.  
* Permit retesting, if necessary.

> **6. Expected Test Results**  
Identify all expected test results for the test case/script, including both intermediate and final results. Describe what the system should look like after the test case/script is run by examining particular screens, reports, files, etc. Identify all outputs required to verify the test case/script. Keep in mind the level for which the test case/script is written and describe the outputs accordingly. Be sure to identify all outputs (e.g., data (values, sets), tables, human actions, conditions (states), files (databases, control files, transaction files), relationships, timing (response times, duration)). The description of outputs can be simplified by using tables, and may even be included in the same table as the associated input to further simplify the documentation and improve its usefulness.

> **7. Pass/Fail Criteria**  
Identify the criteria to be used for evaluating the intermediate and final results of the test case/script, and determining the success or failure of the test case/script. For each test result, the following information should be provided, as applicable:  
* The range or accuracy over which an output can vary and still be acceptable;  
* Minimum number of combinations or alternatives of input and output conditions that constitute an acceptable test result;  
* Maximum/minimum allowable test duration, in terms of time or number of events;  
* Maximum number of interrupts, halts, or other system breaks that may occur;  
* Allowable severity of processing errors;  
* Conditions under which the result is inconclusive and re-testing is to be performed;  
* Conditions under which the outputs are to be interpreted as indicating irregularities in input test data, in the test database/data files, or in test procedures;  
* Allowable indications of the control, status, and results of the test and the readiness for the next test case/script (may be output of auxiliary test software); and  
* Other criteria specific to the test case/script.

> **8. Test Procedure**  
Describe the series of individually numbered steps that are to be completed in sequential order to execute the test procedure for the test case/script. For convenience in document maintenance, the test procedures may be included as an appendix and referenced in this paragraph. The appropriate level of detail in the test procedure depends on the type of software being tested. For most software, each step may include a logically-related series of keystrokes or other actions, as opposed to each keystroke being a separate test procedure step. The appropriate level of detail is the level at which it is useful to specify expected results and compare them to actual results. The following should be provided for the test procedure, as applicable:  
* Test operator actions and equipment operation required for each step, including commands, as applicable, to:  
* Initiate the test case/script and apply test inputs  
* Inspect test conditions  
* Perform interim evaluations of test results  
* Record data  
* Halt or interrupt the test case/script  
* Request diagnostic aids  
* Modify the database/data files  
* Repeat the test case if unsuccessful  
* Apply alternate modes as required by the test case/script  
* Terminate the test case/script.  
* Expected result and evaluation criteria for each step.  
* If the test case/script addresses multiple requirements, identification of which test procedure step(s) address which requirements.  
* Actions to follow in the event of a program stop or indicated error, such as:  
* Recording of critical data from indicators for reference purposes  
* Halting or pausing time-sensitive test-support software and test apparatus  
* Collection of system and operator records of test results  
* Actions to be used to reduce and analyze test results to accomplish the following:  
* Detect whether an output has been produced  
* Identify media and location of data produced by the test case/script  
* Evaluate output as a basis for continuation of test sequence  
* Evaluate test output against required output  

> **9. Assumptions**  
Identify any assumptions made and constraints or limitations imposed in the description of the test case due to system or test conditions (e.g., limitations on timing, interfaces, equipment, personnel, and database/data files. If waivers or exceptions to specified limits and parameters are approved, they are to be identified and their effects and impacts upon the test case/script described

> **10. Constraints**  
Describe any limitations or constraints that have a significant impact on the test cases/scripts in general. Constraints specific to an individual test case/script are to be described in a later section corresponding with that particular test case/script. Constraints may be imposed by any of the following (the list is not exhaustive):  
* Hardware or software environment  
* End-user environment  
* Availability of resources  
* Interoperability requirements  
* Interface/protocol requirements  
* Data repository and distribution requirements.

> **11. Risk**  
 Describe any risks associated with the test cases/scripts and proposed mitigation strategies.


###### APPENDIX A: ACRONYMS
Provide a list of acronyms and associated literal translations used within the document. List the acronyms in alphabetical order using a tabular format as depicted below.

###### APPENDIX B: GLOSSARY
Provide clear and concise definitions for terms used in this document that may be unfamiliar to readers of the document. Terms are to be listed in alphabetical order.

###### APPENDIX C: REFERENCE DOCUMENTATION & STRUCTURE
Summarize the relationship of this document to other relevant documents. Provide identifying information for all documents used to arrive at and/or referenced within this document (e.g., related and/or companion documents, prerequisite documents, relevant technical documentation, etc.).
