What are the basic concepts of DFT?

DFT (Date Flow Testing) is a technology which can detect problems about data dependency and optimize performance of program. There are two important concepts in DFT. They are Data Flow (Date Dependency) and Data Slice.
There are two kind of data operation in DFT, Define (D) and Use (U). D means create, initialize and assign data. And U involves computational and predicate characteristics of data operations. We should focus on Define and relate Use. There are some methods to analysis data dependency problem. U-U and D-U are ok. And if you found D-D, U-D, there may be some problems in your program, and you should focus on this. DFT focuses on testing D-U relations. We can use DDG help us to analysis software.
