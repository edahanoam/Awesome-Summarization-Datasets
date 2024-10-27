# Awesome-Summarization-Datasets
The collection and ontology is a result of our survey __The State and Fate of Summarization Datasets__.  

<p align="center">
  <img src="./images/ontology.png" alt="plot">
</p>

<!-- here a way to cite our paper -->



If you'd like to contribute a dataset, please submit a pull request and add it to dataset.csv.

For standardization, we recommend using the Summarization Data Card, which follows findings from our survey.<details>
<summary>📋 Click here to copy the LaTeX code</summary>

```latex
\begin{table}[tb!]
\resizebox{\columnwidth}{!}{%
\begin{tabular}{|p{7.5cm}|}

\hline
\textbf{Summarization Data Card}                                                                                      \\ \hline
\textbf{\underline{Sample information:}}      
\\
\textbf{Languages:} 
\newline
\textit{List all supported languages}                                                                               \\
\textbf{Summary Shape:}
\newline
\textit{Paragraph/One Sentence/Highlights/Span}                                                                \\
\textbf{Domain:} 
\newline
\textit{Example: News/Scientific/Dialogues/etc.}                                                                       \\
\textbf{Size:}
\newline
\textit{Number of document-summary pairs}                                                                                \\ \hline
\textbf{\underline{Annotation information:}}                                                                                      \\
\begin{tabular}[|p{7.5cm}|]{@{}l@{}}\textbf{Annotation efforts:} \\ \textit{Automatic, Human annotations, Semi-automatic}\end{tabular}   \\
\begin{tabular}[|p{7.5cm}|]{@{}l@{}}\textbf{Source of supervision:}\\ \textit{Natural} (summaries created organically)/ \\ \textit{Distant} (annotations are proxies of summaries)/\\ \textit{Dedicated} (annotations created by researchers)\end{tabular} \\
\begin{tabular}[|p{7.5cm}|]{@{}l@{}}\textbf{Brief description of the summaries' source:} \\ \textit{Example:
digests of legal documents}\end{tabular} \\ \hline
\textbf{\underline{Data quality assessment:}}                                                                                     \\
\begin{tabular}[|p{7.5cm}|]{@{}l@{}}\textbf{Abstraction level:} \\ \textit{1-to-4-gram ratios} \end{tabular} \\
\textbf{Compression rate:}  
$ \frac{\text{doc length (\#words)}}{\text{summary length (\#words)}}$                                                                                                    \\
\textbf{Human evaluation:} \textit{Yes/No}                                                                                              \\ \hline
\textbf{\underline{Availability details:}}                                                                                        \\
\begin{tabular}[|p{7.5cm}|]{@{}l@{}}\textbf{How is the data made accessible:} \\ \textit{Publicly Available} / \\
\textit{URL-based Reconstruction} / \\ \textit{Upon Request}\end{tabular}    \\
\begin{tabular}[c]{@{}l@{}}\textbf{Copyrights information:} \\ \textit{License}\end{tabular}                                            \\ \hline
\end{tabular}%
}
\caption{Template for a summarization data card.}
\label{tab:datacard}

\end{table}

```
</details>

<p align="center">
  <img src="./images/datacard.PNG" alt="plot">
</p>
