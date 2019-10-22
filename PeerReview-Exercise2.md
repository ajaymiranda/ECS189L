# Peer-Review for Programming Exercise 2 #

## Description ##

For this assignment, you will be giving feedback on the completeness of assignment two: Obscura. In order to to do so, we will be giving you a rubric to give feedback on. For the feedback, please give positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to review the code and project files that were given out by the instructor.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.   

Email: asisandhu at ucdavis dot edu

## Due Date and Submission Information
This code review is due on:  
*Friday, May 3rd at 11:59 PM*

A successful submission should consist of a copy of this markdown document template that is modified with your peer-review. The file name should be the same as it is in the template: `CodeReview-Exercise2.md`. You also need to include your name and email address in the `Peer-reviewer Information` section below. This review document should be placed into the base folder of the repo you are reviewing in a branch called `review`. This branch should be on the origin of the repository you are reviewing.

If you are in the rare situation where there are two peer-reviewers on a single repository, append your UC Davis user name before the extension of your review file. An example: `CodeReview-Exercise2-username.md`. Both reviewers should submit their reviews in the `review` branch.
___
# Solution Assessment #

## Peer-reviewer Information

* *name:* [Ajay Vincent Miranda] 
* *email:* [avmiranda@ucdavis.edu]

### Description ###

For assessing the solution, you will be choosing ONE choice from: unsatisfactory, satisfactory, good, great, or perfect.

The break down of each of these labels for the solution assessment.

#### Perfect #### 
    Can't find any flaws in relation to the prompt. Perfectly satisfied all stage objectives.

#### Great ####
    Minor flaws in one or two objectives. 

#### Good #####
    Major flaw and some minor flaws.

#### Satisfactory ####
    Couple of major flaws. Heading towards solution, however did not fully realize solution.

#### Unsatisfactory ####
    Partial work, not really converging to a solution. Pervasive Major flaws. Objective largely unmet.


___

## Solution Assessment ##

### Stage 1 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
Works as intended, each of the cases are properly handled.

___
### Stage 2 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
The saturation cases for each direction are accounted for. Good comments.

___
### Stage 3 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
The comments are well written and the code cases are self-explanatory.

___
### Stage 4 ###

- [ ] Perfect
- [X] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
Descriptive variable names, more or less clear flow of logic from part to part.

___
### Stage 5 ###

- [ ] Perfect
- [X] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
Organized and well thought out logic for the inner box and corresponding camera control.
Could provide a few more lines of comments on the math function and its flow.
___
# Code Style #


### Description ###
Check the scripts to see if the student code adheres to the dotnet style guide.

If there are sections that don't adhere to the style guide, please peramlink the line of code from Github and justify why the line of code has infractured the style guide.

It should look something like this:

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

Please refer to the first code review template on how to do a permalink.


## Code Style Infractures ##
* [The variable name should follow the camelCase naming convention](https://github.com/ensemble-ai/exercise2-cameracontroller-failury/blob/3b426aa8d77e2f7c11cc98698d5d18df09e2492c/Obscura/Assets/Scripts/FourWaySpeedupPushZoneCameraController.cs#L29)

___
#### Put style guide infractures ####
* [Addition of parentheses to enclose the logic concatenated between the and symbol would help with clarity](https://github.com/ensemble-ai/exercise2-cameracontroller-failury/blob/3b426aa8d77e2f7c11cc98698d5d18df09e2492c/Obscura/Assets/Scripts/FourWaySpeedupPushZoneCameraController.cs#L48)

* [The indentation should be consistent with the other lines](https://github.com/ensemble-ai/exercise2-cameracontroller-failury/blob/3b426aa8d77e2f7c11cc98698d5d18df09e2492c/Obscura/Assets/Scripts/TargetFocusLerpCameraController.cs#L30)

___

# Best Practices #

### Description ###

If the student has followed best practices (Unity coding conventions from the StyleGuides document) then feel free to point at these segments of code as examplars. 

If the student has breached the best practices and has done something that should be noted, please add the infracture.


This should be similar to the Code Style justification.

## Best Practice observations ##

The coding and style guides were followed to a good extent. The written code had a clear throughline which made it relatively easy to grasp. Although some of the variable names did not follow the designated camelCase conventions, they were descriptive enough to address the functionality of the function call without having to add extra comment lines. The comments also complemented the flow of the program where required, and helped aid in understanding.


___
### Put best practice observations here ###

* [The variable names used here, translate the logic of the following operations clearly](https://github.com/ensemble-ai/exercise2-cameracontroller-failury/blob/3b426aa8d77e2f7c11cc98698d5d18df09e2492c/Obscura/Assets/Scripts/TargetFocusLerpCameraController.cs#L35)




___
