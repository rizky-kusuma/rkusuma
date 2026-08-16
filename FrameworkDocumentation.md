---
layout: page
title: 1.0 Introduction
published: false

---

# 1.0 Introduction

The problem solving framework I've developed essentially contains 10 assessment rubrics. This manuscript documents the progress and development of this framework which was conceived, after trials and errors with undocumented framework, on April 2nd 2026. Over its run (as of May 2026) the framework has gone a major change, noticeably in its implementation on question submission / analysis.
\#### Legends:

> - Letter x denotes the corresponding phase to the framework
> - Letter y denotes the corresponding part that is in the phase x
> - F(x.y) reads "part y in phase x of the problem solving framework"
> - Maximum score is 10.00

## 1.1 Problem Solving Framework

| Phase | Stages | Scores (pts) |
|----|----|----|
| Redescription | F(1.1) Identify major physical laws F(1.2) Identify constraints, coordinates, systems | F(1.1) 1.5  pts F(1.2) 1.5  pts |
| Reconstruction | F(2.1) Heuristics, F(2.2) Diagram construction, F(2.3) Mental animation check | F(2.1) 1.5 pts F(2.2) 1.0 pts F(2.3) 0.5  pts |
| Execution | F(3.1) Degree of freedom check F(3.2) Mathematical work | F(3.1) 0.5 pts F(3.2) 1.5 pts |
| Evaluation | F(4.1) Dimensional analysis check F(4.2) Limiting cases check F(4.3) Scaling laws / order of magnitude / proportionality check F(4.4) Symmetry check | F(4.1) 0.5 pts F(4.2) 0.5 pts F(4.3) 0.5 pts F(4.4) 0.5 pts |

Note the two types of framework practice subject: questions and problems. Below is a table listing the framework components relevant for analysis and submission of both types.

## 1.2 Differences in problems and question submissions / analysis

| Phase          | Problems                    | Questions                   |
|----------------|-----------------------------|-----------------------------|
| Redescription  | F(1.1) F(1.2)               | F(1.1) F(1.2)               |
| Reconstruction | F(2.1) F(2.2) F(2.3)        | F(2.1) F(2.2) F(2.3)        |
| Execution      | F(3.1) F(3.2)               | N / A                       |
| Evaluation     | F(4.1) F(4.2) F(4.3) F(4.4) | F(4.1) F(4.2) F(4.3) F(4.4) |

> • Problems: involve phase 3 of the framework.   • Questions: do not involve phase 3 of the framework. • 0.5 of the points from phase phase 3 is allocated to F(2.2)   • 1.5 of the remaining points from phase 3 is distributed equally to F(4.1) → F(4.4)

# 2.0 Updates

## 2.1 Question Variant Format v2 (QVF V2)

The update to this question framework format is done to cut time loss, and ensure compatibility with markdown format (to make feedback generation much easier). As a consequence, the problem solving framework corresponding with this new format is as follows:

| Phase | Original Framework (max. 10.00 pts) | Question Variant Format v2 (max. 5.50 pts) | Problem Variant Format V2 (max. 7 pts) |
|----|----|----|----|
| Phase 1 | F(1.1), F(1.2) | F(1.1), F(1.2) <br>F(1.1): 1.5 pts, F(1.2): 1.5 pts | F(1.1), F(1.2) <br>F(1.1): 1.5 pts, F(1.2): 1.5 pts |
| Phase 2 | F(2.1), F(2.2), and F(2.3) | F(2.1), F(2.3)<br>F(2.1): 1.5 pts, F(2.3): 0.5 pts | F(2.1), F(2.3)<br>F(2.1): 1.75 pts, F(2.3): 0.25 pts |
| Phase 3 | F(3.1), F(3.2) | N/A | F(3.2)<br> F(3.2): 1.5 pts |
| Phase 4 | F(4.1), F(4.2), F(4.3), F(4.4) | Only one of the F(4.y); this could be F(4.1) or F(4.2) or F(4.3) or F(4.4)<br>F(4.y): 0.5 pts | Only one of the F(4.y) component.<br>F(4.y): 0.5 pts. |

