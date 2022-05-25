The Drogue IoT project aims to bring together data and users in an _Internet of Things_ world.

Drogue IoT consists of components that may be used standalone or together:

* **Drogue Cloud** is an efficient and scalable connectivity layer for forwarding telemetry data safely from devices to business applications, and commands back to devices. 
* **Drogue Device** is an SDK for writing safe and efficient applications on microcontroller type of systems. 

<table border="0">
 <tr>
    <td><b style="font-size:30px">Cloud</b></td>
    <td><b style="font-size:30px">Device</b></td>
 </tr>
 <tr>
    <td>
With Drogue Cloud you can:

* Report telemetry data using open standards like HTTP, MQTT, CoAP or third party networks like LoRaWAN, LTE-M or NB-IoT.
* Multitenant model for managing applications, devices and credentials
* Integrate with any system using MQTT, WebSockets or directly accessing Kafka
* Manage IoT workloads for the Edge
* Run on-premise or in the cloud

Go to [https://sandbox.drogue.cloud](https://sandbox.drogue.cloud) and see for yourself!
    </td>
    <td>
Drogue Device is an SDK for writing embedded applications:

* Robust: built using [Rust](https://www.rust-lang.org), an efficient, memory safe and thread safe programming language.
* Efficient: uses [embassy](https://github.com/embassy-rs/embassy), the embedded async project, to deliver a fast and small runtime.
* IoT Ready: provides out of the box drivers and examples for WiFi, LoRaWAN and BLE.
* Composable: provides both an task-based and an Actor-based programming model for writing efficient and composable applications.
    </td>
 </tr>
</table>

Go to our [documentation](https://book.drogue.io/drogue-cloud/dev/index.html) to get started with Drogue IoT, and join the community [chat](https://matrix.to/#/#drogue-iot:matrix.org).

## Getting started

We try to make is as easy as possible to get you started:

* **[Public sandbox](https://sandbox.drogue.cloud)** – A public sandbox to let you try out the cloud side services without the need to install them manually. Just sign up with your GitHub account, and try it out.
* **[Buy a device](https://microbit.org/buy/?version=microbitV2)** – The micro:bit v2 is easy to get, and easy to use. It offers a few sensors and is supported by Rust and Drogue IoT out of the box. Just be sure to get a <u>**v2**</u>!
* **[Workshops](https://book.drogue.io/drogue-workshops/index.html)** – A set of workshops, that walk you through more complex scenarios step-by-step. Different workshops focus on different aspects and technologies.
* **[Meet the code](https://github.io/drogue-iot)** – Check out the code on our GitHub organization.
* **[Meet the people](https://matrix.to/#/#drogue-iot:matrix.org)** – Get in contact with us in our Matrix channel.

## Open source

Drogue IoT is *open source*, and all components are licensed under the Apache 2.0 license.  Development is done on [GitHub](https://github.com/drogue-iot).

This means, that you can participate in the development process. Everyone is welcome! Contributions come in various
ways, not only code.
