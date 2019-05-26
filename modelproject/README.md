# Income taxation and the optimal behaviour of a worker.

In this project, we examine the change of behaviour of a worker due to a change in the marginal tax rate. First, we analysis the behaviour of a worker in a proportional tax system analytically using the `sympy` package. We then analyse the same behaviour grahpically. After we have determied the optimal behaviour of the worker, we estimate the tax rate that maximizes the tax revenue. We do this by simulating a samlpe of agents with different preferences and different income potentials using `numpy.random` and then estimating the ta rate which maximizes the tax revenue using `numpy.optimize`.

After we have analysed these problems for a proportional tax system we extend our analysis by replicate the problems in a tax system which allows for different tax rate for different income levels, i.e. a progressive or regressive tax system. 
