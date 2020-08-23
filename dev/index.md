---
layout: default
title: Ryan Shi
---
<!-- ## About Me -->

<style>
.special {
  <!-- color: #28B463; -->
  color: #4D97AF;
}
</style>

<img class="profile-picture" src="assets/ryan.jpg">

I am a first-year PhD student in [Societal Computing](http://sc.isri.cmu.edu/) in the [School of Computer Science](https://www.scs.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/). I am very fortunate to be advised by Prof. [Fei Fang](https://feifang.info/). Prior to CMU, I graduated from [Swarthmore College](https://www.swarthmore.edu/) with a B.A. in Mathematics and Computer Science. My CV can be found [here](/assets/RS_CV_web.pdf).

I try to develop AI for social good.






<script>
function absCHF(Id) {
    var x = document.getElementById(Id);
    if (x.style.display === "none") {
        x.style.display = "block";
    } else {
        x.style.display = "none";
    }
}
</script>



## Publications



## Previous Publications
**Deep Reinforcement Learning for Green Security Games with Real-Time Information**
<br>
Yufei Wang, **Zheyuan Ryan Shi**, Lantao Yu, Yi Wu, Rohit Singh, Lucas Joppa, and Fei Fang
<br>
In AAAI-19: the Thirty-Third AAAI Conference on Artificial Intelligence
<br>
<a id="abs-aaai19-button" onclick="absCHF('abs-aaai19')">[Abstract]</a>[[full version]](https://arxiv.org/abs/1811.02483) [AAAI version and source code to be available soon]
<div id="abs-aaai19" style="display:none;">
<blockquote>Green Security Games (GSGs) have been proposed and applied to optimize patrols conducted by law enforcement agencies in green security domains such as combating poaching, illegal logging and overfishing. However, real-time information such as footprints and agents' subsequent actions upon receiving the information, e.g., rangers following the footprints to chase the poacher, have been neglected in previous work. To fill the gap, we first propose a new game model GSG-I which augments GSGs with sequential movement and the vital element of real-time information. Second, we design a novel deep reinforcement learning-based algorithm, DeDOL, to compute a patrolling strategy that adapts to the real-time information against a best-responding attacker. DeDOL is built upon the double oracle framework and the policy-space response oracle, solving a restricted game and iteratively adding best response strategies to it through training deep Q-networks. Exploring the game structure, DeDOL uses domain-specific heuristic strategies as initial strategies and constructs several local modes for efficient and parallelized training. To our knowledge, this is the first attempt to use Deep Q-Learning for security games.</blockquote>
</div>

**Designing the Game to Play: Optimizing Payoff Structure in Security Games**
<br>
**Zheyuan Ryan Shi**\*, Ziye Tang\*, Long Tran-Thanh, Rohit Singh, and Fei Fang
<br>
In IJCAI-ECAI-18: the 27th International Joint Conference on Artificial Intelligence and the 23rd European Conference on Artificial Intelligence.
<br>
<a id="abs-ijcai18-button" onclick="absCHF('abs-ijcai18')">[Abstract]</a>
[[IJCAI version]](https://www.ijcai.org/proceedings/2018/71) [[full version]](https://arxiv.org/abs/1805.01987) [[source code]](https://github.com/AIandSocialGoodLab/SecurityGamePayoffManipulation)
<div id="abs-ijcai18" style="display:none;">
<blockquote>Effective game-theoretic modeling of defender-attacker behavior is becoming increasingly important. In many domains, the defender functions not only as a player but also the designer of the game's payoff structure. We study Stackelberg Security Games where the defender, in addition to allocating defensive resources to protect targets from the attacker, can strategically manipulate the attacker's payoff under budget constraints in weighted L^p-norm form regarding the amount of change. Focusing on problems with weighted L^1-norm form constraint, we present (i) a mixed integer linear program-based algorithm with approximation guarantee; (ii) a branch-and-bound based algorithm with improved efficiency achieved by effective pruning; (iii) a polynomial time approximation scheme for a special but practical class of problems. In addition, we show that problems under budget constraints in L^0-norm form and weighted L^\infty-norm form can be solved in polynomial time. We provide an extensive experimental evaluation of our proposed algorithms.</blockquote>
</div>


**Optimizing Peer Teaching to Enhance Team Performance**
<br>
**Zheyuan Ryan Shi** and Fei Fang
<br>
In TEAMAS-17: First International Workshop on Teams in Multiagent Systems, at AAMAS-17
<br>
In Autonomous Agents and Multiagent Systems: AAMAS 2017 Workshops, Best Papers, Springer.
<br>
<b><font color="#B03A2E">Winner of Best Paper</font></b>
<br>
<a id="abs-teamas17-button" onclick="absCHF('abs-teamas17')">[Abstract]</a>
[[Springer version]](https://link.springer.com/chapter/10.1007/978-3-319-71682-4_9)
<div id="abs-teamas17" style="display:none;">
<blockquote>Collaboration among human agents with different expertise and capabilities is becoming increasingly pervasive and important for developing new products, providing patient-centered health care, propelling scientific advance, and solving social issues. When the roles of the agents in such collaborative teamwork are highly interdependent, the performance of the team will rely not only on each team member’s individual capabilities but also on their shared understanding and mutual support. Without any understanding in other team members’ area of expertise, the team members may not be able to work together efficiently due to the high cost of communication and the individual decisions made by different team members may even lead to undesirable results for the team. To improve collaboration and the overall performance of the team, the team members can teach each other and learn from each other, and such peer-teaching practice has shown to have great benefit in various domains such as interdisciplinary research collaboration and collaborative health care. However, the amount of time and effort the team members can spend on peer-teaching is often limited. In this paper, we focus on finding the best peer teaching plan to optimize the performance of the team, given the limited teaching and learning capacity. We (i) provide a formal model of the Peer Teaching problem; (ii) present hardness results for the problem in the general setting, and the subclasses of problems with additive utility functions and submodular utility functions; (iii) propose a polynomial time exact algorithm for problems with additive utility function, as well as a polynomial time approximation algorithm for problems with submodular utility functions.</blockquote>
</div>

**Strategic Reporting in Exponential Family Prediction Markets**
<br>
**Zheyuan Ryan Shi** and Sindhu Kutty
<br>
In URTC-16: 2016 MIT IEEE Undergraduate Research Technology Conference
<br>
<a id="abs-urtc16-button" onclick="absCHF('abs-urtc16')">[Abstract]</a>
[[IEEE version]](http://ieeexplore.ieee.org/document/8284063/)
<div id="abs-urtc16" style="display:none;">
<blockquote>Prediction markets are a platform for aggregating information from a population. We perform market simulations on the exponential family models of prediction markets. We verify the market dynamics and provide some extensions to the previous models. We also consider the incentive compatibility problem in such markets with risk neutral Bayesian traders. We show that while the market is guaranteed to achieve information aggregation, whether traders express their beliefs promptly depends on their beliefs and initial market state.
</blockquote>
</div>


---
<!-- <h1 class="owner-name">About</h1> -->

<!-- {{site.about}} -->

<div class="pagination">
  {% if site.owner.linkedin %}
    <a href="{{ site.owner.linkedin }}" class="social-media-icons"><i class="fa fa-2x fa-linkedin" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.email %}
    <a href="mailto:{{ site.owner.email }}" class="social-media-icons"><i class="fa fa-2x fa-envelope" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.twitter %}
    <a href="{{ site.owner.twitter }}" class="social-media-icons"><i class="fa fa-2x fa-twitter" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.github %}
    <a href="{{ site.owner.github }}" class="social-media-icons"><i class="fa fa-2x fa-github" aria-hidden="true"></i></a>
  {% endif %}
  {% if site.owner.stackexchange %}
    <a href="{{ site.owner.stackexchange }}" class="social-media-icons"><i class="fa fa-2x fa-stack-overflow" aria-hidden="true"></i></a>
  {% endif %}
</div>
<br>
<footer>
  <!-- <p><small>Copyright 2016 - {{site.time | date:"%Y"}} by <a href="https://zheyuan.me">Zheyuan Ryan Shi</a> | Last updated: <span class="label label-info">{{site.time | date:"%Y-%m-%d %H:%M:%S"}}</span> | Theme adapted from <a href="http://irenechen.net">Irene Chen</a></small></p> -->
<p><small>Copyright 2016 - {{site.time | date:"%Y"}} by <a href="{{ site.url }}">Zheyuan Ryan Shi</a> | Last updated: <span class="label label-info">{{site.time | date:"%Y-%m-%d %H:%M:%S"}}</span> | <a href="{{ site.url }}/fun">My previous life </a> </small></p>
</footer>
