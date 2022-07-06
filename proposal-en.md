# Abstract
効率的な練習は大事。
VEを使えば様々な条件下で練習をすることができ、運動学習の保持に貢献する可能性がある。
本研究では、HMDをVEとして、complex motor skill のlearning中にノイズを加えることで、motor leaning のtransferとretention が
実世界に促進されるかを調査する。

# Background
## Virtual Environment as a Training Platform
Virtual Environments (VEs) provide a safe, realistic, and interactive learning environment with the opportunity for repeated practice. 
However, a relatively small number of studies have explored motor skill acquisition and transfer from virtual to real environments [1]. 
Moreover, even fewer studies have used Head-Mounted Displays (HMDs) as VE.

## Motor Skill Consolidation
Newly acquired motor skills become stabilized through consolidation, which represents the process by which motor skills are transformed from an initial fragile state to a more solid state.
Motor skills can be modified and enhanced through exposure to increased sensorimotor variability [2], and contextual variability can strengthen retention [3].
However, whether inducing variability in VEs enhances transfer and retention to real-world tasks is unknown.


# Problem
Does motor learning in VEs transfer to real environment, and does increasing variability in VEs enhance transfer and retention in real world?

# Hypothesis
1. Motor learning in VE using HMD transfers to real environment.
2. Inducing variability in motor learning under VE enhances transfer and retention in the real world.

# Approach
## Using Noise in VE learning
Darts will be used as a motor learning task in this research.
In order to test if inducing variability in VE can strengthen motor skill transfer and retention in the real-world, sensorimotor noise will be added to dart throws. 
For the virtual dart setting, Meta Quest 2 will be used as a HMD, and the dart throwing environment will be implemented by Unity. 

## Noise Implementation
The trajectory of a dart is determined by release point, velocity, and the magnitude of gravity. Noise will be added by changing the velocity of the dart in VE. 

# Experiments
## Participants
Participants will be divided into three groups (VE learing group, VE learning with Noise group, and real-world learning group). Because motor skill experience affects consolidation and retention, all participants should be novices at darts.

## Learning and Test Phases
Experiment has four phases, pre-test, learning phase, post-test, and retention-test. During the learning phase, all participants will complete four sessions consisting of 50 throws. For a group practicing with noise in VE, noise will be added in the last two sessions, so that the participants can consolidate skill without noise in the first two sessions.

# Evaluation
## Pre-, Post, and Retention test
During the test phase, all participants will complete 30 throws in the real-world settings. A participant’s skill level is measured by the distance to the bull’s eye. In order to evaluate the motor skill preservation, retention test will be held in the next day of learning.


# References
- Levac D, Huber M, Sternad D. Learning and transfer of complex motor skills in virtual reality: A perspective review.
  Journal of NeuroEngineering and Rehabilitation, (2019), 16(1).
- Wymbs N, Bastian A, Celnik P. Motor skills are strengthend through reconsolidation.
  Current Biology, (2016), 338-343, 26(3).
- Shea, J.B., and Morgan, R.L. Contextual interference effects on the acquisition, retention, and transfer of a motor skill.
  Journal of Experimental Psychology: Human Learning and Memory, (1979) 5, 179-187


# Expected Questions
- What is sensorimotor variability, and contextual variability?
sensorimotor is about sensory and motor. In this case, sensorimotor variability is change in the visual dart trajectory, and participants' change in motor function.
Contextual interference involves mixing up your practice structure, either by adding different tasks and/or adding practice variability when learning a skill.
