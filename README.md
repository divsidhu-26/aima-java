# AIMA4e-Java (JDK 8+)
Java implementation of algorithms from Norvig And Russell's "Artificial Intelligence - A Modern Approach 4th Edition."

---
## NOTE: This is an in progress complete rewrite of the algorithms, leveraging JDK 8's new language features, from the AIMA3e branch (currently master branch)
## TODO (REMEMBER - KEEP IT SIMPLE SIMPLE SIMPLE!!!! :)
### CURRENT (new demo GUI)
* Mock up screen prototypes
* Tree-Search demo
* Graph-Search demo

### LATER

#### Chapter 3 'core' module.
* Uniform-Cost-Search need a better mechanism for determining state containment in the
  queue and remove a node with a higher state cost.
* Recursive-Best-First-Search - look to improve/tidy up implementation.
* BasicRecursiveBestFirstSearchTest
* 3 	92	Best-First search
* 3 	92	Greedy best-First search
* 3 	93	A* search
* 3 	90	Bidirectional search
* BasicIterativeDeepeningSearchTest
* BasicDepthLimitedSearchTest
* BasicDepthFirstSearchTest
* BasicUniformCostSearchTest
* BreadthFirstSearchTest - additional tests.
* BasicGraphSearchTest
* BasicTreeSearchTest
* BasicProblemTest
* BasicSimpleProblemSolvingAgentTest
* 3.2 	68	Romania

#### Chapter 2 'core' module.
* BasicModelBasedReflexAgentTest
* BasicTableDrivenAgentTest

#### Chapter 2 'extra' module.
* Environment defintion: Consider specifying Dimensions in API, see pg. 42.
* Environment Simulator referenced on pg. 45 (this will be a refactor of the a lot of the environment stuff
  in aima3e-core).

---

## Index of Implemented Algorithms
<table style="width:100%">
   <tbody>
   <tr>
       <td><b>Fig</b></td>
       <td><b>Page</b></td>
       <td><b>Name (in book)</b></td>
       <td><b>Code</b></td>
   </tr>
   <tr>
       <td>2.1</td>
       <td>35</td>
       <td>Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/agent/Agent.java">Agent</a></td>
   </tr>
   <tr>
       <td>2.3</td>
       <td>36</td>
       <td>Table-Driven-Vacuum-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/environment/vacuum/agent/TableDrivenVacuumAgent.java">TableDrivenVacuumAgent</a></td>
   </tr>
   <tr>
       <td>2.7</td>
       <td>47</td>
       <td>Table-Driven-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/agent/TableDrivenAgent.java">TableDrivenAgent</a></td>
   </tr>
   <tr>
       <td>2.8</td>
       <td>48</td>
       <td>Reflex-Vacuum-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/environment/vacuum/agent/ReflexVacuumAgent.java">ReflexVacuumAgent</a></td>
   </tr>
   <tr>
       <td>2.10</td>
       <td>49</td>
       <td>Simple-Reflex-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/agent/SimpleReflexAgent.java">SimpleReflexAgentProgram</a></td>
   </tr>
   <tr>
       <td>2.12</td>
       <td>51</td>
       <td>Model-Based-Reflex-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/agent/ModelBasedReflexAgent.java">ModelBasedReflexAgentProgram</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>66</td>
       <td>Problem</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/Problem.java">Problem</a></td>
   </tr>
   <tr>
       <td>3.1</td>
       <td>67</td>
       <td>Simple-Problem-Solving-Agent</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/agent/SimpleProblemSolvingAgent.java">SimpleProblemSolvingAgent</a></td>
   </tr>
   <tr>
       <td>3.2</td>
       <td>68</td>
       <td>Romania</td>
       <td>---</td>
   </tr>
   <tr>
       <td>3.7</td>
       <td>77</td>
       <td>Tree-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/TreeSearch.java">TreeSearch</a></td>
   </tr>
   <tr>
       <td>3.7</td>
       <td>77</td>
       <td>Graph-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/GraphSearch.java">GraphSearch</a></td>
   </tr>
   <tr>
       <td>3.10</td>
       <td>79</td>
       <td>Node</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/Node.java">Node</a></td>
   </tr>
   <tr>
       <td>3.11</td>
       <td>82</td>
       <td>Breadth-First-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/uninformed/BreadthFirstSearch.java">BreadthFirstSearch</a></td>
   </tr>
   <tr>
       <td>3.14</td>
       <td>84</td>
       <td>Uniform-Cost-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/uninformed/UniformCostSearch.java">UniformCostSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>85</td>
       <td>Depth-first Search</td>
       <td>---</td>
   </tr>
   <tr>
       <td>3.17</td>
       <td>88</td>
       <td>Depth-Limited-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/uninformed/DepthLimitedSearch.java">DepthLimitedSearch</a></td>
   </tr>
   <tr>
       <td>3.18</td>
       <td>89</td>
       <td>Iterative-Deepening-Search</td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/uninformed/IterativeDeepeningSearch.java">IterativeDeepeningSearch</a></td>
   </tr>
   <tr>
       <td>3</td>
       <td>92</td>
       <td>Best-First search</td>
       <td>---</td>
   </tr>
   <tr>
       <td>3</td>
       <td>92</td>
       <td>Greedy best-First search</td>
       <td>---</td>
   </tr>
   <tr>
       <td>3</td>
       <td>93</td>
       <td>A* Search</td>
       <td>---</td>
   </tr>
   <tr>
       <td>3.26</td>
       <td>99</td>
       <td>Recursive-Best-First-Search </td>
       <td><a href="https://github.com/ctjoreilly/aima-java/blob/AIMA4e/core/src/main/java/aima/core/api/search/informed/RecursiveBestFirstSearch.java">RecursiveBestFirstSearch</a></td>
   </tr>
   </tbody>
</table>

---

## USEFUL RESOURCES
### GUI
* http://docs.oracle.com/javase/8/javase-clienttechnologies.htm
* https://bitbucket.org/controlsfx/controlsfx/overview
* https://bitbucket.org/Jerady/fontawesomefx
* http://fortawesome.github.io/Font-Awesome/get-started/
* http://www.pythontutor.com/
* https://svgsalamander.java.net/docs/use.html
* http://blog.netopyr.com/2012/03/09/creating-a-sprite-animation-with-javafx/
* http://www.mrlonee.com/?p=319
* http://harmoniccode.blogspot.com/
* https://rterp.wordpress.com/2014/07/28/adding-custom-javafx-component-to-scene-builder-2-0-part-2/

