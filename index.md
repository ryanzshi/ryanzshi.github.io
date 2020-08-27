---
layout: default
title: Ryan Shi
redirect_from:
  - /en
  - /en/
---

<style>
.special {
  color: #4D97AF;
}
</style>

<img class="profile-picture" src="assets/ryan.jpg">


I research, develop, deploy, and evaluate AI for social good. [[CV]](assets/CV_Complete_Ryan_Shi.pdf)

Fei Fang makes this unworldly dream possible. I also work with Rayid Ghani and Steven Wu.

My technical research lies in data science, game theory, and reinforcement learning.

Contact: ryanshi[attt]cmu[dott]edu.

---

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

AI is easy, social good is hard. The former is shown below, the latter is a lifetime goal.

**Artificial Intelligence for Social Good: A Survey**
<br>
Zheyuan Ryan Shi, Claire Wang, Fei Fang
<br>
Working paper, 2020.
<br>
<a id="abs-ai4sg-button" onclick="absCHF('abs-ai4sg')">[Abstract]</a>[[Initial version]](https://arxiv.org/abs/2001.01818)[<b><font color="#B03A2E">[2020 Symposium on AI and Social Good @CMU]</font></b>](http://aiandsocialgood.org/aisoc20)
<div id="abs-ai4sg" style="display:none;">
<blockquote>Artificial intelligence for social good (AI4SG) is a research theme that aims to use and advance artificial intelligence to address societal issues and improve the well-being of the world. AI4SG has received lots of attention from the research community in the past decade with several successful applications. Building on the most comprehensive collection of the AI4SG literature to date with over 1000 contributed papers, we provide a detailed account and analysis of the work under the theme in the following ways. (1) We quantitatively analyze the distribution and trend of the AI4SG literature in terms of application domains and AI techniques used. (2) We propose three conceptual methods to systematically group the existing literature and analyze the eight AI4SG application domains in a unified framework. (3) We distill five research topics that represent the common challenges in AI4SG across various application domains. (4) We discuss five issues that, we hope, can shed light on the future development of the AI4SG research.</blockquote>
</div>

**Bandit Data-driven Optimization: AI for Social Good and Beyond**
<br>
Zheyuan Ryan Shi, Zhiwei Steven Wu, Rayid Ghani, Fei Fang
<br>
Working paper, 2020.
<br>
<a id="abs-bandit-button" onclick="absCHF('abs-bandit')">[Abstract]</a>[[Initial version]](https://arxiv.org/abs/2008.11707)
<div id="abs-bandit" style="display:none;">
<blockquote>The use of machine learning (ML) systems in real-world applications entails more than just a prediction algorithm. AI for social good applications, and many real-world ML tasks in general, feature an iterative process which joins prediction, optimization, and data acquisition happen in a loop. We introduce bandit data-driven optimization, the first iterative prediction-prescription framework to formally analyze this practical routine. Bandit data-driven optimization combines the advantages of online bandit learning and offline predictive analytics in an integrated framework. It offers a flexible setup to reason about unmodeled policy objectives and unforeseen consequences. We propose PROOF, the first algorithm for this framework and show that it achieves no-regret. Using numerical simulations, we show that PROOF achieves superior performance over existing baseline.</blockquote>
</div>


**Improving Efficiency of Volunteer-Based Food Rescue Operations**
<br>
Zheyuan Ryan Shi, Yiwen Yuan, Kimberly Lo, Leah Lizarondo, Fei Fang
<br>
IAAI-20: 32nd Annual Conference on Innovative Applications of Artificial Intelligence
<br>
<a id="abs-iaai20fr-button" onclick="absCHF('abs-iaai20fr')">[Abstract]</a>[[IAAI version]](https://aaai.org/ojs/index.php/AAAI/article/view/7051)[<b><font color="#B03A2E">[Deployed @412 Food Rescue]</font></b>](https://412foodrescue.org/)
<div id="abs-iaai20fr" style="display:none;">
<blockquote>Food waste and food insecurity are two challenges that coexist in many communities. To mitigate the problem, food
rescue platforms match excess food with the communities in need, and leverage external volunteers to transport the food. However, the external volunteers bring significant uncertainty to the food rescue operation. We work with a large food rescue organization to predict the uncertainty and furthermore to find ways to reduce the human dispatcher’s workload and the redundant notifications sent to volunteers. We make two main contributions. (1) We train a stacking model which predicts whether a rescue will be claimed with high precision and AUC. This model can help the dispatcher better plan for backup options and alleviate their uncertainty. (2) We develop a data-driven optimization algorithm to compute the optimal intervention and notification scheme. The algorithm uses a novel counterfactual data generation approach and the branch and bound framework. Our result reduces the number of notifications and interventions required in the food rescue operation. We are working with the organization to deploy our results in the near future.</blockquote>
</div>

**Draining the Water Hole: Mitigating Social Engineering Attacks with CyberTWEAK**
<br>
Zheyuan Ryan Shi, Aaron Schlenker, Brian Hay, Daniel Bittleston, Siyu Gao, Emily Peterson, John Trezza, Fei Fang
<br>
IAAI-20: 32nd Annual Conference on Innovative Applications of Artificial Intelligence
<br>
<a id="abs-iaai20sed-button" onclick="absCHF('abs-iaai20sed')">[Abstract]</a>[[IAAI version]](https://aaai.org/ojs/index.php/AAAI/article/view/7050)[[full version]](https://arxiv.org/abs/1901.00586)[<b><font color="#B03A2E">[Software @Chrome Web Store]</font></b>](http://bit.ly/CyberTWEAK)
<div id="abs-iaai20sed" style="display:none;">
<blockquote>Cyber adversaries have increasingly leveraged social engineering attacks to breach large organizations and threaten the well-being of today's online users. One clever technique, the "watering hole" attack, compromises a legitimate website to execute drive-by download attacks by redirecting users to another malicious domain. We introduce a game-theoretic model that captures the salient aspects for an organization protecting itself from a watering hole attack by altering the environment information in web traffic so as to deceive the attackers. Our main contributions are (1) a novel Social Engineering Deception (SED) game model that features a continuous action set for the attacker, (2) an in-depth analysis of the SED model to identify computationally feasible real-world cases, and (3) the CyberTWEAK algorithm which solves for the optimal protection policy. To illustrate the potential use of our framework, we built a browser extension based on our algorithms which is now publicly available online. The CyberTWEAK extension will be vital to the continued development and deployment of countermeasures for social engineering.</blockquote>
</div>


---

**Approximated Temporal-Induced Neural Self-Play for Finitely Repeated Bayesian Games**
<br>
Zihan Zhou, Zheyuan Ryan Shi, Yi Wu, Fei Fang
<br>
Working paper, 2020. Appeared at AAAI-20 workshop.
<br>
<a id="abs-pbne-button" onclick="absCHF('abs-pbne20')">[Abstract]</a>
<div id="abs-pbne20" style="display:none;">
<blockquote>In two-player finitely repeated Bayesian games with one-sided incomplete information, there is a natural information asymmetry among the players. In each round of the game, the player with information disadvantage needs to infer the other player’s type from their actions. The other player, knowing that their actions reveal information about themselves, will balance between playing myopically and maintaining information advantage to maximize their accumulated payoff in the long-run, which can lead to deceptive actions. Computing the Perfect Bayesian Nash Equilibrium (PBNE) in such games can be computationally intractable for large games. In this paper, we propose a new learning-based framework to approximate PBNEs, which uses non-parametric approximation and reinforcement learning from self-play. Our initial results show that it can improve the scalability over existing methods and lead to strategy profiles that are close to PBNEs.</blockquote>
</div>

**Learning and Planning in the Feature Deception Problem**
<br>
Zheyuan Ryan Shi, Ariel D. Procaccia, Kevin S. Chan, Sridhar Venkatesan, Noam Ben-Asher, Nandi O. Leslie, Charles Kamhoua, Fei Fang
<br>
Working paper, 2019. Appeared at EC-19, IJCAI-19 workshops.
<br>
<a id="abs-fdg-button" onclick="absCHF('abs-fdg19')">[Abstract]</a>[[full version]](https://arxiv.org/abs/1905.04833)
<div id="abs-fdg19" style="display:none;">
<blockquote>Today's high-stakes adversarial interactions feature attackers who constantly breach the ever-improving security measures. Deception mitigates the defender's loss by misleading the attacker to make suboptimal decisions. In order to formally reason about deception, we introduce the feature deception problem (FDP), a domain-independent model and present a learning and planning framework for finding the optimal deception strategy, taking into account the adversary's preferences which are initially unknown to the defender. We make the following contributions. (1) We show that we can uniformly learn the adversary's preferences using data from a modest number of deception strategies. (2) We propose an approximation algorithm for finding the optimal deception strategy given the learned preferences and show that the problem is NP-hard. (3) We perform extensive experiments to validate our methods and results. In addition, we provide a case study of the credit bureau network to illustrate how FDP implements deception on a real-world problem.</blockquote>
</div>



**Deep Reinforcement Learning for Green Security Games with Real-Time Information**
<br>
Yufei Wang, Zheyuan Ryan Shi, Lantao Yu, Yi Wu, Rohit Singh, Lucas Joppa, Fei Fang
<br>
AAAI-19: the Thirty-Third AAAI Conference on Artificial Intelligence
<br>
<a id="abs-aaai19-button" onclick="absCHF('abs-aaai19')">[Abstract]</a>[[AAAI version]](https://www.aaai.org/ojs/index.php/AAAI/article/view/3941)[[full version]](https://arxiv.org/abs/1811.02483) [[source code]](https://github.com/AIandSocialGoodLab/DeDOL) [[slides]](/papers/2019_AAAI_RL4SG_slides.pdf)  
<div id="abs-aaai19" style="display:none;">
<blockquote>Green Security Games (GSGs) have been proposed and applied to optimize patrols conducted by law enforcement agencies in green security domains such as combating poaching, illegal logging and overfishing. However, real-time information such as footprints and agents' subsequent actions upon receiving the information, e.g., rangers following the footprints to chase the poacher, have been neglected in previous work. To fill the gap, we first propose a new game model GSG-I which augments GSGs with sequential movement and the vital element of real-time information. Second, we design a novel deep reinforcement learning-based algorithm, DeDOL, to compute a patrolling strategy that adapts to the real-time information against a best-responding attacker. DeDOL is built upon the double oracle framework and the policy-space response oracle, solving a restricted game and iteratively adding best response strategies to it through training deep Q-networks. Exploring the game structure, DeDOL uses domain-specific heuristic strategies as initial strategies and constructs several local modes for efficient and parallelized training. To our knowledge, this is the first attempt to use Deep Q-Learning for security games.</blockquote>
</div>

**Designing the Game to Play: Optimizing Payoff Structure in Security Games**
<br>
Zheyuan Ryan Shi, Ziye Tang, Long Tran-Thanh, Rohit Singh, Fei Fang
<br>
IJCAI-ECAI-18: the 27th International Joint Conference on Artificial Intelligence and the 23rd European Conference on Artificial Intelligence.
<br>
<a id="abs-ijcai18-button" onclick="absCHF('abs-ijcai18')">[Abstract]</a>
[[IJCAI version]](https://www.ijcai.org/proceedings/2018/71) [[full version]](https://arxiv.org/abs/1805.01987) [[source code]](https://github.com/AIandSocialGoodLab/SecurityGamePayoffManipulation) [[slides]](/papers/2018_IJCAI_payoffmanipulation_slides.pdf)
<div id="abs-ijcai18" style="display:none;">
<blockquote>Effective game-theoretic modeling of defender-attacker behavior is becoming increasingly important. In many domains, the defender functions not only as a player but also the designer of the game's payoff structure. We study Stackelberg Security Games where the defender, in addition to allocating defensive resources to protect targets from the attacker, can strategically manipulate the attacker's payoff under budget constraints in weighted L^p-norm form regarding the amount of change. Focusing on problems with weighted L^1-norm form constraint, we present (i) a mixed integer linear program-based algorithm with approximation guarantee; (ii) a branch-and-bound based algorithm with improved efficiency achieved by effective pruning; (iii) a polynomial time approximation scheme for a special but practical class of problems. In addition, we show that problems under budget constraints in L^0-norm form and weighted L^\infty-norm form can be solved in polynomial time. We provide an extensive experimental evaluation of our proposed algorithms.</blockquote>
</div>


**Optimizing Peer Teaching to Enhance Team Performance**
<br>
Zheyuan Ryan Shi, Fei Fang
<br>
TEAMAS-17: First International Workshop on Teams in Multiagent Systems, at AAMAS-17
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
Zheyuan Ryan Shi, Sindhu Kutty
<br>
URTC-16: 2016 MIT IEEE Undergraduate Research Technology Conference
<br>
<a id="abs-urtc16-button" onclick="absCHF('abs-urtc16')">[Abstract]</a>
[[IEEE version]](http://ieeexplore.ieee.org/document/8284063/)
<div id="abs-urtc16" style="display:none;">
<blockquote>Prediction markets are a platform for aggregating information from a population. We perform market simulations on the exponential family models of prediction markets. We verify the market dynamics and provide some extensions to the previous models. We also consider the incentive compatibility problem in such markets with risk neutral Bayesian traders. We show that while the market is guaranteed to achieve information aggregation, whether traders express their beliefs promptly depends on their beliefs and initial market state.
</blockquote>
</div>


<footer>
<p><small>Copyright 2016 - {{site.time | date:"%Y"}} by Zheyuan Ryan Shi</small></p>
</footer>
