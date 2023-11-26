# Latex
Main codes for reports.
 "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
For tables:
\begin{table}[h!]
 \centering
\caption{A multi-column table within one column}
 \label{tab:multicolumntable}
\begin{tabular}{|l|l|l|} % Example with three columns, adjust as needed
        \hline
        Column 1 Header & Column 2 Header & Column 3 Header \\ % Table headers
        \hline
        Row 1, Col 1 & Row 1, Col 2 & Row 1, Col 3 \\ % Table content
        Row 2, Col 1 & Row 2, Col 2 & Row 2, Col 3 \\
        % Add more rows as needed
        \hline
    \end{tabular}
\end{table}


For images: 
\begin{figure}[h!]\centering
\includegraphics[width=0.5\linewidth]{image.jpg/png}
\caption{Caption.}
\label{fig: n}
\end{figure}\\

For equations:
\begin{equation}\label{eq:lll}
\frac{{d^2 \theta}}{{dt^2}} + \frac{g}{L} \sin(\theta) = 0
\end{equation}\\


For items:
\begin{itemize}
    \item A
    \item B
    \item C
    \item D
    \item E
    \item F
\end{itemize}


For bilbiography:
\bibliography{biblio}, where biblio is another document inside Latex environment such as
@article{label,
  title={Article's name},
  author={Surname1, Name1 and Surname2, Name2},
  year={0000},
  publisher={NNN}
}

@incollection{label,
  title={Chapter's title},
  author={{Surname1, Name1 and Surname2, Name2},
  booktitle={Book's title},
  pages={000--000},
  year={0000},
  publisher={NNN}
}
 ]
    }
   ],
