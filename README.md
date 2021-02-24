# TeamMeena
The repository contains the project <a href="implemented_codes"> implemented codes </a>, <a href="Report_team_Meena.pdf"> the final report </a>
<ul>
<li><a href = "implemented_codes/EDA.ipynb">EDA</a> - all sort of data vidualization and signal feature check</li>
<li><a href = "implemented_codes/Data_Imbalancing_handeling.ipynb">Data Imbalancing handle</a> - Augmentation method Linear Sampling implemented and balanced the term pretermm class</li>
<li><a href = "implemented_codes/Train_on_our_proposed_Model.ipynb">Training on our proposed model</a> - based on our proposed model gerneralised training and estimate the accuracy values</li>
</ul>


<p>We have proposed an app which can keep and show health records of a woman throughout her pregnency period. Mainly we have discussed two methods that will be diagnosed which defines whether the baby is term and preterm</p>
<ul>
  <li>Uterine Contraction analysis</li>
  <li>Urinanalysis</li>
  </ul>
## Uterine Contraction Analysis
<p>We can get the diagnosis of the term/preterm staage of pregnancy by only providing the MMG signal. As we have used supervised neural network, We have pretrained our model using the <a href="https://archive.physionet.org/physiobank/database/tpehgdb/">The Term-Preterm EHG Database (TPEHG DB)</a>
<p><i>We were unable to sync the dataset inside the repo, so we provided the dataset link</i></p>

.column {
  float: left;
  width: 50%;
  padding: 5px;
}
</style>
</head>
<body>
  
<p>In this dataset, we are having 12 channel signals as input</p>
<img src = "images/plot signals (1).png" width = 300 >
<p>We then focused on to do some feature analysis such as EMD</p>
<img src = "images/EMD.png" width = 300 >
<p>Training matrixes</p>
<div class="row">
  <div class="column">
    <img src="images/training.png" alt="Training Matrix"  style = "width:100%" >
  </div>
  <div class="column">
    <img src="images/prediction.PNG" alt="Prediction Demo"  height = "width:100%" >
  </div>
 </div>

## Urinanalysis
<p>the proposed method for urinanalysis using AI</p>
<img src = "images/urine.png" height = 400>
