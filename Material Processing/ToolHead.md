#Tool Head

#####Tool heads can have a variety of uses and can be installed in many different locations. They can serve as 3D print heads as well as function as other peripherals such as subtractive manufacturing heads, post processing attachments, and more.

####Tool Head Interfaces

Tool heads provide a variety of additive, subtractive, post-processing and other operations for a manufacturing system. When required, payloads may supply power and data for commanding electrical subsystems for operating the tool head. The physical and electrical interfaces for integrating a tool head are detailed below.

#####Physical Interfaces

The tool head interface allows for a filament-fed extruder setup as well as other peripherals. The entry port for the filament is shown in Figure 2a. The port is capable of accepting filament of 1.75 ±0.1mm diameter. The outer dimensions shall not exceed the dimensions listed in the drawing.

#####Electrical Interfaces

A 40-pin connector is used to transfer power and data to the tool head. Both 24V and 5V power sources are available for heating elements, motors, and other components. Total power draw is limited to 100W for the tool head. Pinouts are shown in the table below.

**[TABLE]**

##Specifications and Technical Notes

####For Hardware Designers

The tool head interfaces allow hardware designers to create new capabilities for existing space-based manufacturing platforms as well as capabilities that conform well to new platforms as they come online. The drawing for the tool head provides a starting point for designers. The interface document describes a maximum volume by which the hardware designer can develop new tool heads to exist within. With a standard set of mounting holes and a standard electrical connector, the new
tool head designed will be easily integrated within space-based manufacturing platforms in a plug-and-play manner.

####For Software Engineers

Software engineers and electrical engineers may work simultaneously to design control capability for tool heads. The interface document describes a standard MOLEX 71660-7040 connector that provides power and data to the tool head. This connector specification defines the extent of the electrical/mechanical interface of the tool head, allowing for a wide flexibility in control options.

####For Manufacturing Engineers

he MOLEX connector can be mounted within the tool head volume in a variety of manners, leaving freedom to the manufacturing engineer to choose which method best suits the given purpose.

A general best practice when manufacturing the tool head is to abide by NASA Payload Safety Policy and Requirements for the International Space Station, document SSP 51700, in order to meet safety and human factors requirements. Since the tool head is a component that at some point may be handled by crew, certain design additions may need to be made to enable accessibility and ease of manipulation as well as safety to the crew from sharp edges or hot ends.

#####Material Properties

All materials will need to be approved for use on the intended host platform, such as the International Space Station. The MSFC-HDBK-527 Material Selection List for Space Hardware Systems can be followed for material selection.

Materials not currently in NASA’s Materials and Processes Technical Information System (MAPTIS) may need to be tested for Flammability and Outgassing per NASA-STD-6001.

###Safety and Human Factors

Crew safety is paramount during operations. Safety processes per SSP 51700 shall be followed when designing new hardware.

####Relevant Documents

MSFC-HDBK-527 Material Selection List for Space Hardware Systems

SSP 30237 Space Station Electromagnetic Emission and Susceptibility Requirements

SSP 51700 Payload Safety Policy and Requirements for the International Space Station

NASA-STD-6001, Test 7 Flammability, Odor, Offgassing, and compatibility Requirements and Test Procedures for Materials in Environments That Support Combustion




