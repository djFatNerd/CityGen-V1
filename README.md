<img src="asset/logo.png" height="120px" align="right">

# CityGen: Infinite and Controllable 3D City Layout Generation

[![](http://img.shields.io/badge/cs.CV-arXiv%3A2311.15209-B31B1B.svg)](https://arxiv.org/abs/2311.15209)

> **Infinite and Controllable 3D City Layout Generation**  
> Jie Deng<sup>♠️</sup>, Wenhao Chai<sup>♠️♥️</sup>, Jianshu Guo<sup>♠️</sup>, Qixuan Huang, Wenhao Hu,Jenq-Neng Hwang, Gaoang Wang✉️   
> _arXiv 2023._  
> <sup>♠️</sup> Equal contribution. <sup>♥️</sup> Project lead.

[![](https://img.youtube.com/vi/WGP99R5UXq0/0.jpg)](https://www.youtube.com/embed/WGP99R5UXq0?si=i2LVxm3Mlw1F5WTZ)

STEVE, named after the protagonist of the game Minecraft, is our proposed framework aims to build an embodied agent based on the vision model and LLMs within an open world.

## :fire: News
* **[TBD]** : We will soon release our code, model weight, and dataset.
* **[2023.11.26]** :page_with_curl: We release the [paper](https://arxiv.org/abs/2311.15209).

<h3 align="center"> If you like our project, please give us a star ⭐ on GitHub for the latest update.</h3>

## 💡 Overview
The Vision Perception part takes images or videos, encodes them into tokens, and combines them with the tokens of Agent State and Task as input. The STEVE-13B in the Language Instruction part is used for automatic reasoning and task decomposition, and it calls the Skill Database in the form of the Query to output code as action.
![](asset/overview.png)

## 📣 Demo Video
[![](https://img.youtube.com/vi/NzJEqhIbcZg/0.jpg)](https://www.youtube.com/embed/NzJEqhIbcZg?si=_flZME4YDfok4LVn)
[![](https://img.youtube.com/vi/OWJDZGwephs/0.jpg)](https://www.youtube.com/embed/OWJDZGwephs?si=Vig4h99HPsNf95CP)
[![](https://img.youtube.com/vi/sloqnCtx4kc/0.jpg)](https://www.youtube.com/embed/sloqnCtx4kc?si=eMj_bNEHlg0wg7Py)
[![](https://img.youtube.com/vi/ziYueiXBP7A/0.jpg)](https://www.youtube.com/embed/ziYueiXBP7A?si=76TWzSlHsEeC7rv1)
[![](https://img.youtube.com/vi/6riHoiocb8k/0.jpg)](https://www.youtube.com/embed/6riHoiocb8k?si=PJC6Plb8hQQohQgI)
[![](https://img.youtube.com/vi/LualEoZ7EZQ/0.jpg)](https://www.youtube.com/embed/LualEoZ7EZQ?si=xWTxrJEnZeVRedEt)

## ✏️ Citation

If you find STEVE useful for your your research and applications, please cite using this BibTeX:

```bibtex
@article{zhao2023see,
  title={See and Think: Embodied Agent in Virtual Environment},
  author={Zhao, Zhonghan and Chai, Wenhao and Wang, Xuan and Boyi, Li and Hao, Shengyu and Cao, Shidong and Ye, Tian and Hwang, Jenq-Neng and Wang, Gaoang},
  journal={arXiv preprint arXiv:2311.15209},
  year={2023}
}
```
