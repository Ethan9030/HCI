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

## Heuristic[启发式] models

GOMS and Fitt's Law: =====> Narrow, precise, and predictive 

Heuristic models and general models: ======> Broader, generalising, prescriptive



### **Direct Manipulation:**

Direct manipulation是一种用户界面交互范例，允许用户直接使用物理手势或动作与数字对象或图形元素进行交互。它旨在为用户提供一种更直观、更即时的方式来操作和控制屏幕上或虚拟环境中的对象，模拟感官

### **Gulfs of Execution and Evaluation:**  

Gulfs of Execution and Evaluation是人机交互领域中的概念，由Donald Norman提出。它们描述了人类与计算机系统之间的差距，这些差距可能会导致用户在使用计算机系统时遇到困难。

- **Gulf of Execution**：指的是用户的意图与计算机系统的操作之间的差距。如果用户的意图与计算机系统的操作不匹配，那么用户就会遇到执行上的困难。例如，如果用户想要在计算机上打印文档，但不知道如何打开打印机，那么就会出现执行上的困难。
- **Gulf of Evaluation**：指的是用户的期望与计算机系统的反馈之间的差距。如果计算机系统的反馈不符合用户的期望，那么用户就会遇到评估上的困难。例如，如果用户不知道他们的文档是否已经成功打印，那么就会出现评估上的困难。

这些差距可能会导致用户在使用计算机系统时感到困惑或沮丧。设计师可以通过使用易于理解的界面和反馈来减少这些差距，从而提高用户的满意度和效率。



The idea is that this model can help decompose and diagnose issues with usability: it  helps pinpoint wither the issue lies with visibility, interpretation, or maybe with missing system functions



## Information processing theories in the First Wave

All the theories we looked at here are grounded in information processing models of cognition, from cognitive psychology – they share some fundamental assumptions and limitations, and as such they are very compatible with one-another. We saw how direct manipulation was directly related to gulfs of execution and evaluation.

And the Gulfs model is also closely related to GOMS.
We can translate the gulf of execution back into the framework of GOMS very easily: a gulf of execution occurs when I don’t have the right Model for the task, and I need to alter it. 
That is: I need to form the right intentions, or set of sub-goals, and specify a correct sequence of operations for each to form a method. Using GOMS we could quantify this.

[而Gulfs模型也与GOMS密切相关。
我们可以非常轻松地将执行鸿沟转化回 GOMS 框架：当我没有适合任务的正确模型时，就会出现执行鸿沟，并且我需要更改它。
也就是说：我需要形成正确的意图，或者一组子目标，并为每个目标指定正确的操作顺序以形成方法。 使用 GOMS 我们可以对此进行量化]

In particular, HCI researchers started to find that the context of use, external resources such as other people, spatial layout of technology, and representations of information in the world outside the screen were integral to how people behaved with technology. <u>People began to feel that the kind of theories we looked at this week didn’t capture interaction as such, they just described an internal model, and that the real conditions of interaction might affect how this internal model worked.</u>  They began to develop theories which emphasised more accessible features of human behaviour, that were easier to study, and that allowed them to engage with a wider breadth of human experience. Some of this was influenced by the other theories of psychology, anthropology and sociology which I briefly mentioned above. We’ll hear more about all this in the coming weeks.