> Note: In writing submission using the previous version of question variant format, i.e. the "vanilla" version of the problem solving framework applied for question submission / analysis, the user must *first* label the phase of what is to be written *before* writing. On top of that, the user must *progress methodically* from phase one to phase two, etc. In this updated variant the user is allowed to write the label *after* he / she is done with writing. And for this reason, the user is *allowed* to jump around between phases.
>
> For example, it might be natural to evoke F(4.2) or F(4.3) related techniques before F(2.1) or F(1.2) early on during problem solving; especially when the problem is nontrivial. To force the user in going "step by step" can negatively impact the user's performance. However, it is important to emphasize that beginners *should not* jump around and *have to* go over methodically.

# 3.0 Demonstration

## 3.1. Question Demo

I've decided to adapt a new  format for question approaches using my framework. The aim is to save time from question solving so that it can be allocated to real problem solving. Below is a demo of the QVF v.2 framework for Question 3 from HRK CH19 (mechanical waves). For

### Question

> How do the amplitude and the intensity of surface water waves vary with the distance from the source?

### Submission

> *The paragraph below discusses the main idea prompted by the question and also sets up simple physical constraints. Therefore it belongs to the F(1.1) and F(1.2) phase of the framework.*

Surface water wave is a 2D transverse wave (planar wave). Water wave can be visualized as a protrusion forming a ring that spreads out from the source. Define a 3D coordinate $(r, \theta, y)$ system, a planar polar coordinate to describe the "ring" and a vertical coordinate to describe the height of each local protrusion.

> *The paragraph below mentions a heuristic related to wave shape forms. This paragraph thus belong to the F(2.1) phase.*

Take a cross section of the protrusion and you'll see the familiar $y=f(r \pm vt)$ wave shape (where $v$ is the wave speed in water). Consequently, the amplitude of said wave corresponds to the height of the protrusion.

> *This paragraph attempts to convey the motion of the wave. It deserves the F(2.3) phase.*

Taking a closer look at how the wave travels through the medium reveals two proper motions: 1) the "protrusion ring" (ripples) travels away from the medium, increasing in radius as it does, and 2) a water element in the medium displaces upward by the same amount as the amplitude of the wave as it hits the element.

> *The following paragraphs contain several core heuristics related to wave intensity, power, and amplitude. Additionally, the paragraphs use scaling relations to convey these heuristics. Thus, they belong to the F(2.1) and F(4.3) phase of the framework.*

Intensity is defined as $I = P/A$ where $P$ is power and $A$ is the (surface) area. The water ripples (of radius $r$) traces out surface area $A \propto r^2$ as it travels. By this, hence the intensity varies as

$$ I \propto \frac{1}{\pi r^2} $$

Now consider the 1D water element. The power needed to displace this element is $P = \mathbf{F} \cdot \mathbf{v}$. See that the force on this infinitesimal water element can be thought of as tension that points along the surface of the water. Note that $\bf{v}$ is strictly vertical. Consequently $P = \bf{F} \cdot \bf{v}= F_y v$,

$$ P = F \sin \phi \frac{\partial y}{\partial t} = F\left(\frac{\partial y}{\partial x}\right)\left(\frac{\partial y}{\partial t}\right) $$

Hence, $P \propto I$. The amplitude varies inversely with the distance from the source.

$$ \partial y \propto \frac{1}{r} $$

> *The section below is entirely optional. Recall that our framework requires only one of the four phases from F(4.y). This section attempts to discuss the geometric relevance of the result beyond what the problem asks. Hence it belongs to F(4.4). However, since some of the preceding arguments are invalid, this section is automatically invalid.*

It's worth noting that the symmetry of a circle causes its surface area to vary as $r^2$ from the distance to the source. For other shapes, say, a square of side length $s$ its surface area vary as$s^2$. But $s$ is not the same as $r$. Technically, for a square whose center is fixed at the source, the distance of points on its sides to its center, $r$, takes range of value $(r/2, r\sqrt{2}/2)$. With $r/2$ corresponding to shortest distance and $r\sqrt{2}/2$ the longest distance (e.g. at the vertices).

