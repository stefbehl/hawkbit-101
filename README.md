# hawkBit-101 Tutorial

This repository provides a _hands-on tutorial_ to get familiar with  [Eclipse hawkBit™](https://www.eclipse.org/hawkbit/), in particular its APIs. Eclipse hawkBit™ is a domain-independent backend framework for rolling out software updates to constrained edge devices as well as more powerful controllers and gateways that are connected to a IP-based networking infrastructure.

The tutorial was originally created for and held at [EclipseCon Europe 2019](https://www.eclipsecon.org/europe2019/sessions/eclipse-hawkbit-101) and is meant for a technical target audience which can include beginners as well as developers who already acquired some basic knowledge about hawkBit. To conduct the tutorial, it is recommended to walk the participants through the different steps using the slides that are available [here](https://stefbehl.github.io/hawkbit-101/).

The tutorial has four parts covering the most important workflows /use cases:
- Provisioning a device
- Creating an update
- Updating a single device
- Updating many devices

## Setup Instructions

[![Get help at https://gitter.im/eclipse/hawkbit-101](https://badges.gitter.im/eclipse/hawkbit-101.svg)](https://gitter.im/eclipse/hawkbit-101?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

It is recommended to run the tutorial against the hawkBit setup which is available in this repository as a [Docker stack](https://github.com/stefbehl/hawkbit-101/blob/master/setup/docker-compose-stack.yml). The Docker stack includes a _hawkBit Update Server_ including the required infrastructure components (a MySQL database and a RabbitMQ message broker). In addition, it includes a _device simulator_ which can be used to simulate a fleet of devices that are connected to the update server. Find the concrete setup instructions in the supporting slide deck on [slide 9](https://stefbehl.github.io/hawkbit-101/#/9).

To execute the different API requests, the participants can either use the command line tool [curl](https://curl.haxx.se/) or a [Postman](https://www.getpostman.com/) client (ideally version 6 or higher). To support the participants in doing that (and rid them from typing too much), the slides offer small inline links to copy the commands into the clipboard. In addition, there is a [Postman collection](https://github.com/stefbehl/hawkbit-101/blob/master/postman/hawkbit101.postman_collection.json) which can be imported into Postman as well as a text file listing all of the different [curl commands](https://github.com/stefbehl/hawkbit-101/blob/master/postman/hawkbit101.curl_snippets.txt).
