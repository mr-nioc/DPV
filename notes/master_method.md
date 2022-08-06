## Master Method

The master method works for following type of recurrences

$T(n) = aT(n/b) + \Theta(n^c)$ where $a \ge 1$ and $b > 1$

with three cases:

- if $c < \log_ba$, then $T(n) = \Theta(n^{\log_ba})$;

- if $c = \log_ba$, then $T(n) = \Theta(n^c\log n)$;

- if $c > \log_ba$, then $T(n) = \Theta(n^c)$.
