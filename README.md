# capsule-network
[![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](https://github.com/armiro/COVID-CXNet/blob/master/LICENSE)
![license](https://img.shields.io/badge/development-100%25-yellow?style=flat-square)

The tensorflow implementation of CapsNet is based on [Aurélien Geron's](https://github.com/ageron/handson-ml) code.

The number of non-zero elements are counted. The two types of pruning are applied.

\begin{table}[h]
\caption{Amount of zeros that can be generated with 1\% drop in the accuracy}
\begin{center}
\begin{tabular}{|c|c|c|}
\hline
\textbf{Layer} & \textbf{First Approach} & \textbf{\begin{tabular}[c]{@{}c@{}}Second Approach\end{tabular}} \\ \hline
1              & 78.76\%            & 44.32\%                                                                        \\ \hline
2              & 95.03\%            & 89.84\%                                                                        \\ \hline
\end{tabular}
\label{tab3}
\end{center}
\end{table}
