# Code Chunk
    
```gnuplot {cmd=true output="html"}
set terminal svg
set title "Simple Plots" font ",20"
set key left box
set samples 50
set style data points

plot [-10:10] sin(x),atan(x),cos(atan(x))
```

```latex {cmd=true}
\documentclass{standalone}
\begin{document}
   
\end{document}
```