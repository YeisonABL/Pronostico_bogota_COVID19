# Pronostico_bogota_COVID19

A través de RNN's simples, con celdas LSTM y celdas GRU se hace pronostico del COVID-19 sobre los casos, recuperados y fallecidos diarios y acumulados.


- Se realiza el entrenamiento y testeo con los datos desde el 2020-03-06 hasta el 2022-03-06, y se hace el pronostico para 60 dias despues. 
- Se utilizó tensorflow como libreria para la modelación del problema. 
- Se utilizó keras tuner para probar distintos tipos de redes neuronales y encontrar la más optima para la solución del problema: El número de neuronas y el learning rate. 

