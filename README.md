Reinforcement Learning for Flappy Bird in JS
===================

<img src="https://raw.githubusercontent.com/nileshsah/reinforcement-learning-flappybird/master/images/high-score.png" width="256" height="256"/>

A project aimed to explain reinforcement learning in the most simplistic way ever possible by training a _32px by 32px_ game of flappy bird using Q-learning through a script written purely in JavaScript.

一个旨在以尽可能简单的方式解释强化学习的项目，通过使用纯 JavaScript 编写的脚本，利用 Q 学习训练一个32 像素 ×32 像素的 flappy bird 游戏。

The script [`js/brain.js`](js/brain.js) is where the learning logic resides and has been documented heavily to explain the baseline Q-learning algorithm from scratch and how it can be applied in a real-time scenario.

脚本js/brain.js是学习逻辑所在之处，并且有大量文档解释了从零开始的基本 Q 学习算法以及它如何在实时场景中应用。

With everything written solely in JS, the game can be trained and tested right inside our browser with no external dependencies at all. You can witness how the bird learns to play the game in real-time by visiting the link:  [`http://nileshsah.github.io/reinforcement-learning-flappybird/`](http://nileshsah.github.io/reinforcement-learning-flappybird/) ¯\\_(ツ)_/¯

由于所有内容都是用 JS 单独编写的，因此可以在我们的浏览器内部直接训练和测试游戏，完全没有外部依赖。通过访问链接http://nileshsah.github.io/reinforcement-learning-flappybird/，你可以实时见证小鸟如何学会玩这个游戏。

In an ideal scenario, the bird learns to operate upon a static non-volatile environment in mere 25 trials of the game while for a randomized environment it might take up to 1000+ trials.

在理想情况下，小鸟在仅仅 25 次游戏试验中就能学会在静态非易失性环境中操作，而对于随机环境，可能需要多达 1000 多次试验。

### Further Reading
---

`[1]` http://people.revoledu.com/kardi/tutorial/ReinforcementLearning/

`[2]` https://medium.com/emergent-future/simple-reinforcement-learning-with-tensorflow-part-0-q-learning-with-tables-and-neural-networks-d195264329d0

`[3]` https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf











