# CORBA Lab (Java)

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![CORBA](https://img.shields.io/badge/CORBA-Distributed-4B4B77?style=flat-square)
![Maven](https://img.shields.io/badge/Build-Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

A distributed-programming lab using **CORBA** in Java. It defines a remote service through an **IDL** interface and implements a server and a client that communicate through the ORB. The example service is a simple currency converter (Euro).

## Contents

- `src/main/java/Euro.idl` : the CORBA interface definition (IDL)
- `Euro/` : the classes generated from the IDL (stubs, helpers, holders)
- `Euro/Client.java`, `Euro/Server.java` : the client and the server

## Tech stack

Java, CORBA (IDL / ORB), Maven.

## Notes

Academic lab (distributed systems). Part of a wider set of labs also gathered in [Distributed-Systems-Labs](https://github.com/WafaaRahmoune/Distributed-Systems-Labs).

## License

Released under the MIT License. See [LICENSE](LICENSE).
