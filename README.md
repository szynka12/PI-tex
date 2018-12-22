# PI-tex
Report from integration project 

Nowe użyteczne komendy
1. Wektory pisane boldem:
    \bVec{a}

2. Moduł wektora:
    \vMag{a}

3. Puste makro
    \noop{Cokolwiek}
    Przydatne do sortowania bibliografii alfabetycznie po nazwiskach np.
        @incollection{perez,
	            author={\noop{Lozano}{T. Lozano-Pérez. \textit{Spatial planning: A configuration space approach}. W Cox I.J., Wilfong G.T.
	            \textit{Autonomous Robot Vehicles}.  Springer, New York, NY, USA, 1990.}},
            }
    Argument będzie obecny ale nie będzie wyświetlony
