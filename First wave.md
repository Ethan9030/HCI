# First wave

## Introduction

•1980s-1990s

•HCI as an applied science, grounded in lab research

•An information processing perspective, from cognitive psychology[认知心理学]

•Still influential today (though in many cases superseded) 



### Broad theoretical approaches in the first era :



**Paradigm**[范例]: 

Scientific, grounded in lab based cognitive psychology. Computational, centralized, symbol processing view

**Goal**: 

How do individuals make use of computational technologies, and how can technologies be designed to be more usable, and useful.

**Main Approaches to Theory**:

##### 1.Using Isolated Ideas from basic science disciplines

•Easy to remember

•Lacks detail and discrimination

•Not clear how to develop further 

##### 2.Applying theories from basic science disciplines

eg. Paired associate theory 

The approach is specific and allows us to refine our approach by reference to the theory 

##### 3.Developing new HCI-specific theory, grounded in lab science disciplines 

eg. GOMS  Gulfs of Execution and Evaluation 



## GOMS and Fitts’ Law 

•<u>Fitt’s Law</u>: predicting performance on mouse tasks

•<u>GOMS</u>: predicting performance on a range of input tasks (Goals, Operators, Methods and Selection rules)

•Both grounded in cognitive psychology

•Both expanded and developed in HCI

•Narrow, and precise and focused on particular phenomena



### Fitt's Law: pointing, parameterised 

•Originally developed to understand pointing with a finger

•HCI adopted and extended to understand mouse, touchscreen use, and other examples of cursor control

•Posits[断定] a speed-accuracy trade-off in movement towards a target, and quantifies this



**All share one basic idea**: that there is a determinate, quantifiable, speed-accuracy trade-off in movement towards a target. The law predicts that users will make more errors, the faster they move to a target, and the smaller the target, and it says that we can capture this effect numerically, to a reasonable degree of precision. 



Three ways to use Fitt’s Law:

1.High Level qualitative-quantitative engagement



**Further = harder / slower**

•Minimise length of mouse moves

•Control the user’s mouse-path

•Spawn controls close to mouse position

**bigger = easier**

•Make UI elements bigger when time pressure, or risk of error are high

**Alerting the designer to high error rates**

•Minimise cost of error

**Edges and Corners Are Special: infinite width**



2.Mathematical Engagement with the model



•Build tools to analyse layouts and guide design

•Analyse use of nested vs flat menus

•Calculate times for paths through website

•Create adaptive interfaces?



3.Further Theory Building



### GOMS: <u>G</u>oals <u>O</u>perators <u>M</u>ethods and <u>S</u>election rules 

This is a family of predictive models of human performance on more general input tasks.

It can handle a wider range of input behaviours than Fitts’ law - keystrokes, button pushes, clicks, pointer movement. 

It aims to provide an *engineering model* of human performance, to produce quantitative predictions of performance during development and design, before we do any user testing. 



•Analyse times for input tasks for a **skilled user**

•Again, grounded in information processing models from cognitive psychology

•Aims to be easy for designers to apply



•Decomposes tasks into on atomic actions (operators) and assigns times:

it helps us find the times for these various atomic operations, and estimate the time for the task.

•Various versions of varying complexity

•Simple: KLM-GOMS

•Complex: CPM-GOMS



<u>The advantage of this over something like Fitts’ Law</u> is that it allows more aspects of the interface to be captured and optimised together. With Fitts’ Law we noted that in each case, other factors had to be taken into account separately. GOMS aims to eliminate some of this messiness.



•**GOALS**: what the user wants to do

simply the user’s goals - what they want to achieve with the software over a given period (seconds, minutes, hours). These can be broken into sub-goals. Say I want to write a tetris imitation - I can break that task into several sub-goals all of which can be done with a computer: I need to find out the rules of tetris, download libraries, implement the code, make the art work, test the game



•**OPERATORS**: individual actions

actions which can be performed on the computer, and are allowed by the software and hardware. At the time of GOMS most systems used command line interfaces, so this could all be described in terms of keypresses. Now we have GUIS, so operators might also include button pushes, mouse clicks, drags, and various other GUI actions. In principle, any meaningful behaviour could be defined and given some time estimate or heuristic for estimating time: eye movements on screen, for example.



•**METHODS**: how to combine actions to achieve the goal

They are collections of sub-goals and operators, learned by the user, which are combined together to accomplish the overall goal. It’s easy to see that there might be more than one method to accomplish the goal in a particular system.



•**SELECTION RULES**: how to choose between potential METHODS of the task 

the rules the user follows when deciding which method to use to achieve the goal, given the particular circumstances they are in.



KLM OPERATORS:

•K - press a key

•P - point to location on screen with mouse

•H - move hands to home position on the keyboard

•M - mentally preparing to perform an action

•R - system response while the user waits for the system.



**Limitations:**

•No Fatigue

•No Learning (expert users)

•No Errors (expert users)

•All tasks are goal-directed

•Goal is clear at start of the task (no problem solving)

GOMS 不处理可能影响使用的一系列其他因素，例如疲劳、创造力、与同事的互动。 它不处理错误，并假定用户是专家。 它不处理学习。 它还假设所有任务都是目标导向的，并且目标在活动和子活动开始时就被明确定义——因此它忽略了问题的解决。 与 Fitts 一样，它只告诉我们速度：这只是系统使用的一个非常狭窄的维度。 它并没有告诉我们一个系统使用起来有多愉快或愉快。 除了我们希望系统本身令人愉快之外，这可能会影响现实世界中模型的准确性：我们可能会发现，如果系统太无聊，性能可能会随着时间的推移而下降。

