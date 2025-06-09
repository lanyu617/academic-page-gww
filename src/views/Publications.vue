<template>
<div id="main" class="alt">
        <!-- One -->
        <section id="one">
          <div class="inner">
            <header class="major">
              <h1>Publications</h1>
            </header>
            <h4>2025</h4>
            <table>
              <tbody>
                <tr>
                  <td>
                    <a
                      href="https://journals.aps.org/pre/abstract/10.1103/PhysRevE.111.054315"
                      target="_blank"
                      style="font-weight: bold"
                      >Haoran Nan, Senquan Wang, Chun Ouyang, Yanchen Zhou,
                      Weiwei Gu. Assessing the robustness and reducibility of
                      multiplex networks with embedding-aided interlayer
                      similarities. <em>Physical Review E.</em></a
                    >
                    <br />
                    <p>
                      The study of interlayer similarity of multiplex networks
                      helps us understand the intrinsic structure of complex
                      systems, revealing how changes in one layer can propagate
                      and affect others, thus enabling broad implications for
                      transportation, social, and biological systems. Existing
                      algorithms that measure similarities between network
                      layers typically encode only partial information, which
                      limits their effectiveness in capturing the full
                      complexity inherent in multiplex networks. To address this
                      limitation, we propose an interlayer similarity measuring
                      approach named Embedding Aided Interlayer Similarity
                      (EATSim). EATSim concurrently incorporates intralayer
                      structural similarity and cross-layer anchor node
                      alignment consistency, providing a more comprehensive
                      framework for analyzing interconnected systems. Extensive
                      experiments on both synthetic and real-world networks
                      demonstrate that EATSim effectively captures the
                      underlying geometric similarities between interconnected
                      networks, significantly improving the accuracy of
                      interlayer similarity measurement. Moreover, EATSim
                      achieves state-of-the-art performance in two downstream
                      applications: predicting network robustness and network
                      reducibility, showing its great potential in enhancing the
                      understanding and management of complex systems.
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <a href="" style="font-weight: bold" target="_blank"
                      >Weiwei Gu, Chen Yang, Lei Li, Jinqiang Hou, Filippo
                      Radicchi.Deep-learning-aided dismantling of interdependent
                      networks. <em>Nature Machine Intelligence.</em></a
                    >
                    <br />
                    <p>
                      Identifying the minimal set of nodes whose removal breaks
                      a complex network apart, also referred as the network
                      dismantling problem, is a highly non-trivial task with
                      applications in multiple domains. Whereas network
                      dismantling has been extensively studied over the past
                      decade, research has primarily focused on the optimization
                      problem for single-layer networks, neglecting that many,
                      if not all, real networks display multiple layers of
                      interdependent interactions. In such networks, the
                      optimization problem is fundamentally different as the
                      effect of removing nodes propagates within and across
                      layers in a way that can not be predicted using a
                      single-layer perspective. Here, we propose a dismantling
                      algorithm named MultiDismantler, which leverages multiplex
                      network representation and deep reinforcement learning to
                      optimally dismantle multi-layer interdependent networks.
                      MultiDismantler is trained on small synthetic graphs; when
                      applied to large, either real or synthetic networks, it
                      displays exceptional dismantling performance, clearly
                      outperforming all existing benchmark algorithms. We show
                      that MultiDismantler is effective in guiding strategies
                      for the containment of diseases in social networks
                      characterized by multiple layers of social interactions.
                      Also, we show that MultiDismantler is useful in the design
                      of protocols aimed at delaying the onset of cascading
                      failures in interdependent critical infrastructures.
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <a
                      style="font-weight: bold"
                      target="_blank"
                      href="https://www.sciencedirect.com/science/article/abs/pii/S0893608025003685"
                      >Weiwei Gu, Linbi Lv, Gang Lu, Ruiqi Li. MWTP: A
                      heterogeneous multiplex representation learning framework
                      for link prediction of weak ties.
                      <em>Neural Networks.</em></a
                    >
                    <br />
                    <p>
                      Weak ties that bridge different communities are crucial
                      for preserving global connectivity, enhancing resilience,
                      and maintaining functionality and dynamics of complex
                      networks, However, making accurate link predictions for
                      weak ties remain challenging due to lacking of common
                      neighbors. Most complex systems, such as transportation
                      and social networks, comprise multiple types of
                      interactions, which can be modeled by multiplex networks
                      with each layer representing a different type of
                      connection. Better utilizing information from other layers
                      can mitigate the lack of information for predicting weak
                      ties. Here, we propose a GNN-based representation learning
                      framework for Multiplex Weak Tie Prediction (MWTP). It
                      leverages both an intra-layer and an inter-layer
                      aggregator to effectively learn and fuse information
                      across different layers. The intra-layer one integrates
                      features from multi-order neighbors, and the inter-layer
                      aggregation exploits either logit regression or a more
                      sophisticated semantic voting mechanism to compute
                      nodal-level inter-layer attentions, leading to two
                      variants of our framework, MWTP-logit, and MWTP-semantic.
                      The former one is more efficient in implementation
                      attribute to fewer parameters, while the latter one is
                      slower but has stronger learning capabilities. Extensive
                      experiments demonstrate that our MWTPs outperform eleven
                      popular baselines for predicting both weak ties and all
                      ties across diverse real-world multiplex networks.
                      Additionally, MWTPs achieve good prediction performance
                      with a relatively small training size.
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <a
                      href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13633/136330S/Predicting-methane-adsorption-ability-of-MOFs-based-on-the-crystal/10.1117/12.3067331.full"
                      style="font-weight: bold"
                      target="_blank"
                    >
                      Gang Lu, Xiuyi Jiang, Qingyuan Yang, Zhengyang Zhao,
                      Weiwei Gu, Ruiqi Li. Predicting methane adsorption ability
                      of MOFs based on the crystal structural information by
                      convolutional neural network.
                      <em
                        >Fifth International Conference on Material Science and
                        Technology (ICMST 2025).</em
                      >
                    </a>
                    <br />
                    <p>
                      High-throughput computational screening (HTCS) methods
                      have been widely used in addressing the challenges of
                      screening metal-organic framework (MOF) materials with
                      high performance from large datasets. Accurately
                      predicting the performance of MOFs with hypothetical
                      structures, such as adsorption capacity for methane, can
                      be a great help to HTCS. Traditional molecular dynamics
                      simulation methods are computationally cumbersome and
                      costly. Feature engineering-based machine learning methods
                      have a high reliance on expert experience to extract
                      effective features, some of which can be time-consuming to
                      calculate. Although some classical machine learning models
                      can already achieve good performance, the heavy burden for
                      features computation prior to model training would
                      eventually limit their practical applications, flexibility
                      and generality. In this paper, an approach is proposed for
                      predicting the methane adsorption ability of MOFs directly
                      from their crystal structural information recorded in
                      Crystallographic Information File (CIF)-formatted files,
                      without the need for molecular dynamics simulation or
                      calculating any physical or chemical properties. By
                      expressing the structural information in the crystal cells
                      of MOFs as matrices, a deep convolutional neural network
                      model based on residual structure is applied to train an
                      end-to-end model to predict their methane adsorption
                      ability. The experimental results show that the model
                      accomplishes the prediction task with high accuracy,
                      giving the mean square correlation coefficient (R2) as
                      0.925 and the mean absolute error (MAE) as 22.28 cm3g-1,
                      which demonstrates a good performance over baselines.
                    </p>
                  </td>
                </tr>
              </tbody>
            </table>
            <h4>2024</h4>
            <table>
              <tbody>
                <tr>
                  <td>
                    <a
                      href="https://arxiv.org/abs/2403.07566"
                      style="font-weight: bold"
                      target="_blank"
                      >Weiwei Gu, Senquan Wang. An Improved Strategy for Blood
                      Glucose Control Using Multi-Step Deep Reinforcement
                      Learning.
                      <em
                        >Proceedings of the 2024 16th International Conference
                        on Bioinformatics and Biomedical Technology.</em
                      ></a
                    >
                    <br />
                    <p>
                      Blood Glucose (BG) control involves kee** an individual's
                      BG within a healthy range through extracorporeal insulin
                      injections is an important task for people with type 1
                      diabetes. However,traditional patient self-management is
                      cumbersome and risky. Recent research has been devoted to
                      exploring individualized and automated BG control
                      approaches, among which Deep Reinforcement Learning (DRL)
                      shows potential as an emerging approach. In this paper, we
                      use an exponential decay model of drug concentration to
                      convert the formalization of the BG control problem, which
                      takes into account the delay and prolongedness of drug
                      effects, from a PAE-POMDP (Prolonged Action
                      Effect-Partially Observable Markov Decision Process) to a
                      MDP, and we propose a novel multi-step DRL-based algorithm
                      to solve the problem. The Prioritized Experience Replay
                      (PER) sampling method is also used in it. Compared to
                      single-step bootstrapped updates, multi-step learning is
                      more efficient and reduces the influence from biasing
                      targets. Our proposed method converges faster and achieves
                      higher cumulative rewards compared to the benchmark in the
                      same training environment, and improves the time-in-range
                      (TIR), the percentage of time the patient's BG is within
                      the target range, in the evaluation phase. Our work
                      validates the effectiveness of multi-step reinforcement
                      learning in BG control, which may help to explore the
                      optimal glycemic control measure and improve the survival
                      of diabetic patients.
                    </p>
                  </td>
                </tr>
              </tbody>
            </table>
            <h4>2023</h4>
</div>
</template>

<script setup>
// no script
</script>
