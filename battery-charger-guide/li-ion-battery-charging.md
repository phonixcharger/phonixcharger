# Li-ion Battery Charging Guide

Lithium-ion batteries require a properly matched battery charger to charge safely and efficiently. The charger voltage, charging current, charging profile, connector and communication method should be selected according to the battery pack design and its Battery Management System (BMS).

## What Is a Lithium-Ion Battery Charger?

A lithium-ion battery charger is a power supply designed to charge lithium-ion battery packs using a controlled charging process.

Most lithium-ion battery charging systems use a Constant Current (CC) and Constant Voltage (CV) charging profile.

The charger first provides a controlled charging current. As the battery voltage approaches the specified full-charge voltage, the charger transitions to constant-voltage operation and the charging current gradually decreases.

## How Does Lithium-Ion Battery Charging Work?

A typical lithium-ion charging process includes several stages:

1. Pre-charge when required
2. Constant-current charging
3. Constant-voltage charging
4. Charge termination or current cutoff

The exact charging parameters depend on the battery chemistry, cell configuration, battery capacity, BMS requirements and application.

## How to Choose the Correct Charger Voltage

The charger output voltage must match the battery pack's required full-charge voltage.

For example, a common lithium-ion cell has a nominal voltage of approximately 3.7 V and a typical full-charge voltage of 4.2 V.

Therefore:

- 1S lithium-ion battery: 4.2 V full-charge voltage
- 2S lithium-ion battery: 8.4 V
- 3S lithium-ion battery: 12.6 V
- 4S lithium-ion battery: 16.8 V
- 6S lithium-ion battery: 25.2 V
- 10S lithium-ion battery: 42.0 V
- 13S lithium-ion battery: 54.6 V
- 20S lithium-ion battery: 84.0 V

The actual charger voltage should always be determined from the battery pack design and charging requirements rather than from the nominal battery voltage alone.

## How to Choose Charging Current

Charging current is normally selected according to battery capacity, required charging time, battery specifications and BMS limitations.

For example, a 10 Ah battery charged at 2 A has a nominal charging rate of approximately 0.2C.

However, the appropriate charging current is not determined by capacity alone. The battery manufacturer, cell specifications, thermal conditions and BMS limits should also be considered.

## Can a Standard Power Supply Be Used as a Lithium-Ion Battery Charger?

A standard DC power supply is not necessarily a suitable lithium-ion battery charger.

A battery charger may need to provide controlled charging voltage and current, charge termination, protection functions and, in some applications, communication with the BMS.

For this reason, a properly designed battery charger should be selected for the specific battery pack.

## Lithium-Ion Charger and BMS Communication

Some battery systems require communication between the charger and BMS.

Depending on the application, communication may use:

- CAN Bus
- RS485
- UART
- SMBus

A customized charger can be designed to work with the communication requirements of the battery management system.

## Custom Lithium-Ion Battery Chargers

Battery-powered equipment may require charger parameters that are not available from standard off-the-shelf products.

Custom charger development can include:

- Output voltage
- Charging current
- CC/CV charging profile
- Charging termination parameters
- Connector type
- Cable length
- Enclosure design
- Communication protocol
- BMS integration
- Mechanical dimensions
- OEM branding and labeling

Custom battery chargers are commonly used for industrial equipment, robots, drones, medical equipment, electric mobility products, marine equipment and other specialized battery-powered systems.

## Choosing a Lithium-Ion Battery Charger

When selecting a lithium-ion battery charger, consider:

1. Battery chemistry
2. Number of cells in series
3. Required full-charge voltage
4. Battery capacity
5. Recommended charging current
6. BMS requirements
7. Charging communication
8. Connector type
9. Input power requirements
10. Safety and certification requirements

A charger should be matched to the complete battery system rather than selected only by nominal battery voltage.

## Custom Battery Charger Manufacturing

Phonix Technology provides OEM and ODM battery charger development and manufacturing for lithium-ion, LiFePO4 and lead-acid battery applications.

Custom charging solutions can be developed for different output voltages, charging currents, charging profiles, connectors, communication protocols and mechanical requirements.

Learn more about custom battery charger solutions:

https://www.phonixcharger.com
