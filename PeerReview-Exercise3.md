# Peer-Review for Programming Exercise 3 #

## Description ##

For this assignment, you will be giving feedback on the completeness of assignment three: Pikmini. In order to to do so, we will be giving you a rubric to give feedback on. For the feedback, please give positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to review the code and project files that were given out by the instructor.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.   

Email: asisandhu at ucdavis dot edu

## Due Date and Submission Information
This code review is due on:  
Monday, May 13th.

A successful submission should consist of a copy of this markdown document template that is modified with your peer-review. The file name should be the same as it is in the template: `CodeReview-Exercise3.md`. You also need to include your name and email address in the `Peer-reviewer Information` section below. This review document should be placed into the base folder of the repo you are reviewing in a branch called `review`. This branch should be on the origin of the repository you are reviewing.

If you are in the rare situation where there are two peer-reviewers on a single repository, append your UC Davis user name before the extension of your review file. An example: `CodeReview-Exercise3-username.md`. Both reviewers should submit their reviews in the `review` branch.
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

### Stage 1.1 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
The colorwatcher objects are instantiated according to each of the cases properly.
The watcher function is called within update, and the color polling functionality works as intended.

___
### Stage 1.2 ###

- [ ] Perfect
- [ ] Great
- [ ] Good
- [X] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
While the functionality is written clearly, the throttle functionality to introduce a noticeable delay
between each consecutive color change did not work as expected on testing with different values.

___
### Stage 2.1 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
The subscribe, unsubscribe and notify methods are self explantory. 
Moreover, inclusion of the foreach method to loop through the list makes it concise. 
___
### Stage 2.2 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
The subscribe and unsubscribe methods add and remove the pikmini gameobject respectively
as intended through their individual functionalities. 

___
### Stage 2.3 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
The SendMessageWithPublisher method correctly notifies each pikmini gameobject of 
its respective destination in response to the UI button clicks in response to the 
user's choice. 

___
### Stage 3 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justifaction ##### 
On triggering the Fire2 mouse button click, it instantiates the pikmini gameobject
based on the prefab passed into its field as intended.

___
# Code Style #


### Description ###
Check the scripts to see if the student code adheres to the dotnet style guide.

If there are sections that don't adhere to the style guide, please peramlink the line of code from Github and justify why the line of code has infractured the style guide.

It should look something like this:

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

Please refer to the first code review template on how to do a permalink.


## Code Style Infractures ##
There weren't any major code style infractures that hindered the flow of 
logic throughout the code files. 
___
#### Put style guide infractures ####

___

# Best Practices #

### Description ###

If the student has followed best practices (Unity coding conventions from the StyleGuides document) then feel free to point at these segments of code as examplars. 

If the student has breached the best practices and has done something that should be noted, please add the infracture.


This should be similar to the Code Style justification.

## Best Practice observations ##

He followed the best practices and style guide really well, since I did not have my understanding of 
the written code impeded in any way. These practices consistenly helped parse the logic flow and code
at a glance.

___
### Put best practice observations here ###

*[Maintained a consistent pattern with keeping private variables](https://github.com/ensemble-ai/exercise3-observer-ssfaruque/blob/dcbc9136ec3cceb45f41cb424e607cffa02504a1/Pikmini/Assets/Scripts/MiniController.cs#L17)

*[Kept the serialized fields private, not public ](https://github.com/ensemble-ai/exercise3-observer-ssfaruque/blob/dcbc9136ec3cceb45f41cb424e607cffa02504a1/Pikmini/Assets/Scripts/PikminiSpawner.cs#L8)

*[Used a constructor for the class to initialize the list for each instantiated object](https://github.com/ensemble-ai/exercise3-observer-ssfaruque/blob/dcbc9136ec3cceb45f41cb424e607cffa02504a1/Pikmini/Assets/Scripts/Publisher.cs#L12)

*[Using the foreach method to loop improves readability by a lot](https://github.com/ensemble-ai/exercise3-observer-ssfaruque/blob/dcbc9136ec3cceb45f41cb424e607cffa02504a1/Pikmini/Assets/Scripts/Publisher.cs#L19)

___
