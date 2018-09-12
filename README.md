# ANUGA Clinic CSDMS 2018


The aim of the clinic is to present the basic ideas of producing an ANUGA domain, which entails creating an appropriate triangulated mesh, setting up intial conditions, and boundary conditions, operators such as flow inlets and then running (evolve) the simulation. Within the constraints of a jupyter notebook we will also see how to extract data from an `sww` file (the standard ANUGA output file) and visualise the output.  

The clinic is composed of 3 jupyter notebooks:

* [Notebook 1: Introduction to ANUGA](notebooks/notebook1.ipynb)
  - Here we introduce the idea of creating a `domain` which contains the mesh and quantities needed to run the simulation, and encapsulates the methods for setting up the initial conditions, the boundary conditions and the method for evolving the solution. 

* [Notebook 2: Merewether Flood Case Study](notebooks/notebook2.ipynb)
  - Here we look at a case study of a flood in the community of Merewether.  We will add a flow using an `Inlet_operator` and extract flow details at various points by interagating the `sww` file which is produced from each ANUGA run. 

* [Notebook 3: Setup a simple erosion Operator](notebooks/notebook3.ipynb)
  - Setup a sanddune erosion operator.
  
 * [Notebook 4: Setting up a Pumping Operator separated by a River Wall](notebooks/notebook4.ipynb)
   - Here we go through the process of creating an operator (fractional step operator) which implements a simple pump, and separate the inlet from the outlet with a River wall.

## Colaboratory

These notebooks have been designed to run in the google `colaboratory` environment, which provides a jupyter notebook environment running on a virtual machine in the cloud. To use this environment you need a google account so that your copies of the notebooks can be saved on google drive. 

Once you have your google account, you can start interacting with the notebooks. 

Here are direct links to the notebooks which open directly in colaboratory. This will start up a virtual environment associated with your google account where you can run the code in the notebook (and save any changes you might make).

* [Notebook 1: Introduction to ANUGA](https://colab.research.google.com/github/stoiver/anuga-clinic-2018/blob/master/notebooks/notebook1.ipynb)
* [Notebook 2: Merewether Flood Case Study](https://colab.research.google.com/github/stoiver/anuga-clinic-2018/blob/master/notebooks/notebook2.ipynb)
* [Notebook 3: Setup a simple erosion Operator](https://colab.research.google.com/github/stoiver/anuga-clinic-2018/blob/master/notebooks/notebook3.ipynb)
* [Notebook 4: Setup a pump operator](https://colab.research.google.com/github/stoiver/anuga-clinic-2018/blob/master/notebooks/notebook4.ipynb)

Alternatively open up the notebooks on github and then following the `View in Colaboratory` at the top of each notebook. 


## More Examples

If you are interested in learning more about ANUGA, the github repository has [documentation](https://github.com/GeoscienceAustralia/anuga_core/tree/master/doc), [example code](https://github.com/GeoscienceAustralia/anuga_core/tree/master/examples) and over 30 [validation tests](https://github.com/GeoscienceAustralia/anuga_core/tree/master/validation_tests).
