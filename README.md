<h1 align="center">Chameleon: Episodic Memory for Long-Horizon Robotic Manipulation</h1>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/arXiv-TBD-b31b1b?logo=arxiv&logoColor=white" alt="arXiv" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Project_Page-TBD-2ea44f?logo=googlechrome&logoColor=white" alt="Project Page" /></a>
  <a href="https://github.com/gxyes/MARS_Chameleon"><img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white" alt="Code" /></a>
  <img src="https://komarev.com/ghpvc/?username=gxyes&repo=MARS_Chameleon&color=blueviolet" alt="Visitors" />
</p>

<p align="center">
  <strong>Xinying Guo</strong><sup>1,2,‡</sup>,
  <strong>Chenxi Jiang</strong><sup>1,‡</sup>,
  <strong>Hyun Bin Kim</strong><sup>1</sup>,
  <strong>Ying Sun</strong><sup>2</sup>,
  <strong>Yang Xiao</strong><sup>1</sup>,
  <strong>Yuhang Han</strong><sup>3</sup>,
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
  <img src="./images/fig-motivation.png" alt="Chameleon teaser figure" width="76%" />
</p>

<table align="center">
  <tr>
    <td valign="top" width="78%">
      <b>Abstract.</b> Robotic manipulation often requires memory: occlusion and state changes can make decision-time observations perceptually aliased, making action selection non-Markovian at the observation level because the same observation may arise from different interaction histories. Most embodied agents implement memory via semantically compressed traces and similarity-based retrieval, which discards disambiguating fine-grained perceptual cues and can return perceptually similar but decision-irrelevant episodes. Inspired by human episodic memory, we propose <b>Chameleon</b>, which writes geometry-grounded multimodal tokens to preserve disambiguating context and produces goal-directed recall through a differentiable memory stack. We also introduce <b>Camo-Dataset</b>, a real-robot UR5e dataset spanning episodic recall, spatial tracking, and sequential manipulation under perceptual aliasing. Across tasks, Chameleon consistently improves decision reliability and long-horizon control over strong baselines in perceptually confusable settings.
      <br /><br />
      <img src="./images/mars_lablogo.png" alt="MARS Lab Logo" width="76" align="right" />
      <b>Correspondence:</b> Jianfei Yang at <a href="mailto:jianfei.yang@ntu.edu.sg">jianfei.yang@ntu.edu.sg</a>
    </td>
  </tr>
</table>

<p align="center">
  <img src="./images/fig-method.png" alt="Chameleon method overview" width="64%" />
</p>

<p align="center">
  <i>Code coming soon.</i>
</p>
