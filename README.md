# Modelo epidemiológico espacio-temporal

### Autores: Benjamin Bórquez, Rodrigo Altamirano, Diego Olguín.

En epidemiología es usual considerar modelos de EDO, únicamente temporales, que toman en consideración la proporción total de susceptibles, infectados, recuperados, etc. en la población. Por ejemplo, si se considera una dinámica de infección como sigue

* La población susceptible nace a tasa $A > 0$.
* La población susceptible se enferma a tasa $\beta$ debido a la interacción con los infectados.
* La población general fallece a tasa $d$.
* La población infectada fallece a tasa $\mu$ por la enfermedad.
* La población infectada se recupera a tasa $\gamma$.

El modelo de EDO asociado es, si se denota a $S, I$ los susceptibles e infectados, respectivamente

$$
\begin{align}
    \frac{dS}{dt} & =  A - \beta S I - dS, & t > 0 \\
    \frac{dI}{dt} & = \beta S I - (d + \mu + \gamma)I, & t > 0 \\
    S(0) & = S_0 \\
    I(0) & = I_0 
\end{align}
$$

### Condición inicial para una semilla fija


![alt text](https://github.com/diegoolguinw/EpidemicCrossDiffusion/blob/main/Imagenes/Resolucion_sistema/Ini_con.pdf?raw=true)

    