### Analysis and grading

And since the submission is incorrect, below is its graded analysis from Gemini 3.1 Pro.

F(1.1) Identify major physical laws: 0.5 / 1.5 pts

You identified the phenomenon as a 2D wave, but you missed the primary physical law governing the energy distribution: the conservation of energy. You attempted to use the power equation ($P=F \cdot v$), but the foundational premise for finding intensity scaling relies on the fact that the total power output from the source remains constant as the wave expands.

F(1.2) Identify constraints, coordinates, systems: 1.0 / 1.5 pts

You correctly defined a cylindrical coordinate system ($r, \theta, y$) to model the surface ripples. However, you incorrectly constrained a surface water wave as purely transverse. Water waves are primarily surface waves, involving both longitudinal and transverse motion (particles move in elliptical orbits), though modeling it as transverse is a common, acceptable simplification for amplitude scaling in introductory contexts.

F(2.1) Heuristics / specific ideas: 0.0 / 1.5 pts

Your heuristic for deriving intensity is fundamentally flawed. You defined area as the flat surface area traced out by the ripples ($A \propto r^2$). In a 2D surface wave, the energy does not spread over a surface area; it spreads over the circumference of the expanding wavefront. Therefore, the "area" through which the power flows is a 1D boundary (a circle of length $2\pi r$).

F(2.3) Mental animation check: 0.5 / 0.5 pts

You correctly visualized the macroscopic expansion of the rings and the vertical displacement of the individual water elements.

F(4.3) Scaling laws / proportionality check: 0.0 / 0.5 pts

Intensity: Because your heuristic was flawed, your scaling is incorrect. Since power $P$ is constant and is distributed over a circumference $2\pi r$, the intensity (power per unit length of wavefront) scales as $I \propto 1/r \implies I\not \propto 1/r^2$.

Amplitude: You correctly stated that $P \propto A_{m}^2$. However, because your intensity was wrong, your final amplitude scaling is mathematically inconsistent with your own derivation. If $I \propto 1/r^2$ and $I \propto A_{m}^2$, then $A_{m}$ would scale as $1/r$. The correct physics is: $I \propto 1/r$ and $I \propto A_{m}^2$, therefore $A_{m} \propto 1/\sqrt{r}$.

Adjusted Score (Active Phases Only): 2.0 / 5.50

- Correct Answer Formulation: The key to this problem is understanding the geometry of energy conservation.
- Intensity: Assume the source emits energy at a constant power $P$. In a 2D surface wave (like ripples on a pond), this energy spreads out uniformly along the circular perimeter of the wavefront. The length of this perimeter is $2\pi r$. Therefore, the intensity (Power per unit length) is: $I = \frac{P}{2\pi r} \implies I \propto \frac{1}{r}$
- Amplitude: For any mechanical wave, the intensity is proportional to the square of the amplitude ($I \propto A_m^2$).Since we established $I \propto 1/r$, we can substitute: $A_m^2 \propto \frac{1}{r} \implies A_m \propto \frac{1}{\sqrt{r}}$.
- Conclusion: Intensity varies inversely with the distance ($1/r$).Amplitude varies inversely with the square root of the distance ($1/\sqrt{r}$).

Overall, the CPS (competitive physics score) for this submission is 0.36 (2.0/5.50)

## 3.2 Problem Demo

For a problem, the analysis uses original framework. \[To be continued\]

## 3.3 Analysis Demo

Aside from using the framework to solve problem, it can also be used to parse and "decode" solutions. For example, I've used the framework to analyze Vlad-Stefan Oros solution to Physics Cup 2022 Problem No.2. Keep in mind that this analysis was done on May 1st 2026, and was one of the major reasons why I ended up altering my framework format to be more flexible by the end of May. Below is the excerpt taken from the analysis I've written. Note that my intention was purely to parse his solution with the problem solving framework I've developed; not to determine whether his solution was correct or not.

#### Introduction

