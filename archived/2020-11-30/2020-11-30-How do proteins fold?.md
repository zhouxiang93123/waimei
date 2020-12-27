---
layout: post
title: "How do proteins fold?"
date: 2020-11-30T17:09:43.000Z
author: 经济学人en
from: https://www.economist.com/science-and-technology/2020/11/30/how-do-proteins-fold
tags: [ 经济学人en ]
categories: [ 经济学人en ]
---
<!--1606756183000-->
[How do proteins fold?](https://www.economist.com/science-and-technology/2020/11/30/how-do-proteins-fold)
------

<div>
<img src="https://images.weserv.nl/?url=www.economist.com/img/b/1280/720/90/sites/default/files/20201205_STP501.jpg"/><div></div><aside ><div ><time itemscope="" itemType="http://schema.org/DateTime" dateTime="2020-11-30T00:00:00Z" >Nov 30th 2020</time><meta itemProp="author" content="The Economist"/></div></aside><p >TO UNDERSTAND LIFE, you must understand proteins. These long, convoluted molecular chains—each assembled from a menu of 20 types of chemical links called amino acids—are the worker ants of biology. Proteins, in the guise of enzymes, catalyse almost all of the chemical reactions that keep bodies running. Actin and myosin, the proteins of muscles, permit those bodies to move around. Keratin provides their skin and hair. Haemoglobin carries their oxygen. Insulin regulates their metabolism. And it is a protein, SARS-CoV-2 spike, that allows a certain type of coronavirus to invade human cells, thereby shutting down entire economies.</p><p >Analysing a protein’s amino-acid composition is now easy. Machines to do so have existed for decades. But this is only half the battle in the quest to understand how proteins work. For what a protein does, and how it does it, depends also on how its amino-acid chain folds up after its creation, into its final, intricate shapes.</p><div id="" ><div><div id="econ-1"></div></div></div><p >At the moment, molecular biologists can probe proteins’ shapes experimentally, using techniques like X-ray crystallography, but doing so is fiddly and time-consuming process. Now, things may be about to get much easier. On November 30th researchers afrom DeepMind, an artificial-intelligence (AI) laboratory owned by Alphabet, Google’s parent company, presented results suggesting that they have made enormous progress on one of biology’s grand challenges—how to use a computer to predict a protein’s shape from a list of its amino-acid components.</p><h2>Chain gangs</h2><p >To non-biologists, this may sound somewhere between arcane and prosaic. In fact, it is a big achievement. Replacing months of experiments with a few hours of computing time could shed new light on the inner workings of cells. It could speed up drug development. And it could in particular suggest treatments for diseases like Alzheimer’s, in which misshapen proteins are thought to play a role. But there is yet more to it than that. Until now, the machine-learning techniques which DeepMind’s team used to attack the protein-folding problem have been best known for powering things like face-recognition cameras and voice assistants, and for defeating human beings at tricky games like Go. But Demis Hassabis, DeepMind’s boss, founded what was then an independent firm in the hope that they could also be employed to accelerate the progress of science. This result demonstrates how that might work in practice.</p><p >The idea of using computers to predict proteins’ shapes is half a century old. Progress has been real, but slow, says Ewan Birney, deputy director of the European Molecular Biology Laboratory, a multinational endeavour headquartered in Germany. And it has been marked by a history of wrong turns and premature declarations of victory. These days a humbler field, it now measures its progress by how well algorithms perform in something called Critical Assessment of Protein Structure Prediction (CASP). This is a biennial experiment-cum-competition which started in 1994 and is jokingly dubbed the “Olympics of protein folding”. In it, algorithms are subjected to blind tests of their ability to predict the shapes of several proteins of known structure.</p><div id="" ><div><div id="econ-2"></div></div></div><div ><figure><div itemscope="" itemProp="image" itemType="https://schema.org/ImageObject" data-slim="1"><meta itemProp="url" content="https://www.economist.com/img/b/608/662/90/sites/default/files/20201205_STC068_0.png"/><img loading="lazy" src="https://www.economist.com/img/b/608/662/90/sites/default/files/20201205_STC068_0.png"  sizes="300px" alt=""/></div></figure><p >At this, its second attempt, DeepMind has aced CASP. Its first try, dubbed AlphaFold, made waves two years ago by performing much better than any existing program. The current version, AlphaFold 2, has stretched that lead still further (see chart). One measure of success within CASP is the global-distance test. This assigns algorithms a score between zero and 100 by comparing the predicted locations of atoms in a molecule’s structure with their location in reality. AlphaFold 2 had an average score of 92.4—an accuracy that CASP’s founder, John Moult, who is a biologist at the University of Maryland, says is roughly comparable with what can be obtained by techniques like X-ray crystallography.</p><p >Until now, DeepMind was probably best known for its success in teaching computers to play games—particularly Go, a pass-time of deceptively simple rules but fiendish strategy that had been a totem of AI researchers since the field began. In 2016 a DeepMind program called AlphaGo defeated Lee Sedol, one of the world’s best players. Dr Hassabis says there are more similarities between protein-folding and Go than might, at first, appear.</p><p >One is the impracticality of attacking the problem with computational brute force. There are thought to be around 10<sup>170</sup> legal positions in Go, a number far exceeding the number of atoms in the observable universe, and which is thus way beyond the reach of any computer. Proteins are, if anything, even more complicated. One estimate is that there may be as many as 10<sup>300</sup> different shapes in which a reasonably complex protein could find itself. Add to this the fact that a protein ends up in the desired shape thanks to the balance of various atomic-scale forces acting between and within its amino-acid building blocks, and with any other molecules, particularly of those of water, surrounding them, and it becomes clear that the only way to perform the trick of predicting protein folding is to look for shortcuts.</p><p >The progress that computers have made on the problem over the years demonstrates that some of these exist. But it also turns out that even inexpert humans can learn such tricks by playing around. Dr Hassabis recalls being struck by the ability of human amateurs to achieve good results with “FoldIt”, a science-oriented video game launched in 2008 that invites its players to try folding proteins themselves, and which has generated a clutch of papers and discoveries.</p></div><p >Getting players of “FoldIt” to explain exactly what they are up to, though, is tricky. Here, there is another parallel with Go. Rather than explaining step by step what they are thinking, players of both games tend to talk in vaguer terms of “intuition” and “what feels right”. This is where the machine learning comes in. By feeding computers enough examples, they are able to learn and apply shortcuts and rules-of-thumb of the sort that human beings also do, but struggle to articulate. Sometimes, the machines come up with insights that surprise human experts. As Dr Moult observes, “In general, the detail of the backbone [the molecular scaffolding that joins amino acids together] is extraordinary. [AlphaGo] has decided that if you don’t get the details right, you won’t get the big things right. This is a school of thought that’s been around for some time, but I thought it wasn’t correct.”</p><h2>Alpha-helix dogs</h2><p >As an AI achievement, AlphaFold 2 is not quite so far ahead of the field as was AlphaGo. Plenty of other research groups have applied machine learning to the protein-structure problem, and have seen encouraging progress. Exactly what DeepMind has done to seize the lead remains unclear, though the firm has promised a technical paper that will delve into the details. For now, John Jumper, the project’s leader, points out that machine learning is a box which contains a variety of tools, and says that they have now abandoned the system they used to build the original AlphaFold in 2018, after it became clear that it had reached the limits of its ability.</p><p >The current version, says Dr Jumper, has more room to grow. He and his team think there is space to boost the software’s accuracy still further. There are, for now, things that remain beyond its reach, such as how structures built from several proteins joined together.</p><p >Moreover, as Ken Dill, a biologist at Stony Brook University, in New York state, who is the author of a recent overview of the field, points out, what AlphaFold 2, its rivals, and, indeed, techniques like X-ray crystallography discover are static structures. Action in biology, by contrast, comes from how molecules interact with each other. “It is,” he puts it, “a bit like someone asking how a car works, so you open the hood[bonnet] and take a picture and say, ‘there, that’s how it works!’” Useful, in other words. But not quite the entire story.</p><p >Nonetheless—and depending on how DeepMind decides to license the technology—an ability to generate protein structures routinely in this way could have a big impact on the field. Around 180m amino-acid sequences are known to science. But only some 170,000 of them have had their structures determined. Dr Moult thinks that boosting this number could help screen candidate drugs to see which are likely to bind well to a particular protein. It could be used to reanalyse existing drugs to see what else they might do. It could boost synthetic biology, by speeding up the creation of human-designed proteins designed to catalyse chemical reactions.</p><p >There have, indeed, already been promising successes. AlphaFold 2 was, for example, able to predict the structures of several of the proteins used by SARS-CoV-2 virus, including spike. As for Dr Birney, he says, “we’re definitely going to want to spend some time kicking the tyres. But when I first saw these results, I nearly fell off my chair.”</p><br><hr><div>获取更多RSS：<br><a href="https://feedx.net" style="color:orange" target="_blank">https://feedx.net</a> <br><a href="https://feedx.xyz" style="color:orange" target="_blank">https://feedx.xyz</a><br></div>
</div>