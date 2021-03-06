# Learning Theory and Statistical Optimization

This is a GitHub page for the reading group on Learning Theory and Statistical Optimization held at the Department of Statistics, University of Oxford.

**Academic organizer:** [Patrick Rebeschini](http://www.stats.ox.ac.uk/~rebeschi/).

## Organization

We will hold hybrid sessions (as we do with classes), so that people can attend/present remotely. **Priority for the physical presence is reserved to the people presenting in the reading group**. Anyone who is interested to attend in person should let us know beforehand (please email patrick.rebeschini [at] stats.ox.ac.uk to confirm as we need to make sure we do not exceed the max room capacity).

**Where**: Social Area (Ground Floor), Department of Statistics (max room capacity: 14 people).

**When**: Mondays **(note the time change!)**, from 15:30 to 17:00, starting from Week 2 until Week 8.

## Schedule for Michaelmas Term

Week  | Speaker | Title
----- | ------- | ------
2 | Dominic Richards | Learning with Gradient Descent and Weakly Convex Losses (with M. Rabbat) (Accepted to AISTATS, 2021), [(paper)](https://arxiv.org/abs/2101.04968)
3 | --- | ---
4 | Valentin De Bortoli | Quantitative Propagation of Chaos for SGD in Wide Neural Networks [(paper)](https://arxiv.org/abs/2007.06352)
5 | Fan Wu | Minimax Rates of Estimation for Sparse PCA in High Dimensions [(paper)](https://arxiv.org/pdf/1202.0786.pdf)
6 | Carlo Alfano | On the Theory of Policy Gradient Methods: Optimality, Approximation, and Distribution Shift [(paper)](https://arxiv.org/abs/1908.00261)
7 | Tyler Farghly | A Non-Asymptotic Analysis of Stochastic Gradient Langevin Dynamics [(notes)](https://github.com/TomasVaskevicius/learning-and-statistical-optimization/blob/main/tex/michaelmas/week7/A_Non_Asymptotic_Analysis_of_SGLD.pdf) [(paper)](https://arxiv.org/abs/1702.03849)
8 | Tomas Vaskevicius | Fast Rates and Sparse Linear Prediction [(outline)](https://github.com/TomasVaskevicius/learning-and-statistical-optimization/blob/main/tex/michaelmas/week8/main.pdf)

## Schedule for Hilary Term

Week  | Speaker | Title
----- | ------- | ------
2 | Amartya Sanyal | Linear Convergence of Gradient and Proximal-Gradient Methods Under the Polyak- Lojasiewicz Condition [(paper)](https://arxiv.org/abs/1608.04636)
3 | Gonzalo Mena | Statistical Bounds for Entropic Optimal Transport and Sinkhorn EM ([paper 1](https://arxiv.org/abs/1905.11882), [paper 2](https://arxiv.org/abs/2006.16548))
4 | Eugenio Clerico | Some Information-Theoretic Generalization Bounds ([paper 1](https://arxiv.org/abs/1705.07809), [paper 2](https://arxiv.org/abs/1806.03803), [paper 3](https://www.researchgate.net/publication/330476152_Generalization_error_bounds_using_Wasserstein_distances))
5 | Eduard Oravkin | The Double Descent Phenomenon and Implicit Bias of Mirror Descent ([paper 1](https://arxiv.org/abs/1903.08560), [paper 2](https://arxiv.org/pdf/2006.10732.pdf))
6 | David Martinez | Accelerating Variance-Reduced Stochastic Gradient Methods [(paper)](https://arxiv.org/abs/1910.09494)
7 | --- | ---
8 | Jun Yang | Optimal dimension dependence of the Metropolis-Adjusted Langevin Algorithm ([paper 1](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.399.5634&rep=rep1&type=pdf), [paper 2](https://arxiv.org/abs/2012.12810))


## Instructions for the Speakers

Instead of whiteboard, we will be using graphical tablets. The speakers can either use their own equipments, or use the equipment available on the computer in the Social Area (Windows credentials are needed to log in). It is also fine to use slides, but ideally we should be using the whiteboard on Teams (or other methods). **The speakers should make sure to try the equipment beforehand.**

Speakers are asked to upload latex notes (up to 10 pages). Please store your latex files in ./tex/{term}/week{#}. Please also upload a compiled pdf of your notes.

To clone the repository execute
```
git clone https://github.com/TomasVaskevicius/learning-and-statistical-optimization.git
```

From the root of the cloned github repository, go to the directory which corresponds to your presentation. For example,
```
cd tex/michaelmas/week2
```

Upload you tex files, compile a pdf, and push to this repository. For example,
```
git add *.tex *.pdf {or whatever other files your are uploading}
git commit -m "Notes for the presentation of..."
git push
```

For help with GitHub see https://git-scm.com/docs/gittutorial or email vaskevicius.tomas [at] gmail.com.
