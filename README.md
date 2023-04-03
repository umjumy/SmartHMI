# SmartHMI
The ISO 14649 standard provides a common framework for exchanging information related to the manufacturing of mechanical parts. In order to facilitate the implementation of this standard, a metadata manager has been developed, which is capable of transforming data stored in different file formats, such as JSON, XML or MySQL databases, into a common format that conforms to the ISO 14649 standard.

The metadata manager is made available to developers through a Dynamic Link Library (DLL) that provides the necessary functions to manipulate the data in the target file format. By utilizing this library, developers can modify the file structure of their data to match the ISO 14649 standard.

Specifically, the DLL library for the ISO 14649 metadata manager allows for the conversion of the file structure of JSON, XML or MySQL databases into a structured JSON file format that adheres to the ISO 14649 standard. This provides a uniform way to manage manufacturing-related data, enabling easier exchange of information between different systems and applications.

In summary, the ISO 14649 metadata manager DLL library is an essential tool for implementing the ISO 14649 standard in manufacturing systems, enabling efficient and standardized exchange of data.

# Input and Output Data
The input and output file format of this Dll library for the ISO 14649 metadata manager are as follows:
1. Virtual Machine: JSON to JSON
2. Sketchturn: XML to JSON
3. NXCAM: MySQL to JSON

# Implementation Code Example
Code example to use VirtualMachineDll

```
VirtualMachineClass vm = new VirtualMachineClass();
string inputFile = "File directory"; //example D:\\Data\\CAVITY_MILL_ROUGH.json
string outputFile= "File directory"; //example D:\\Data\\virtual_machine_metadata.json
vm.VMmetadata(inputFile, outputFile);
```

# Acknowledge
This work was supported by the Technology Development Program for Smart Controller in Manufacturing Equipment (20012807, Development of Customized Smart HMI Systems) funded By the Ministry of Trade, Industry & Energy (MOTIE, Korea) and Institute of Information & communications Technology Planning & Evaluation(IITP) grant funded by the Korea government(MSIT) (RS-2022-00155911, Artificial Intelligence Convergence Innovation Human Resources Development (Kyung Hee University)).