> I've analyzed how Vlad Stefan Oros wrote his solution for Physics Cup 22 problem 2. The problem was on a triangular house and the minimum time needed to circumnavigate the house. Kalda specifically mentioned that the problem involves 1) hodographs, 2) calculus of variation. Vlad predominantly used calculus of variation. In essence, this problem was really a disguised math problem.

#### Findings

> Since the problem description was rather general, he utilized F(4.3) and F(4.1) to obtain a relationship between the given variables. Vlad also described a (probable) F(2.1) heuristic. He then used F(4.4) to further reduce the cognitive load of the problem. These constraints \[F(4.3) to F(4.4)\] are later used as the basis of his F(1.2) stage. Beyond F(1.2) he laid out an idealized F(2.2) diagram for the motion around one side of the house, which is then extrapolated over all the sides.

> Then he described the main F(2.1): calculus of variation technique. Only F(3.2) is present from phase 3. In the end he provided a F(4.2) by first generalizing the expression for the triangular house (n=3) to a N sided polygon. Taking N to infinity reveals that we have a curve (which is more familiar; akin to centripetal motion).

Below is the relevant table

| Phase | Type | Count |
|----|----|----|
| Redescription | F(1.1) F(1.2) | F(1.1) Not mentioned / Assumed to be implicit. But see that this is predominantly a math problem disguised as kinematics F(1.2) There are 5 main heuristics: 1) optimal trajectory should touch all vertices due to the established F(4.3);   2) smooth, continuous trajectory due to a heuristic in F(2.1);   3) optimal trajectory uses max acceleration due to the established F(4.3);  4) there can only be one optimal trajectory due to F(4.4) related symmetries; 5) the trajectory is parabolic due to geometry relationships from F(4.4). |
| Representation | F(2.1) F(2.2) | 4 ⇔ F(2.1) 1) Trajectory must be continuous. 2) The path that it traces cannot have abrupt and jaggedness. 3) Calculus of variation, from which you get the minimized path. 4) EOM for a 2D parabolic motion. F(2.2) ⇔ a typical trajectory of a parabolic motion with a 60 degree launch angle. |
| Execution | F(3.1) F(3.2) | F(3.1) ⇔ None / assumed implicit F(3.2) ⇔ 3 1) trig identities, 2) derivatives / integration,  3) taylor series |
| Evaluation | F(4.1) F(4.2) F(4.3) F(4.4) | F(4.1) ⇔ used in conjunction with F(4.3) F(4.2) ⇔ 2 1) generalizing for N-gons,   2) taking N → infinity F(4.3) ⇔ used at the beginning to guess the form and dependance, of time with the givens. F(4.4) ⇔ 4 1) equilateral triangle symmetry, 2) trajectory is rotationally and reflectionally symmetric. This ensures that there cannot be multiple shortest trajectories.   3) symmetry in time to get from one vertex to another. 4) trajectory is symmetric with respect to perpendicular bisectors so the problem can effectively be reduced to parabolic motion. |

#### Conclusion

It is interesting to see Vlad's problem solving approach. He first deduced the relation of minimum time via F(4.1) and F(4.3) with the given quantities (friction coefficient, gravity, side length). From this he deduced several constraints. Do keep in mind that the ultimate goal of his constraints is to assume a parabolic / 2D motion trajectory. For this reason you can see him using several symmetry arguments. The big picture here is that Vlad turned this physics cup problem to a 2D kinematic problem, which happens to have a parabolic trajectory. From then on the physics is "trivial" and this turns into a "math problem", which happens to involve calculus of variation.

> I should also mention how the ordering at which the phases are found in his solution is arbitrary: each phase can precede / supersede another. Also, if you look at the physics cup website, Vlad's solution is nominated as one of the best solutions. Clearly, his submission grants him a CPS of 1.0.

# 4.0 CPR (Competitive Physics Rating)

> CPR is an Elo-inspired rating system to quantify Physics Olympiads problem solving strength.

### 4.1 Competitive Physics Score ($CPS$)

