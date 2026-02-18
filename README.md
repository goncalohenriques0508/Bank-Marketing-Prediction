# Bank-Marketing-Prediction
\section{\faChartLine\ Bank Marketing – Previsão de Subscrição de Depósitos a Prazo}

\subsection{\faInfoCircle\ Descrição}

Projeto de classificação supervisionada com o objetivo de prever a probabilidade de um cliente subscrever um depósito a prazo, com base em dados demográficos e comportamentais provenientes de campanhas de marketing bancário.

O trabalho foi desenvolvido segundo a metodologia \textbf{CRISP-DM}, cobrindo as fases de compreensão do negócio, exploração e preparação dos dados, modelação e avaliação de desempenho.

\subsection{\faBullseye\ Objetivos}

\begin{itemize}[leftmargin=1.5cm]
    \item Identificar o perfil de cliente com maior probabilidade de adesão.
    \item Determinar as variáveis com maior influência no target.
    \item Avaliar o melhor período do ano para campanhas.
    \item Comparar diferentes algoritmos de classificação supervisionada.
\end{itemize}

\subsection{\faDatabase\ Dataset}

\begin{itemize}[leftmargin=1.5cm]
    \item 45\,211 registos
    \item 16 variáveis independentes
    \item 1 variável target (\textit{y}: yes/no)
    \item Dados provenientes de campanhas telefónicas reais
\end{itemize}

\subsection{\faCogs\ Metodologia}

\subsubsection{\faSearch\ Business Understanding}

\begin{itemize}
    \item Definição do problema como classificação binária.
    \item Enquadramento estratégico no contexto do marketing bancário.
\end{itemize}

\subsubsection{\faChartBar\ Data Understanding}

\begin{itemize}
    \item Análise exploratória de variáveis numéricas e categóricas.
    \item Avaliação de distribuições e correlações.
\end{itemize}

\subsubsection{\faTools\ Data Preparation}

\begin{itemize}
    \item Tratamento de outliers (Balance, Previous, Campaign).
    \item Recodificação de categorias semelhantes.
    \item Eliminação de variáveis irrelevantes ou altamente correlacionadas.
    \item Engenharia de variáveis (ex: conversão da duração para minutos).
    \item Tratamento de desbalanceamento do target.
\end{itemize}

\subsubsection{\faBrain\ Modeling}

Modelos implementados:

\begin{itemize}
    \item Support Vector Machine (SVM)
    \item Decision Tree
    \item Naive Bayes
    \item Regressão Logística
\end{itemize}

\subsubsection{\faCheckCircle\ Evaluation}

Métricas utilizadas:

\begin{itemize}
    \item Recall
    \item Precision
    \item F1-Score
\end{itemize}

\subsection{\faChartPie\ Principais Resultados}

\begin{itemize}
    \item Variável com maior influência: \textbf{Job}
    \item Melhor mês para campanha: \textbf{Março}
    \item Melhoria de desempenho após Data Preparation
\end{itemize}

\subsection{\faWrench\ Ferramentas Utilizadas}

\begin{itemize}
    \item Orange Data Mining
    \item Metodologia CRISP-DM
    \item Algoritmos de Machine Learning supervisionado
\end{itemize}

\subsection{\faLightbulb\ Competências Demonstradas}

\begin{itemize}
    \item Aplicação prática da metodologia CRISP-DM
    \item Limpeza e transformação de dados
    \item Feature selection
    \item Modelação supervisionada
    \item Avaliação de métricas de classificação
    \item Interpretação orientada ao negócio
\end{itemize}
