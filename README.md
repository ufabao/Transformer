# Transformer

This repository contains a simple transformer model, built essentially from scratch, starting with help from Andrej Karpathy's guide: https://www.youtube.com/watch?v=kCc8FmEb1nY&t=6317s&ab_channel=AndrejKarpathy


I trained the model on the LaTeX source code of the stacks project: https://stacks.math.columbia.edu/, and after rougholy 1 hour of training on my personal 1660 GPU was able to generate realistic looking algebraic geometry expressions. The model outputs LaTeX code that is close enough to compiling that overleaf can produce a pdf without making any changes. 