Your problem solving strength score. A maximum value of $1.0$ and minimum of $0.0$. A direct measurement of successful framework phases completion. Measured per problem sets, or ideally, per problem solved. Calculated as follows: $$CPS=\frac{Actual \ Framework \ Score}{Max\ Framework \ Score}$$\
\### 4.2 Competitive Physics Rating ($CPR$)
Your problem solving strength rating. The baseline can be calculated using the $CPS_E$ formula as I will demonstrate below. Your CPR is calculated using the formula: $$CPR=R_0+k(CPS-CPS_E)$$
\### 4.3 Expected CPS ($CPE$)
What is expected as the outcome from a solve. To explain clearly, in the spirit of original Elo system, an expected outcome is a scale from $0.0\to1.0$. With $1.0$ as having $100\%$ solve success rate. And expected outcome is calculated as follows: $$CPE=\frac{CPS_a}{CPS_a+(1-CPS_a)\times10^{(Rp-R)/254}}$$With $R$ being your current rating. I've set it so that a $200$ elo difference corresponds to $1$ standard deviation.\
>Update: per 1 August 2026, I have changed the formula for measuring $CPE$ from the one above to the following: $$CPE=\frac1{1+10^{(R_p-R)/254}}$$This is primarily done because the aforementioned formula introduced unintended penalties when a user attempts to solve higher rated problems (some $0.2\sigma-0.3\sigma$ higher rated type of problems) and, as expected, fail to meet the moving CPS average. Further, the moving CPS average will certainly be higher than what is reflective of the condition. In a sense, when a user move past solving similarly rated problems to his rating, resulting in him having a high moving cps average, to solving higher rated problems as mentioned previously, his moving cps average will naturally drop. And the previous model, unnecessarily let this natural progression be penalized with (severe) rating drops.

\### 4.4 Moving CPS Average $(CPS_a)$
The user's moving CPS average. The value gets updated per 10 solve sessions.

### 4.5 Problem Ratings $(R_p)$

An estimated rating level of a problem. This acts as the opponent's rating from the original Elo system. Some examples:
- A typical HRK exercise (which is equivalent to an HRW) is rated $800-1000$ a $\sigma$ span.
- An average HRK problem can span $1.5\sigma$ with a sizeable gap ($0.5\sigma$) between its exercise variants. So an HRK problem are rated between $1100-1400$.
- KnZhou problems, on the other hand, span a massive $3\sigma$ with each $3\sigma$ being able to solve *all of* KnZhou problems correctly while at the same time consistently obeying the framework phases requirement. Easiest KnZhou problems are also tougher than HRK problems by a decent gap, $\sigma$. All in all, KnZhou problems are rated within the range of $1600-2200$ Elo.
\### 4.6 Growth Constant ($k$)\
A constant that determines the $CPR$ growth from each solve. I'd set $k=40$ to ensure that progress can happen with minimal plateaus.
\#### 4.6.1 Some calculations:
I've done $5$ sessions of mid to high HRK problems. To be more exact, I'll display them below. Note that I categorize HRK problems into three tiers: low, mid, high. High tier problems are marked as 1400, mid tier problems are 1200, while a low tier problem stands at 1100. Moving CPS Average from previous sessions (before these 5 sessions): $0.54$ These 5 sessions average CPS: 0.69

| Problem | $CPS$ | $R_p$                                    |
|---------|-------|------------------------------------------|
| P21-19  | 0.50  | $1100+1\times1.5\sigma\implies1400$      |
| P22-19  | 1.00  | $1100+2/3\times 1.5\sigma \implies 1300$ |
| P23-19  | 1.00  | $1100+2/3\times 1.5\sigma \implies 1300$ |
| P24-19  | 0.54  | $1100+1\times 1.5\sigma \implies 1400$   |
| P26-19  | 0.40  | $1100+1/3\times 1.5\sigma \implies 1200$ |

My current rating can be determined using the expected CPS formula as follows. Do note that I will substitute the average CPS over the most recent 5 sessions as the expected CPS, and I will also use the average problem rating from the same sessions as the problem rating below. : $$0.69 = \frac{0.54}{0.54+(1-0.54)\times10^{(1320-R_p)/254}}$$ And after a little bit of algebra: $$R_p\approx1390$$
