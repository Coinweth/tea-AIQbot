<div>
  <div align="right">
    👆 右上角点击 <img class="ai-header-badge-img" src="r"> 告诉我，你希望这个项目继续加速开发迭代 ❤️ & ☕️
  </div>
  <h1> 🤖 Qbot </h1>
</div>

<p align="left">
    <img alt="ViewCount" valign="bottom" src="https://views.whatilearened.today/views/github/UFund-Me/Qbot.svg">
    <a href='https://github.com/MShawon/github-clone-count-badge'><img alt='GitHub Clones' valign="bottom" src='https://img.shields.io/badge/dynamic/json?color=success&label=Clone&query=count&url=https://gist.githubusercontent.com/MShawon/cf89f3274d06170b8a4973039aa6220a/raw/clone.json&logo=github'></a>
    <img alt="releases" valign="bottom" src="https://img.shields.io/github/downloads/UFund-Me/Qbot/total"> <code>since Sep 26</code>
</p>

[![CodeQL](https://github.com/UFund-Me/Qbot/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/UFund-Me/Qbot/actions/workflows/codeql-analysis.yml)
[![AutoTrade](https://github.com/UFund-Me/Qbot/actions/workflows/auto-trade.yml/badge.svg)](https://github.com/UFund-Me/Qbot/actions/workflows/auto-trade.yml)
[![Pylint](https://github.com/UFund-Me/Qbot/actions/workflows/pylint.yml/badge.svg)](https://github.com/UFund-Me/Qbot/actions/workflows/pylint.yml)
[![Coverage](https://github.com/UFund-Me/Qbot/actions/workflows/coverage.yml/badge.svg)](https://github.com/UFund-Me/Qbot/actions/workflows/coverage.yml)
<a href="https://github.com/UFund-Me/Qbot"><img src="https://img.shields.io/badge/Python-%203.8|%203.9-000000.svg?logo=Python&color=blue" alt="Python version"></a>
<a href="https://ufund-me.github.io/Qbot/#/"><img src="https://readthedocs.org/projects/pyod/badge/?version=latest" alt="Documentation status"></a>

<div align="center">
  <a href="https://github.com/UFund-Me/Qbot" target="_blank" rel="noopener">
    <picture>
      <source media="(prefers-color-scheme: dark)" alt="Qbot" srcset="https://user-images.githubusercontent.com/29084184/204598632-23c473db-92ee-4e9b-9b57-d6d95c861fdf.png" />
      <img alt="Qbot" width="224" src="https://user-images.githubusercontent.com/29084184/204598632-23c473db-92ee-4e9b-9b57-d6d95c861fdf.png" />
    </picture>
  </a>
  <div>&nbsp;</div>
  <div align="center">
    <b><font size="5">Qbot website</font></b>
    <sup>
      <a href="https://ufund-me.github.io/Qbot/#/">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">Qbot platform</font></b>
    <sup>
      <a href="https://ufund-me.github.io/Qbot/quantstats/docs/tearsheet.html">
        <i><font size="4">TRY IT OUT</font></i>
      </a>
    </sup>
  </div>
  <div>&nbsp;</div>
</div>

<div align="center">
  <p>AI智能量化投研平台</p>
</div>

>  <b>Qbot</b> is an AI-oriented automated quantitative investment platform, which aims to realize the potential, empower AI technologies in quantitative investment. Qbot supports diverse machine learning modeling paradigms. including supervised learning, market dynamics modeling, and RL.

<br>

```
🤖 Qbot = 智能交易策略 + 回测系统 + 自动化量化交易 (+ 可视化分析工具)
            |           |            |            |
            |           |            |             \_ quantstats (dashboard\online operation)
            |           |             \______________ Qbot - vnpy, pytrader, pyfunds
            |           \____________________________ BackTest - backtrader, easyquant
            \________________________________________ quant.ai - qlib, deep learning strategies
```

<br>

<div align="center">
  

</div>

## Quick Start

Qbot是一个免费的量化投研平台，提供从数据获取、交易策略开发、策略回测、模拟交易到最终实盘交易的全闭环流程。在实盘接入前，有股票、基金评测和策略回测，在模拟环境下做交易验证，近乎实盘的时延、滑点仿真。故，本平台提供GUI前端/客户端（部分功能也支持网页），后端做数据处理、交易调度，实现事件驱动的交易流程。对于策略研究部分，尤其强调机器学习、强化学习的AI策略，结合多因子模型提高收益比。

但本项目可能需要一点点python基础知识，有一点点交易经验，会更容易体会作者的初衷，解决当下产品空缺和广大散户朋友的交易痛点，现在直接免费开源出来！

```bash
cd ~ # $HOME as workspace
git clone https://github.com/UFund-Me/Qbot.git

cd Qbot
pip install -r requirements.txt

python main.py  #if run on Mac, please use 'pythonw main.py'
```

<p id="demo">
  <!-- <img width="" alt="demo" src="https://user-images.githubusercontent.com/29084184/221901048-bb1615fe-674f-40e8-b1e7-ba5db30a82a6.png"> -->
  <img width="" alt="demo" src="https://user-images.githubusercontent.com/29084184/223608757-5808e23c-86e4-4b1b-8b03-e04c8f368f5c.gif">
</p>

<details><summary>Mac系统在安装之前需要手动安装tables库的依赖hdf5，以及pythonw  </summary>

```
brew install hdf5
brew install c-blosc
export HDF5_DIR=/opt/homebrew/opt/hdf5 
export BLOSC_DIR=/opt/homebrew/opt/c-blosc
```
</details>

[![Open in Gitpod]

<!-- ![Gitpod-Ready](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod) -->

## Highlight

<table class="table table-striped table-bordered table-vcenter">
    <tbody class=ai-notebooks-table-content>
    <tr>
        <td colspan="3" rowspan="1" class="ai-notebooks-table-points ai-orange-link">
            <div class="features-2 mdl-grid">
                <h2 style="text-align:center">1. 多种交易方式：在线回测 + 模拟交易 + 实盘自动化交易</h2>
                <p>以策略研究为目标，提供多种交易方式验证策略和提高收益。</p>
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="mdl-cell mdl-cell--4-col">
                <img class="illustration_img" width="330" src="https://github.com/UFund-Me/Qbot/assets/29084184/222de589-a61f-4c45-bc5f-49de3fc2a72e"></img>
            </div>
        </td>
        <td>
            <div class="mdl-cell mdl-cell--4-col">
                <img class="illustration_img" width="330" src="https://user-images.githubusercontent.com/29084184/221901048-bb1615fe-674f-40e8-b1e7-ba5db30a82a6.png"/>
            </div>
        </td>
        <td>
            <div class="mdl-cell mdl-cell--4-col">
                <img class="illustration_img" width="330" src="https://github.com/UFund-Me/Qbot/assets/29084184/e96206ff-586a-4c6a-8f7a-cd578c8bdc43"/>
            </div>
        </td>
    </tr>
    </tbody>
</table>

<table class="table table-striped table-bordered table-vcenter">
    <tbody class=ai-notebooks-table-content>
    <tr>
        <td colspan="3" rowspan="1" class="ai-notebooks-table-points ai-orange-link">
            <div class="features-2 mdl-grid">
                <h2 style="text-align:center">2. 多种提示方式：邮件 + 飞书 + 弹窗 + 微信</h2>
                <p>这是qbot的消息提示模块，多种方式提示交易信息：交易买卖信息、每日交易收益结果、股票每日推荐等。</p>
            </div>
        </td>
    </tr>
    <tr>
        <td>
            <div class="mdl-cell mdl-cell--4-col">
                <img class="illustration_img" width="330" src="https://github.com/UFund-Me/Qbot/assets/29084184/aafff916-1945-4ae7-b836-60254ecacf76"></img>
            </div>
        </td>
        <td>
            <div class="mdl-cell mdl-cell--4-col">
                <img class="illustration_img" width="220" src="https://github.com/UFund-Me/Qbot/assets/29084184/a5cfadb5-8233-4307-ab79-6e0c0aca536d"/>
            </div>
        </td>
        <td>
            <div class="mdl-cell mdl-cell--4-col">
                <img class="illustration_img" width="330" height="150%" src="https://github.com/UFund-Me/Qbot/assets/29084184/beb5877b-e45e-45a8-afdb-1926ea2ea8a1"/>
            </div>
        </td>
    </tr>
    </tbody>
</table>

## USAGE ʕ •ᴥ•ʔ

### Installation

[Install Guide](./docs/01-新手指引/Install_guide.md) | [Online documents](https://ufund-me.github.io/Qbot/#/)

```
 ____________________________________
< Run ``./env_setup.sh`` to say hello >
 ------------------------------------
            \   ^__^
             \  (oo)\_______
                (__)\       )\/\
                    ||----w |
                    ||     ||
```

### Get Started

本项目分为前端（客户端）和后端两部分，前端由wxPython编写的轻量化GUI客户端，后端分为策略开发、策略回测 ``qbot/strategies``、股票基金评测、模拟交易、在线回测几个部分，对应于客户端从左到右的三个菜单。

#### 前端/客户端

➕ 请注意：本项目建议使用python 3.8、3.9版本，推荐使用conda搭建环境，参考 [Install Guide](./docs/01-新手指引/Install_guide.md)。

<sub>* 如果是 Win 系统使用``set``命令.</sub>

```shell
export USER_ID="admin"                   # replace your info
export PASSWORD="admin1234."             # replace your info

pip install -r requirements.txt

# if run on Mac, please use 'pythonw main.py'
python main.py
```

主要包含四个窗口，如果启动界面未显示或有问题可以参考下图中对应的启动方式。


#### 后端/服务端

1. 选基、选股助手（对应前端/客户端第二个菜单：AI选股/选基）

运行命令

```
cd investool
go build
./investool webserver
```

2. 基金策略在线分析（对应于前端/客户端第四个菜单：基金投资策略分析）

需要 node 开发环境: `npm`、`node`，

<details><summary>版本信息（作为参考）</summary>

```
▶ go version
go version go1.20.4 darwin/amd64
~
▶ node --version
v19.7.0
~
▶ npm --version
9.5.0
```

</details>

使用docker运行项目，在项目路径 `pyfunds/fund-strategies/` 下运行以下命令构建项目的docker镜像
```
docker build -t fund_strategy .
```

镜像构建完毕后运行
```
docker run -dp 8000:8000 fund_strategy --name="fund_strategy_instance"
```

等待项目启动过程中，可通过以下命令查看启动日志：
```
docker logs -f fund_strategy_instance
```

启动后，可通过`http://locahost:8000`访问网页。

## No-code operation (TODO)

<img width="" alt="dagster" src="https://user-images.githubusercontent.com/29084184/221900050-2275a6e2-5c9b-4b81-84e5-0087e8fb58ec.png">

体验下来，dagster是很适合金融数据采集、处理，还有机器学习的场景。当然这里的场景更偏向于“批处理”，“定时任务”的处理与编排。

```
dagster-daemon run &
dagit -h 0.0.0.0 -p 3000
```
## Strategy Lib 

部分未整理。。。

<div align="center">
  <b>经典策略</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>股票</b>
      </td>
      <td>
        <b>基金</b>
      </td>
      <td>
        <b>期货</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
      <ul>
        <li><a href="docs/02-经典策略/01-股票/布林线均值回归.md">布林线均值回归 ('2022)</a></li>
        <li><a href="docs/03-智能策略/">移动均线+KDJ</a></li>
        <li><a href="docs/02-经典策略/01-股票/多因子选股.md">多因子选股 ('2023)</a></li>
        <li><a href="docs/02-经典策略/01-股票/小市值.md">小市值 ('2021)</a></li>
        <li><a href="docs/02-经典策略/01-股票/指数增强.md">指数增强 ('2022)</a></li>
        <li><a href="docs/02-经典策略/01-股票/Alpha对冲.md">Alpha对冲 ('2022)</a></li>
        <li><a href="docs/02-经典策略/03-期货/网络交易.md">网格交易 ('2022)</a></li>
        <li><a href="docs/03-智能策略/拐点交易.md">拐点交易 ('2022)</a></li>
        <li><a href="docs/03-智能策略/">趋势交易</a></li>
        <li><a href="docs/03-智能策略/">海龟策略</a></li>
        <li><a href="docs/03-智能策略/">动态平衡策略</a></li>
        <li><a href="docs/03-智能策略/">阿隆指标策略</a></li>
      </ul>
      </td>
      <td>
      <ul>
        <li><a href="docs/02-经典策略/02-基金/4433法则.md">4433法则 ('2022)</a></li>
        <li><a href="docs/02-经典策略/02-基金/">对冲策略：指数型+债券型对冲</a></li>
        <li><a href="docs/02-经典策略/02-基金/">组合策略：多因子组合配置</a></li>
        <li><a href="docs/02-经典策略/02-基金/">组合策略：惠赢智能算法1</a></li>
        <li><a href="docs/02-经典策略/02-基金/">组合策略：择时多策略</a></li>
        <li><a href="docs/02-经典策略/02-基金/">组合策略：智赢多因子1</a></li>
      </ul>
      </td>
      <td>
      <ul>
        <li><a href="docs/02-经典策略/03-期货/双均线策略.md">双均线策略 ('2022)</a></li>
        <li><a href="docs/02-经典策略/03-期货/网络交易.md">网格交易 ('2022)</a></li>
      </ul>
      </td>
    </tr>
  </tbody>
</table>

<div align="center">
  <b>智能策略</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="middle">
      <td>
        <b>GBDT</b>
      </td>
      <td>
        <b>RNN</b>
      </td>
      <td>
        <b>Reinforcement Learning</b>
      </td>
      <td>
        <b>:fire: Transformer</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
        <li><b>GBDT</b></li>
        <ul>
            <li><a href="pytrader/strategies/benchmarks/XGBoost">XGBoost (KDD'2016)</a></li>
            <li><a href="pytrader/strategies/benchmarks/LightGBM">LightGBM (NIPS'2017)</a></li>
            <li><a href="">Catboost (NIPS'2018)</a></li>
        </ul>
        <li><b>BOOST</b></li>
        <ul>
            <li><a href="">DoubleEnsemble (ICDM'2020)</a></li>
            <li><a href="">TabNet (ECCV'2022)</a></li>
        </ul>
        <li><b>LR</b></li>
        <ul>
            <li><a href="pytrader/strategies/benchmarks/Linear"> Line Regression ('2020)</a></li>
        </ul>
      </td>
      <td>
        <li><b>CNN</b></li>
        <ul>
          <li><a href="pytrader/strategies/benchmarks/MLP">MLP (CVPRW'2020)</a></li>
          <li><a href="">GRU (ICCVW'2021)</a></li>
          <li><a href="">ImVoxelNet (WACV'2022)</a></li>
          <li><a href="">TabNet (AAAI'2019)</a></li>
        </ul>
        <li><b>RNN</b></li>
        <ul>
          <li><a href="pytrader/strategies/benchmarks/LSTM">LSTM (Neural Computation'2017)</a></li>
          <li><a href="">ALSTM (IJCAI'2022)</a></li>
          <li><a href="">ADARNN (KDD'2021)</a></li>
          <li><a href="">ADD (CoRL'2020)</a></li>
        </ul>
      </td>
      <td>
          <li><a href="pytrader/strategies/benchmarks/TFT">TFT (IJoF'2019)</a></li>
          <li><a href="">GATs (NIPS'2017)</a></li>
          <li><a href="">SFM (KDD'2017)</a></li>
      </td>
      <td>
          <li><a href="pytrader/strategies/benchmarks/Transformer">Transformer (NeurIPS'2017)</a></li>
          <li><a href="">TCTS (ICML'2021)</a></li>
          <li><a href="">TRA (KDD'2021)</a></li>
          <li><a href="">TCN (KDD'2018)</a></li>
          <li><a href="">IGMTF (KDD'2021)</a></li>
          <li><a href="">HIST (KDD'2018)</a></li>
          <li><a href="">Localformer ('2021)</a></li>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>

### Benchmark and Model zoo



<details><summary><em><b>👉 点击展开查看具体AI模型benchmark结果</b></em></summary>

|                | status | benchmark |   framework  | DGCNN | RegNetX | addition |   arXiv    |
|  :-----------: | :----: | :--------:|   :----:     | :---: | :-----: | :------: | :--------: |
|     GBDT       |   ✗    |     ✗     |   XGBoost    |   ✗   |    ✗    |  Tianqi Chen, et al. KDD 2016 |     ✗      |
|     GBDT       |   ✗    |     ✗     |   LightGBM   |   ✗   |    ✓    |  Guolin Ke, et al. NIPS 2017 |     ✗      |
|     GBDT       |   ✗    |     ✗     |   Catboost   |   ✗   |    ✓    |  Liudmila Prokhorenkova, et al. NIPS 2018 |     ✗      |
|     MLP        |   ✓    |     ✓     |   pytorch    |   ✗   |    ✗    |  --      |     ✗      |
|     LSTM       |   ✓    |     ✓     |   pytorch    |   ✗   |    ✗    |  Sepp Hochreiter, et al. Neural computation 1997 |  ✗  |
|    LightGBM    |   ✓    |     ✓     |   pytorch    |   ✗   |    ✗    |  --      |     ✗      |
|     GRU        |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Kyunghyun Cho, et al. 2014 |     ✗      |
|     ALSTM      |   ✗    |     ✗     |   pytorch    |   ✗   |    ✗    |  Yao Qin, et al. IJCAI 2017 |     ✗      |
|     GATs       |   ✗    |     ✓     |   pytorch    |   ✗   |    ✗    |  Petar Velickovic, et al. 2017 |     ✗      |
|     SFM        |   ✓    |     ✓     |   pytorch    |   ✗   |    ✗    |  Liheng Zhang, et al. KDD 2017 |     ✗      |
|     TFT        |   ✓    |     ✓     |   tensorflow |   ✗   |    ✗    |  Bryan Lim, et al. International Journal of Forecasting 2019 | ✗ |
|     TabNet     |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Sercan O. Arik, et al. AAAI 2019 |     ✗      |
| DoubleEnsemble |   ✓    |     ✓     |   LightGBM   |   ✗   |    ✗    |  Chuheng Zhang, et al. ICDM 2020 |     ✗      |
|     TCTS       |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Xueqing Wu, et al. ICML 2021 |     ✗      |
|  Transformer   |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Ashish Vaswani, et al. NeurIPS 2017 |     ✗      |
|  Localformer   |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Juyong Jiang, et al. |     ✗      |
|     TRA        |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Hengxu, Dong, et al. KDD 2021 |     ✗      |
|     TCN        |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Shaojie Bai, et al. 2018 |     ✗      |
|     ADARNN     |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  YunTao Du, et al. 2021 |     ✗      |
|     ADD        |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Hongshun Tang, et al.2020 |     ✗      |
|     IGMTF      |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Wentao Xu, et al.2021 |     ✗      |
|     HIST       |   ✓    |     ✗     |   pytorch    |   ✗   |    ✗    |  Wentao Xu, et al.2021 |     ✗      |


<sup>**Note:** All the about **300+ models, methods of 40+ papers** in quant.ai supported by [Model Zoo](./docs/03-智能策略/model_zoo.md) can be trained or used in this codebase.</sup>

</details>

<br>

## 开源共创、社区共建

首先，感谢自今年5月份开源以来收到广大用户的关注！我们在基础版本中开放了很多传统量化策略、深度学习、强化学习等人工智能策略和多因子库，为此，我们发起《Qbot人工智能量化交易社区共建计划》。采取以下两种方式共建共赢：

1. 内容共建：

- 在我们免费提供的<b>人工智能交易策略</b>基础上，提高SOTA指标，然后以个人所有权提交Qbot量化交易社区，作为一种策略服务提供给更多人，获取收益；
- 在我们免费提供的<b>上千个交易因子</b>基础上，应用交易因子完成策略回测、模拟交易，对交易结果好的可作为一种交易策略服务提供给更多人，获取收益；

2. 代码贡献：

- 参与本代码仓库程序设计与实现，多提交PR合并后可免费加入知识星球；
- 贡献榜单前10名可获得一年免费使用权，前3名可获得qbot进阶版终身免费使用权；

.....................................
