### Hi there 👋 

![](https://camo.githubusercontent.com/992babdffd8c74a1502de375fbdf7e4d54773242/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f53576f536b4e36447854737a71494b4571762f67697068792e676966)

<h1 align="center">Hello!! Welcome to my profile :) <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35"></h1>
<p align="center">
  <a href="https://github.com/DenverCoder1/readme-typing-svg"><img src="https://readme-typing-svg.herokuapp.com?lines=Federated+Learning;Causal+Machine+Learning;MedicalAI%20|%20Blockchain%20|%20NLP%20;Project%20Management;Always%20learning%20new%20things&center=true&width=500&height=50"></a>
</p>
<hr/>
<h4 align="center"> I am a masters student in Machine Learning at MILA, University Of Montreal. I like to Code, Design, Innovate and Experiment. I love taking up new challenges and learning new skills. I enjoy meeting new people, exchanging ideas and spreading knowledge and positivity.</h4>
<br>
<p align="center"> <img src="https://komarev.com/ghpvc/?username=sreyafrancis&label=Profile%20views&color=0e75b6&style=plastic" alt="sreyafrancis" /> </p>




### 📕 Research and Talks given during my time at MILA

| Date | Venue | Title | Reference |
|---|--|--|----|
| ... | | | |
|07/05/2021|ICLR 2021 Workshop|<details><summary>Towards Causal Federated Learning For enhanced robustness and privacy </summary><p>Federated Learning is an emerging privacy-preserving distributed machine learning approach to building a shared model by performing distributed training locally on participating devices (clients) and aggregating the local models into a global one. As this approach prevents data collection and aggregation, it helps in reducing associated privacy risks to a great extent. However, the data samples across all participating clients are usually not independent and identically distributed (non-iid), and Out of Distribution(OOD) generalization for the learned models can be poor. Besides this challenge, federated learning also remains vulnerable to various attacks on security wherein a few malicious participating entities work towards inserting backdoors, degrading the generated aggregated model as well as inferring the data owned by participating entities. In this paper, we propose an approach for learning invariant (causal) features common to all participating clients in a federated learning setup and analyze empirically how it enhances the Out of Distribution (OOD) accuracy as well as the privacy of the final learned model.</p></details> | [Talk](https://iclr.cc/virtual/2021/workshop/2148) [Paper](https://arxiv.org/pdf/2104.06557.pdf)|
|07/05/2021|ICLR 2021 Workshop|<details><summary>Gradient Masked Federated Optimization</summary><p>Federated Averaging (FedAVG) has become the most popular federated learning algorithm due to its simplicity and low communication overhead. We use simple examples to show that FedAVG has the tendency to sew together the optima across the participating clients. These sewed optima exhibit poor generalization when used on a new client with new data distribution. Inspired by the invariance principles in (Arjovsky et al., 2019; Parascandolo et al., 2020), we focus on learning a model that is locally optimal across the different clients simultaneously. We propose a modification to FedAVG algorithm to include masked gradients (AND-mask from (Parascandolo et al., 2020)) across the clients and uses them to carry out an additional server model update. We show that this algorithm achieves better accuracy (out-of-distribution) than FedAVG, especially when the data is non-identically distributed across clients.</p></details> | [Talk](https://iclr.cc/virtual/2021/workshop/2148) [Paper](https://arxiv.org/pdf/2104.10322.pdf)|
|07/08/2020| MILA Reading Group |<details><summary>Towards Learning Cell Causal-Embeddings</summary><p> We want to take advantage of the different environments (growth conditions, cell lines) present in gene expression datasets to get a better insight into the actual mechanisms that happen inside the cell. We would like to avoid relying on any explicit prior knowledge such as pathways that are always incomplete.We propose a multi-environment training procedure that aims at learning cell embeddings which are disentangled from the drug effect point of view. Our model is similar to a Conditional VAE along with an attention mechanism that can sparsely modify the prior distribution in latent space based on the environment.</p></details>|[Code](https://github.com/Bertinus/causal_cell_embedding) [Talk](https://github.com/ieee8023/medical-reading-group) [Slides](https://github.com/francissre/francissre/blob/main/MILA/CausalCEmb_Presentation.pdf) |
|09/11/2020| MAIS 2020 |<details><summary>Plastic Net - Plastic Structured Prediciton Energy Network</summary><p> No current algorithm or network can learn all the possible shapes in a scene. In this project, we take on the task of explicit representation by predicting the configuration of a graph of features with an energy network.  Using both the information encoded in the vertices and edges of the graph of simple geometric features, we find what shapes arise in a point cloud.  We've decided to work on point cloud as it the most difficult setting, and most methods in it can be generalized to one with more information.  Unlike images, semantic learning on 3D point clouds using a deep network is challenging due to the natural way data is unstructured. Hence we aim to do graph partitioning with the goal of finding the lowest cost unions, but where the result of alterations is unknown unless we compute the energy.   But also with the possibility of edge additions.  In a sense like a flow of mixed elements: if we let a node flow into a set, that element may "react" to increase or dampen the energy.   Finally, we want unsupervised learning as most use cases have no ground truth; we simply want the best solution. We hope the network architecture presented here will the reader's interest as much it did ours.</p></details>| [Paper](https://github.com/sreyafrancis/PlasticNet/blob/master/Project_Report.pdf) [Slides](https://github.com/sreyafrancis/PlasticNet/blob/master/PlasticNet_ppt.pptx) |
|10/17/2019|2019 International Conference on Distributed Computing and Knowledge Discovery (CyberC)|<details><summary>Record and Reward Federated Learning Contributions with Blockchain</summary><p>Although Federated Learning allows for participants to contribute their local data without it being revealed, it faces issues in data security and in accurately paying participants for quality data contributions. In this paper, we propose an EOS Blockchain design and workflow to establish data security, a novel validation error based metric upon which we qualify gradient uploads for payment, and implement a small example of our blockchain Federated Learning model to analyze its performance.</p></details> | [Code](https://github.com/sreyafrancis/BlockchainForFederatedLearning) [Paper](https://ieeexplore.ieee.org/abstract/document/8945913) [Slides](https://github.com/sreyafrancis/BlockchainForFederatedLearning/blob/master/IFT6055_Blockchain%2BFL/BlockchainForFederatedLearning.pdf)|
| 7/15/2019| Mila Medical Reading Group |  <details><summary> Estimating Causal Effects from High-Dimensional Observational Data in Healthcare </summary><p>Everyone wants to make better decisions. The impact of a decision on an outcome of interest is called a causal effect, and is traditionally estimated by performing randomized experiments. However, large data sources such as electronic medical records present opportunities to study causal effects of interventions that are difficult to evaluate through experiments. One example is the management of septic patients in the ICU. This typically involves performing several interventions in sequence, the choice of one depending on the outcome of others. Successfully evaluating the effect of these choices depends on strong assumptions, such as having adjusted for all confounding variables. While many argue that having high-dimensional data increases the likelihood of this assumption being true, it also introduces new challenges: the more variables we use for estimating effects, the less likely that patients who received different treatments are similar in all of them. In this talk, we will discuss causal effect estimation and treatment group overlap. We will also discuss the potential outcomes framework, classical methods for estimating causal effects, as well as new ones, tailored for working with large datasets.</p></details> | [Talk](https://github.com/ieee8023/medical-reading-group) [Slides](https://github.com/ieee8023/medical-reading-group/blob/master/slides/SreyaFrancis-CausalEffectEstimationInHealthcare.pdf) |

### 📕 Research and Talks given during my time at Panasonic AI Research Lab @Tata Elxsi

| Date | Venue | Title | Reference |
|---|--|--|----|
|  |Tutorial to the team|<details><summary>Tiny YOLO V1 performance analysis-Ways to improve execution speed in flight kit GPU  </summary><p>Analysis of ways to reduce execution speed of Tiny YOLO V1 in flightkit GPU with an in depth PrecisionLoss comparison of Tiny YOLO V1 32 to that of 16Bit.</p></details>|[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/20171113_32Vs16Bit_PrecisionLoss_comparison.pdf) |
|  |Tutorial to the team|<details><summary>YOLO execution speed improvement - optimization steps</summary><p>YOLO execution speed improvement - optimization steps as well as issues faced  </p></details> |[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/20171120_YOLOExecutionSpeedImprovement.pdf) |
|  |Tutorial to the team|<details><summary>Input data size to Accuracy relation analysis  </summary><p>  </p></details> |[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/20171130_ReducedInputSize_Experiment.pdf) |
|  |Tutorial to the team|<details><summary>Improve Darknet Software by introducing validation error  </summary><p>  </p></details> |[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/20171227_ValidationLoss.pdf) |
|  |Tutorial to the team|<details><summary>SSD MobileNet Vs YOLO - An Analysis </summary><p>  </p></details> |[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/SSD%20with%20MobileNets.pdf) |
|  |Tutorial to the team|<details><summary>Capsule Network</summary><p>  </p></details> |[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/CapsuleNetworks-converted.pdf) |
|  |Tutorial to the team|<details><summary>Using Simulation and Domain Adaptation to Improve Deep Robotic Vision</summary><p>  </p></details> |[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/DeepRoboticVision.pdf) |
|  |Tutorial to the team|<details><summary>Effects of Augmentation and Incremental Data Addition</summary><p>  </p></details> |[Slides](https://github.com/francissre/francissre/blob/main/Panasonic/Increment_experiment.pdf) |

### ⚡ Awards and Scholarships

| Year | Award/Scholarship | 
|---|--|
|2010|`Indian Certificate of Secondary Education (ICSE) Topper Award`|
|2012|`Top 0.1% in ALL India Entrance Exam`|
|2018|`Panasonic HAG Project Excellence Award`|
|2019|`Most innovative Project Lead Pana HAG`|
|2019-2021|`UdeM Fee exemption scholarship from MILA`|
|2020|`Microsoft Research Diversity Award`|
|2021|`Microsoft Research Diversity Award`|



### 🔥 Streak Stats

<p align="center"><img align="center" src="https://github-readme-stats.vercel.app/api?username=sreyafrancis&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40" alt="Sreya's Github Stats"></p>

<p align="center"><img src="https://github-readme-streak-stats.herokuapp.com/?user=candida18&theme=algolia" alt="candida18"  /></p>


## 🛠️ My Skills

### 👉 Programming languages

<p align="left"> 
  &emsp; 
  <a href="https://www.cprogramming.com/" target="_blank"> 
    <img alt="C" src="https://img.shields.io/badge/C%20-%232370ED.svg?logo=c&logoColor=white">
  </a> 
  &emsp;
  <a href="https://www.w3schools.com/cpp/" target="_blank"> 
    <img alt="C++" src="https://img.shields.io/badge/C++%20-%2300599C.svg?logo=c%2B%2B&logoColor=white">
  </a> 
  &emsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> 
     <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript%20-%23F7DF1E.svg?logo=javascript&logoColor=black">
   </a>
  &emsp;
  <a href="https://www.java.com" target="_blank"> 
    <img alt="Java" src="https://img.shields.io/badge/Java-%23007396.svg?logo=java&logoColor=white">
  </a>
  &emsp;
   <a href="https://www.python.org" target="_blank">
    <img alt="Python" src="https://img.shields.io/badge/Python%20-%2314354C.svg?logo=python&logoColor=white">
  </a>
  &emsp;
  <a href="https://www.php.net/">
    <img alt="PHP" src="https://img.shields.io/badge/PHP-%23777BB4.svg?logo=php&logoColor=white"/>
  </a>
</p>

### 👉 Frontend Development
<p align="left"> 
  &emsp; 
  <a href="https://www.w3.org/html/" target="_blank"> 
   <img alt="HTML" src="https://img.shields.io/badge/HTML5%20-%23E34F26.svg?logo=html5&logoColor=white">
  </a>   
  &emsp;
  <a href="https://www.w3schools.com/css/" target="_blank">
    <img alt="CSS" src="https://img.shields.io/badge/CSS%20-%231572B6.svg?logo=css3&logoColor=white">
  </a> 
   &emsp;
  <a href="https://getbootstrap.com" target="_blank"> 
    <img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-%23563D7C.svg?style=flat&logo=bootstrap&logoColor=white"/>
  </a>
</p>

### 👉 Databases & Cloud Hosting
<p align="left">
  &emsp;
    <a href="https://www.mysql.com/"><img alt="MySQL" src="https://img.shields.io/badge/MySQL-%2300f.svg?style=flat&llogo=mysql&logoColor=white"></a>
  &emsp;
    <a href="https://www.sqlite.org/"><img alt="SQLite" src ="https://img.shields.io/badge/sqlite-%2307405e.svg?style=flat&logo=sqlite&logoColor=white"/></a>
  &emsp;
    <a href="https://www.github.com"><img alt="GitHub Pages" src="https://img.shields.io/badge/GitHub%20Pages-%23327FC7.svg?style=flat&llogo=github&logoColor=white"></a>
  &emsp;
    <a href="https://www.heroku.com/"><img alt="Heroku" src="https://img.shields.io/badge/Heroku%20-%23430098.svg?logo=heroku&logoColor=white"></a>  
  &emsp;
    <a href="https://firebase.google.com/"><img alt="Firebase" src ="https://img.shields.io/badge/Firebase-%23316192.svg?logo=firebase&logoColor=white"></a>
 </p>
  
### 👉Graphic Designing
<p align="left">
  &emsp;
  	
  
   <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank"> 
    <img alt="Adobe Illustrator" src="https://img.shields.io/badge/Adobe Illustrator-%23FF9A00.svg?style=flat&logo=adobeillustrator&logoColor=white"/>
  </a> 
  &emsp;
  <a href="https://www.adobe.com/in/products/indesign.html" target="_blank"> 
    <img alt="Adobe Indesign" src="https://img.shields.io/badge/Adobe Indesign-%e749a0.svg?style=flat&logo=adobeindesign&logoColor=white"/> 
  </a> 
    &emsp;
  <a href="https://www.adobe.com/in/products/photoshop-lightroom.html" target="_blank"> 
    <img alt="Adobe Lightroom" src="https://img.shields.io/badge/Adobe Lightroom-%2300f.svg?style=flat&logo=adobelightroom&logoColor=white"/>
  </a>
   &emsp;
  <a href="https://www.adobe.com/in/products/premiere.html" target="_blank"> 
   <img alt="Adobe Premiere Pro" src="https://img.shields.io/badge/Adobe Premiere Pro-%2300f.svg?style=flat&logo=adobepremierepro&logoColor=white"/>
  </a>
    &emsp;
  <a href="#">
  	<img alt="Canva" src="https://img.shields.io/badge/Canva-%2300C4CC.svg?style=flat&logo=Canva&logoColor=white"/>
  </a>
 </p>

 ### 👉 Software & Tools
 
<p>
  &emsp;
    <a href="#"><img alt="Adobe" src="https://img.shields.io/badge/Adobe%20-%23FF0000.svg?logo=adobe&logoColor=white"></a>
  &emsp;
    <a href="#"><img alt="Colab" src="https://img.shields.io/badge/Colab-00b56a.svg?logo=google-colab&logoColor=white"></a>
  &emsp;
    <a href="#"><img alt="Codepen" src="https://img.shields.io/badge/Codepen-000000.svg?logo=codepen&logoColor=white"></a>
  &emsp;
    <a href="#"><img alt="Git" src="https://img.shields.io/badge/Git%20-%23F05033.svg?logo=git&logoColor=white"></a>
  &emsp;
    <a href="#"><img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"></a>
  &emsp;
    <a href="#"><img alt="Google Sheets" src="https://img.shields.io/badge/Google%20Sheets%20-%2334A853.svg?logo=google%20sheets&logoColor=white"></a>
  &emsp;
    <a href="#"><img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?logo=visual-studio-code&logoColor=white"></a>
  &emsp;
    <a href="#"><img alt="Jupyter" src="https://img.shields.io/badge/Jupyter%20-%23F37626.svg?logo=Jupyter&logoColor=white"></a>
  &emsp;
    <a href="#"><img alt="Stack Overflow" src="https://img.shields.io/badge/-Stack%20Overflow-FE7A16?logo=stack-overflow&logoColor=white"></a>
  &emsp;
</p>

<br/>

## 📊 Github Stats (Expand to View) 


<details> 
  <summary><b>💻 GitHub Profile Stats</b></summary>
  <br/>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="Sreya's Github Stats" src="https://github-readme-stats.vercel.app/api?username=sreyafrancis&show_icons=true&count_private=true&theme=algolia" height="192px"/></a>
<br/>
  &nbsp;
	  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=sreyafrancis&show_icons=true&locale=en&layout=compact&theme=algolia" alt="sreyafrancis" height="192px"/>
  <br/>
  <b>Note:</b> Top languages is only a metric of the languages my public code consists of and doesn't reflect experience or skill level.
  </p>
</details>


<details>
  <summary><b>⚡ Recent GitHub Activity</b></summary>
  <br/>
   <a href="https://github.com/sreyafrancis"><img alt="Sreya's Activity Graph" src="https://activity-graph.herokuapp.com/graph?username=sreyafrancis&custom_title=Sreya%20Francis's%20Contribution%20Graph&theme=react-dark" /></a>
  <br/>

</details>

<br/>

## 🙋‍♀️ Let's Connect
<p align="center">
  <a href="https://scholar.google.com/citations?user=gMEpjJQAAAAJ&hl=en/"><img src="https://img.icons8.com/bubbles/50/000000/web.png" alt="Website"/></a>
	<a href="mailto: sreya.francis@umontreal.ca "><img src="https://img.icons8.com/bubbles/50/000000/gmail.png" alt="Gmail"/></a>
	<a href="https://github.com/sreyafrancis"><img src="https://img.icons8.com/bubbles/50/000000/github.png" alt="GitHub"/></a>
	<a href="https://sreyafrancis.github.io"><img src="https://img.icons8.com/bubbles/50/000000/linkedin.png" alt="LinkedIn"/></a>
	<a href="https://instagram.com/sreyafrancis"><img src="https://img.icons8.com/bubbles/50/000000/instagram.png" alt="Instagram"/></a>
	
	
</p>

<hr/>

* Credit: [Francis](https://github.com/sreyafrancis)
* Last Edited on: 23/08/2021


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
