******************************************************
* SemEval-2017 Task #3: Community Question Answering *
*                                                    *
*               TEST datasets                        *
*            for subtasks A, B, C, and D             *
*                                                    *
* http://alt.qcri.org/semeval2017/task3/             *
* semeval-cqa@googlegroups.com                       *
*                                                    *
******************************************************

SUMMARY

- SemEval2017_task3_test_ABCD_README.txt -- this file


English/

  - SemEval2017-task3-English-test.xml -- test dataset for subtasks A, B, and C (English).
Note that, as in SemEval-2016 Task 3, there are repetitions of related questions (marked with SubtaskA_Skip_Because_Same_As_RelQuestion_ID="XXX"), and these are to be skipped if you use this file for subtask A.

  - SemEval2017-task3-English-test-subtaskA.xml -- an alternative input for subtask A, which excludes the repetitions that are present in SemEval2017-task3-English-input.xml

  *** NOTE: This time we are not providing the "multiline"-formatted version from 2016.

Arabic/

  - SemEval2017-Task3-CQA-MD-test.xml.gz -- test input for subtask D (Arabic)


INPUT DATA FORMAT

  The TEST input data is in the same format as the DEV input data.


EXPECTED OUTPUT FORMAT

  As before, this is the format specified in the README of the scorer. For your reference, there should be 2,930 predictions for subtask A, 880 predictions for subtask B, 8,800 predictions for subtask C, and 12,600 for subtask D.


LICENSE

Licensing: 
- the scripts and all files released for the task are free for general research use 
- you should use the following citation in your publications whenever using these resources:

  @InProceedings{SemEval-2017:task3,
     author    = {Nakov, Preslav and Hoogeveen, Doris and M\`{a}rquez, Llu\'{i}s and Moschitti, Alessandro and Mubarak, Hamdy and Baldwin, Timothy and Verspoor, Karin},
     title     = {{SemEval}-2017 Task 3: Community Question Answering},
     booktitle = {Proceedings of the 11th International Workshop on Semantic Evaluation},
     series    = {SemEval '17},
     month     = {August},
     year      = {2017},
     address   = {Vancouver, Canada},
     publisher = {Association for Computational Linguistics},
   }

CREDITS

Task Organizers:

    Preslav Nakov, Qatar Computing Research Institute, HBKU
    Lluís Màrquez, Qatar Computing Research Institute, HBKU
    Alessandro Moschitti, Qatar Computing Research Institute, HBKU
    Hamdy Mubarak, Qatar Computing Research Institute, HBKU
    Timothy Baldwin, The University of Melbourne
    Doris Hoogeveen, The University of Melbourne
    Karin Verspoor, The University of Melbourne

Task website: http://alt.qcri.org/semeval2017/task3/

Contact: semeval-cqa@googlegroups.com
  

References:

- Preslav Nakov, Lluis Marquez, Alessandro Moschitti, Walid Magdy, Hamdy Mubarak, Abed Alhakim Freihat, James Glass, Bilal Randeree. SemEval-2016 Task 3: Community Question Answering. In Proceedings of the 10th International Workshop on Semantic Evaluation (SemEval'2016), June 16-17, 2016, San Diego, California, USA.

- Preslav Nakov, Lluis Marquez, Walid Magdy, Alessandro Moschitti, James Glass, Bilal Randeree. SemEval-2015 Task 3: Community Question Answering. In Proceedings of the 9th International Workshop on Semantic Evaluation (SemEval'2015), pp. 269-281, June 4-5, 2016, Denver, Colorado, USA.
