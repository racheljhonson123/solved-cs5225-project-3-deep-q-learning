Download Link: https://assignmentchef.com/product/solved-cs5225-project-3-deep-q-learning
<br>
In this project, you will be asked to implement DQN to play <a href="https://gym.openai.com/envs/Breakout-v0/" rel="nofollow">Breakout</a>. This project will be completed in Python 3 using <a href="https://pytorch.org/" rel="nofollow">Pytorch</a>. The goal of your training is to get averaging reward in 100 episodes over <strong>40 points</strong> in <strong>Breakout</strong>, with OpenAI’s Atari wrapper &amp; unclipped reward. For more details, please see the <a href="https://docs.google.com/presentation/d/1CbYqY5DfXQy4crBw489Tno_K94Lgo7QwhDDnEoLYMbI/edit?usp=sharing" rel="nofollow">slides</a>.

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project3/metarials/project3.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project3/metarials/project3.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project3/metarials/project3.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>

<h2><a id="user-content-deliverables" class="anchor" href="https://github.com/bucky1995/CS_525_RL/tree/master/Project-3#deliverables" aria-hidden="true"></a>Deliverables</h2>

Please compress all the below files into a zipped file and submit the zip file (firstName_lastName_hw3.zip) to Canvas.

<ul>

 <li><strong>Trained Model</strong>

  <ul>

   <li>Model file</li>

   <li>If your model is too large for Canvas, upload it to a cloud space and write download.sh to download the model</li>

  </ul></li>

 <li><strong>PDF Report</strong>

  <ul>

   <li>Set of Experiments Performed:

    <ul>

     <li>Include a section describing the set of experiments that you performed</li>

     <li>what structures you experimented with (i.e., number of layers, number of neurons in each layer)</li>

     <li>what hyperparameters you varied (e.g., number of epochs of training, batch size and any other parameter values, weight initialization schema, activation function)</li>

     <li>what kind of loss function you used and what kind of optimizer you used.</li>

    </ul></li>

   <li>Special skills: Include the skills which can improve the generation quality. Here are some <a href="https://arxiv.org/pdf/1710.02298.pdf" rel="nofollow">tips</a> may help. (Optional)</li>

   <li>Visualization: Learning curve of DQN.

    <ul>

     <li>X-axis: number of time steps</li>

     <li>Y-axis: average reward in last 30 episodes.</li>

    </ul></li>

  </ul></li>

 <li><strong>Python Code</strong>

  <ul>

   <li>All the code you implemented including sample codes.</li>

  </ul></li>

</ul>

<ul>

 <li style="list-style-type: none;"></li>

</ul>

<h2><a id="user-content-hints" class="anchor" href="https://github.com/bucky1995/CS_525_RL/tree/master/Project-3#hints" aria-hidden="true"></a>Hints</h2>

<ul>

 <li><a href="https://github.com/huiminren/DS595CS525-RL-HW/blob/master/project3/metarials/Pytorch_tutorial.ipynb">Naive Pytorch Tutorial</a></li>

 <li><a href="https://pytorch.org/tutorials/" rel="nofollow">Official Pytorch Tutorial</a></li>

 <li><a href="https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html" rel="nofollow">Official DQN Pytorch Tutorial</a></li>

 <li><a href="https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf" rel="nofollow">Official DQN paper</a></li>

 <li><a href="https://arxiv.org/pdf/1710.02298.pdf" rel="nofollow">Rainbow: Combining Improvements in Deep Reinforcement Learning</a></li>

 <li><a href="https://medium.com/@jonathan_hui/rl-dqn-deep-q-network-e207751f7ae4" rel="nofollow">DQN Tutorial on Medium</a></li>

</ul>