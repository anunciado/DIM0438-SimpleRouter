# Simple Router

A network with a simple router in mininet environment. In this project, each host connects to an openvswitch that have a different subnet IP address. With the aid of the router, the host with different subnet IP addresses can communicate with each other. In this case, there are five subnets, i.e. 10.0.1.0/24, 10.0.2.0/24, 10.0.3.0/24, 10.0.4.0/24 and 10.0.5.0/24. These are subnets that are connected by one router, i.e. r1, r2, r3, r4, r5, respectively. In each subnet, there is one openvswitch. 

### Prerequisites

You will need to install the modules below to run the program: 
* [python 2.7.14](https://www.python.org/downloads/release/python-2714/)
* [mininet](http://mininet.org/download/)
* [pox](https://github.com/noxrepo/pox)

### Running

First, Mininet requires a controller, which we implemented in POX. To run the controller, inside the pox folder, use the following command:
```
./run_pox.sh
```

There are two ways to run the simulation of the network:

* Compile the IDE (PyCharm - Python IDE):
1. Just open the IDE
2. Import the project folder as a Project
3. Choose Run network on the context menu or Press Ctrl+Shift+F10
4. From this it only interacts with the system.

* Compile by terminal:
1. Enter the src folder and run the following command:
```
$ sudo python network.py
```
3. From this it only interacts with the system.

## Built With

* [PyCharm](https://www.jetbrains.com/pycharm/) - A IDE used

## Authors
### Developers: 
* **Luís Eduardo Anunciado Silva ([cruxiu@ufrn.edu.br](mailto:cruxiu@ufrn.edu.br))** 
* **Shirley Ohara Telemaco de Freitas ([shirleyohara@ufrn.edu.br](mailto:shirleyohara@ufrn.edu.br))** 
### Project Advisor: 
* **Augusto José Venâncio Neto ([augusto@dimap.ufrn.br](mailto:augusto@dimap.ufrn.br))** 

See also the list of [contributors](https://github.com/cruxiu/DIM0438-SimpleRouter/contributors) who participated in this project.

## License

This project is licensed under the GPL 3.0 - see the [LICENSE](LICENSE) file for details

