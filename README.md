<<<<<<< HEAD
# Métodos Estadísticos en Cosmología 
## DCI-UGTO 2018

### Prof. Alma González & Gustavo Niz
### email: alma.gonzalez@fisica.ugto.mx, g.niz@ugto.mx 
### Repositorio actual del curso https://github.com/CosmoStats/cosmostats2018

(Para sincronizar tu repositorio con el del curso ejecuta:
git pull https://github.com/CosmoStats/cosmostats2018 master)

## TEMAS

1.- Programación básica [pyhton/conda](https://github.com/cosmostatschool/MACSS2017/blob/master/prerequisites/install_miniconda.md)

2.- Adquisición de datos y tipos de variables (encuestas, diseño de experimentos, observables, etc.)

3.- Probabilidad y estadistica. 

4.- Métodos de muestreo.

5.- Inferencia estadística.

    a) Inferencia clásica

    b) Inferencia Bayesiana

6.- Funciones de correlación de 2 puntos. 

    a) Algoritmos
    
    b) Espacio de Fourier
    
    c) Pesos y funciones ventana
    
    d) Isotrópica 
    
    e) Anisotrópica en espacio de corrimientos al rojo (censos de galaxias)
    

7.- Funciones de correlación de orden superior (si el tiempo lo permite)

    a) Algoritmos

    b) Error de funciones de orden inferior
    
    c) Espacio de Fourier


## Evaluación

-- 60 %  Tareas y Proyectos parciales. Github organizado. Se revisa continuamente.

    -- Tareas y proyectos preferentemente en jupyter notebooks. 
    Si se presentan en pdf deberán añadirse los scripts o códigos. 

-- 40% Proyecto final 


## Bibliografía

    Se proporciona durante el curso, conforme se usa. 
=======
Repository for the final project of the course-part1 

Supernova constraints to Omega matter

The goal is reproduce Figure 9, and table 10  of https://arxiv.org/pdf/1401.4064.pdf

Webpage reference: http://supernovae.in2p3.fr/sdss_snls_jla/ReadMe.html


TODO: 
 - Start a notebook to read and plot the data from http://supernovae.in2p3.fr/sdss_snls_jla/jla_likelihood_v4.tgz.
 
 The data to be read from file jla_lcparams.txt is mub,X1 and C.  alpha, beta, M* and deltaM in equation 4 (together with 5) are free parameters (called nuisance parameters)
 
 - In the same notebook define the relevant functions to describe such data. As well as the likelihood function according to equation 15 of  https://arxiv.org/pdf/1401.4064.pdf
 
 - Make the MCMC analysis using either emcee or your own code. A first approach is to consider only diagonal covariance matrix we used in the simpler example. I will helpt to update this to use the correct covariance matrix once this is done. 
>>>>>>> 163893d468fef2f8dd71d2c3c8b796558839972f
