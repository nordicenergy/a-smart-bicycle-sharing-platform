# ReBike - A Smart Bicycle Sharing Platform



### Introduction

The Rebike´s bicyce sharing app is easy to use for every user. if you want a bike you just open the app and check in on the nearest one. if you want to rent or share your bike you simply add your bike and people will start to use it.

ReBike´s Smart Mobility is able to connect to electronic (bluetooth) bike locks so people can unlock bikes with their phone. ReBike can also be used in a staffed situation where an employee hands over the bike (or bike key).


### Proof of Concept (PoC)

Rebike is a blockchain application platform. Blockchain has a lot of benefits compared to traditional means of storing data on a public network, but the major downside is that the technology is very complex. The goal of the ReBike project is to take away the barrier to entry and make it easy for Javascript developers to build their application on the Blockchain. We like to showcase a Proof of Concept that can be made with the current state of the ReBike Software Development Kit. The application is called ReBike - SmartMobility.
 
Times are changing and nowadays new concepts like 'e-bike sharing' are becoming much more popular. We want to make use of this concept, fit a bike with a GPS tracking lock, build a Javascript application and use the ReBike blockchain for the data registration. Information like who is using the bike, when and its location will be registered on the Nordic Energy´s ReBike blockchain in its own separate side chain. We will build an easy mobile interface to register your usage via a QR code and you are on your way!


### Architecture

#### Software

Backend: NodeJS, ... Frontend: JavaSript, React, ...

#### Data structure - main objects

- Person: Natural persons and legal persons (organizations) who want to use bike sharing. A person has a status: [new] [active] [ended] [blocked]. Status [active] is required to use the full service.
 
- Contract: A person needs a contract to use bikes. The contract defines the relationship between the person and the (membership)provider. Each contract has a Contract Owner (a Person) wich is responsible for all users on his contract. He is responsible for the payment. A contract Owner can invite other persons on his contract to use the service. For example a company who allows staff to use the bikes or family members biking together on one contract. A contract has an Contract Type.
 
- Contract Type defines the fleets of resources [fleets] Persons may use. Contract Type also defines the rates (price of bike use).
 
- Fleet is a collection of resources (bikes). A resource is in (exactly) one fleet.
 
- Resource is an item that is for rent (bike).
 
- Location is a spot where bikes can

#### Roles:

member
admin
provider

