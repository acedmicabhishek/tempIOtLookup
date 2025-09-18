# Module IV: Evolving IoT Standards

## 1. Overview and Approaches
- **Description**: This section provides an overview of the various standards and protocols that are being developed for the Internet of Things. Standardization is crucial for ensuring interoperability between devices from different manufacturers.
- **Key Approaches**:
    - **Top-Down**: Standards developed by traditional standards development organizations (SDOs) like the IETF and ETSI.
    - **Bottom-Up**: Standards that emerge from open-source projects and industry alliances.

## 2. IETF IPv6 Routing Protocol for RPL Roll
- **Description**: RPL (Routing Protocol for Low-Power and Lossy Networks) is a routing protocol designed by the IETF for LLNs. It is optimized for networks where nodes have limited power, memory, and processing capabilities.
- **Key Features**:
    - **Distance-Vector Protocol**: RPL is a distance-vector protocol, but it also has some link-state characteristics.
    - **Objective Function**: RPL uses an objective function to determine the best path to the root of the network.
    - **Support for Different Traffic Patterns**: RPL can support point-to-point, point-to-multipoint, and multipoint-to-point traffic.

## 3. Constrained Application Protocol (CoAP)
- **Description**: CoAP is a specialized web transfer protocol for use with constrained nodes and constrained networks in the IoT. It is designed to be lightweight and efficient, and it is easily translated to HTTP for integration with the web.
- **Key Features**:
    - **Request/Response Model**: CoAP follows a client/server request/response model, similar to HTTP.
    - **UDP-Based**: CoAP runs over UDP, which is more efficient than TCP for constrained devices.
    - **Built-in Discovery**: CoAP includes a mechanism for discovering resources on a server.

## 4. Representational State Transfer (REST)
- **Description**: REST is an architectural style for designing networked applications. It is based on a stateless, client-server, cacheable communications protocol — and in virtually all cases, the HTTP protocol is used. REST is a popular choice for designing APIs for IoT devices.
- **Key Principles**:
    - **Stateless**: The server does not store any client context between requests.
    - **Client-Server**: The client and server are separate entities.
    - **Cacheable**: Responses can be cached to improve performance.

## 5. ETSI M2M
- **Description**: The European Telecommunications Standards Institute (ETSI) has developed a set of standards for Machine-to-Machine (M2M) communications. These standards define an architecture for M2M systems, including interfaces between different components.
- **Key Components**:
    - **M2M Device**: The device that is being managed.
    - **M2M Gateway**: A device that provides connectivity between M2M devices and the network.
    - **M2M Application**: The application that uses the data from the M2M devices.

## 6. Third-Generation Partnership Project Service Requirements for Machine-Type Communications
- **Description**: The 3rd Generation Partnership Project (3GPP) is a collaboration of telecommunications standards associations. It has developed a set of service requirements for Machine-Type Communications (MTC), which are communications between machines with little or no human intervention.
- **Key Requirements**:
    - **Low Power Consumption**: MTC devices should be able to operate for long periods of time on battery power.
    - **Low Cost**: MTC devices should be inexpensive to manufacture.
    - **Scalability**: The network should be able to support a large number of MTC devices.

## 7. CENELEC
- **Description**: The European Committee for Electrotechnical Standardization (CENELEC) is responsible for standardization in the electrotechnical engineering field. It has developed a number of standards that are relevant to the IoT, including standards for smart metering and home automation.

## 8. IETF IPv6 Over Lowpower WPAN (6LoWPAN)
- **Description**: 6LoWPAN is an adaptation layer that allows IPv6 packets to be sent over IEEE 802.15.4 networks. It includes a header compression mechanism that reduces the size of the IPv6 and UDP headers, as well as a fragmentation mechanism that allows large IPv6 packets to be sent over the small MTU of IEEE 802.15.4.

## 9. ZigBee IP (ZIP)
- **Description**: ZigBee IP is a standard for an IPv6-based full wireless mesh network. It is designed for smart object networks that are scalable, secure, and low-power.

## 10. IP in Smart Objects (IPSO)
- **Description**: The IPSO Alliance is a global non-profit organization that promotes the use of IP for the networking of smart objects. It has developed a set of guidelines for designing and implementing IP-based smart object systems.