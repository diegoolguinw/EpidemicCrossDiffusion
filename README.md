# EpidemicCrossDiffusion

En epidemiología es usual considerar modelos de EDO, únicamente temporales, que toman en consideración la proporción total de susceptibles, infectados, recuperados, etc. en la población. Por ejemplo, si se considera una dinámica de infección como sigue
    \begin{itemize}
        \item La población susceptible nace a tasa $A > 0$.
        \item La población susceptible se enferma a tasa $\beta$ debido a la interacción con los infectados.
        \item La población general fallece a tasa $d$.
        \item La población infectada fallece a tasa $\mu$ por la enfermedad.
        \item La población infectada se recupera a tasa $\gamma$.
    \end{itemize}
