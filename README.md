
# 🦟 Wild Mosquito Population Controls
This repository contains the code (and the figure) needed to build a MATLAB app useful for developing strategies for controlling a wild mosquito population. The implementation of the dynamical system describing the evolution of mosquitoes is based on the work of Claire Dufourd and Yves Dumont.
![Logo](https://raw.githubusercontent.com/LucaZepponi/mosquito_controls/main/mosquito_icon.png)



## Overview
The purpose of this app is to use the mathematical model developed by Dufourd and Dumont to simulate the dispersal of mosquitoes taking into account the presence of south wind the biological mosquitoes refer to the mosquito Aedes albopictus, commonly of the *tiger mosquito*.
This mosquito species has been recognized as a vector of several viruses disease, such as *yellow fever*, *dengue*, *chikungunya* and *zika fever*, and some nematodes, such as *dirofilariasis*.

The tiger mosquito is a diurnal mosquito, and the peak of its activity is found in the late afternoon and early morning hours.
When necessary, this mosquito prefers to feed on human blood and frequent urban environments due to the large number of suitable places for its breeding and feeding.


Developing proper mechanical, chemical and biological control of the population of these mosquitoes is therefore essential to reduce the spread of diseases carried by them.
Specifically, this MATLAB app seeks to be an aid to the proper establishment of mechanical and biological interventions by simulating the evolution and distribution of a wild mosquito population.
Mechanical and biological controls were chosen to be implemented instead of chemical ones in order to avoid the undesirable environmental effects of the latter.
In fact, pesticides are often harmful to the environment and not species-specific, so they could also kill other insects that we are interested in preserving.
On the other hand, the use of the *Sterile Insect Technique* (*SIT*) only goes to the population of the target species.
Another advantage of SIT over pesticides is the fact that sterile males can spread, arriving, in effect, in places where chemical intervention would not have been possible, such as within forests or along water streams.

In order to model mosquito population spread and growth, Dufourd and Dumont constructed a system of advection-diffusion-reaction equations.
Releases of sterile males were modeled with impulse differential equations.



## 🧩 Key Features
- Mathematical model for a wild mosquito population dynamics
- Interactive MATLAB app for simulations
- some temperature-dependent parameters for greater model realism



## 💻 Requirements
- MATLAB (reccomended: version 2022b or later)
- App Designer toolbox to edit per editare



## 🛠️ Installation
1. Clone the repository:
    ```bash
        git clone https://github.com/LucaZepponi/mosquito_controls.git
    ```
2. Open the .mlapp file in MATLAB
3. Run the app and customize the parameters as needed
    


## 📚 Acknowledgements
This work is based on the mathematical model proposed in:
 - [Dufourd, Claire, and Dumont, Yves. (2013). *Impact of environmental factors on mosquito dispersal in the prospect of sterile insect technique control*. Computers and Mathematics with Applications, 66(10), 1695-1715.](https://www.sciencedirect.com/science/article/pii/S0898122113002307)

 Additional references that supported the development of this tool include:
 - [Colella, P. (1984). *Multidimensional Upwind Methods for Hyperbolic Conservation Laws*. Lawrence Berkely National Laboratory.](https://escholarship.org/content/qt0f4430zf/qt0f4430zf.pdf)



## 📜 License
[GNU AFFERO GENERAL PUBLIC LICENSE](https://www.gnu.org/licenses/agpl-3.0.en.html#license-text)



## 👨🏻‍💻 Authors
- [Luca Zepponi](https://github.com/LucaZepponi)
