## HOW TO CODE: SIMPLE DATA: UNIVERSITY OF BRITISH COLUMBIA (UBCx - Edx)

How To Code: Simple Data, is the first 7 week module from the [**MICROMASTER - Software Developer** from **University of British Columbia**](https://www.edx.org/course/how-code-simple-data-ubcx-htc1x).

## About this course 

**Course Description**

This course takes a unique approach, focusing on a systematic programming method rather than restricting learners to any one specific programming language. This practical approach will allow you to apply your skills and creativity more widely and to program well in any language.

The course is part of the [**Software Development MicroMasters Program**](https://www.edx.org/micromasters/software-development) and presents a core design method with a focus on numbers, strings, images and lists.

You will learn techniques to:

1. Develop program requirements
2. Produce programs with consistent structure that are easy to modify later
3. Make your programs more reliable by building tests as an integral part of the programming process.
4. This course concludes with the design of a simple interactive game.
5. Learners who enroll in the Verified track will receive staff grading for the course project and increased interaction with the instructor and staff.

What you'll learn:
1. How to represent information as data
2. How to focus each part of your program on a single task
3. How to use examples and tests to clarify what your program should do
4. How to simplify the structure of your program using common patterns
5. Recognize and represent more complicated information

## MODULE 2: How To Design Data (HTDD): INTERVAL

In this lesson from **module 2: How to Design Data - Interval**, we learn how to Design Data (HtDD recipe) to create interval.

### WHEN DO I USE INTERVAL?

Use an interval when the information to be represented is numbers within a certain range. Integer[0, 10] is all the integers from 0 to 10 inclusive; Number[0, 10) is all the numbers from 0 inclusive to 10 exclusive. (The notation is that [ and ] mean that the end of the interval includes the end point; ( and ) mean that the end of the interval does not include the end point.)

### HOW TO CODE WITH INTERVAL?

To create a code using a interval, we need to follow the recipe:

> ;; Countdown is Integer[0, 10]<br>
> ;; interp. the number of seconds remaining to liftoff<br>
> (define C1 10)  ; start<br>
> (define C2 5)   ; middle<br>
> (define C3 0)   ; end<br>
> <br>
> #;<br>
> (define (fn-for-countdown cd)<br>
>  (... cd))<br>

> ;; Template rules used:<br>
> ;;  - atomic non-distinct: Integer[0, 10]<br>

