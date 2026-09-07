<h1 align="center">Chameleon: Episodic Memory for Long-Horizon Robotic Manipulation</h1>

<p align="center">
  <a href="https://arxiv.org/pdf/2603.24576"><img src="https://img.shields.io/badge/arXiv-2603.24576-b31b1b?logo=arxiv&logoColor=white" alt="arXiv" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Project_Page-TBD-2ea44f?logo=googlechrome&logoColor=white" alt="Project Page" /></a>
  <a href="https://github.com/gxyes/MARS_Chameleon"><img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white" alt="Code" /></a>
  <img src="https://komarev.com/ghpvc/?username=gxyes&repo=MARS_Chameleon&color=blueviolet" alt="Visitors" />
</p>

<p align="center">
  <strong>Xinying Guo</strong><sup>1,2,‡</sup>,
  <strong>Chenxi Jiang</strong><sup>1,‡</sup>,
  <strong>Hyun Bin Kim</strong><sup>1</sup>,
  <strong>Yuhang Han</strong><sup>3</sup>,
  <strong>Ying Sun</strong><sup>2</sup>,
  <strong>Yang Xiao</strong><sup>1</sup>,
  <strong>Jianfei Yang</strong><sup>1,†</sup>
</p>

<p align="center">
  <sup>1</sup>MARS Lab, Nanyang Technological University, Singapore<br />
  <sup>2</sup>Institute for Infocomm Research, A*STAR, Singapore<br />
  <sup>3</sup>National University of Singapore
</p>

<p align="center">
  <sup>‡</sup>Equal Contribution&nbsp;&nbsp;&nbsp;
  <sup>†</sup>Corresponding Author
</p>

<p align="center">
  <img src="./images/fig-motivation.png" alt="Chameleon teaser figure" width="78%" />
</p>

<table align="center" width="78%">
  <tr>
    <td valign="top">
      <b>Abstract.</b> Robots often observe information that determines a future action long before that action is executed. In a shell game, for example, a robot first sees which cup hides the ball, watches the cups move, and only later needs to choose the correct cup. The final observation alone is not enough for a decision: the correct action depends on an earlier event. We refer to this temporal gap as observation–action delay. It makes memory a policy-facing problem: a policy must keep similar histories distinct, retrieve the past event relevant to the current decision, and convert that recall into an action-ready state. We call these requirements separability, addressability, and prospectiveness. We introduce Chameleon, a ∼60M visuomotor policy for control-indexed prospective memory. Chameleon writes embodied event memory, preserves separable histories, retrieves control-relevant traces, and trains the resulting working state to be prospective. We also introduce Camo-Dataset, a real-robot benchmark that isolates observation–action delay by making the decision scene visually ambiguous, so the correct action must be inferred from earlier observations. Chameleon improves decision/end-to-end success on Camo-Dataset from 22.5%/21.3% to 80.8%/71.3%. On public long-horizon memory benchmarks, it achieves 87.1%±0.8% on LIBERO-10, 97.3%±4.5% on MemoryBench, and 75.1%±1.4% on MIKASA-Robo, setting the state of the art for same-size models and exceeding multiple larger VLA baselines under the reported protocols. Probes and ablations show that Chameleon learns separable, addressable, and prospective memory, and that these properties drive its performance gains.
      <br /><br />
      <img src="./images/mars_lablogo.png" alt="MARS Lab Logo" width="76" align="right" />
      <b>Correspondence:</b> Jianfei Yang at <a href="mailto:jianfei.yang@ntu.edu.sg">jianfei.yang@ntu.edu.sg</a>
    </td>
  </tr>
</table>

<p align="center">
  <i>🎉 Accepted to CoRL 2026! We are excited to share our work with the community.</i>
</p>

<p align="center">
  <i>Code coming soon.</i>
</p>
