# 23.Flesch-Driver.py

# -*- coding: utf-8 -*-
"""
Created on Mon Jan 21, 2019
Program: fleschdriver.py

Test driver for Flesch Index and Grade level. 

@author: Byen23
"""

# Testing 
"""
Although the main tasks all collaborate in a text analysis program, they can be tested more or less independently, before the entire program is tested. After all, there is no point in running the ocmplete program if you are unsure that even one of the tasks does not work correctly.

This kind of procedure is called bottom-up testing. Each task is coded and tested for one or two tasks, you can test them in short script. THis script is caleld a driver. For example, here is a driver that tests the code for computing the Flesch Index and the Grade Level Equivalent without using a text file:

"""
This driver allows the programmer not only to verify the two tasks, but also to obtain some data to use when testing the complete program later on. For example, the programmer acn supply a text file that contains the number of sentences, words, and syllables already tested in the driver, and then compare the two test results.

In bottom-up testing, the lower-level tasks must be developed and tested before those tasks that depend on the lower-level tasks.

When you have tested all of the parts, you can integrate them into the complete  program. The test data at that point should be short files that produce the expected results. THen, ou should use longer files. For example, you might see if plaintext versions of Dr. Sueuss's Green Eggs and Ham and Shakespeare's Hamlet produce grade levels of 5th grade and 12th grade, respectively. Or you could test the program with its own source program file--but we predict that its readbility will seem quite low, because it lacks most of the standard end-of-sentence marks!
"""
