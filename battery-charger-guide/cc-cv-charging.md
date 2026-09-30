# CC/CV Charging Explained

CC/CV stands for Constant Current / Constant Voltage. It is a common charging method used for rechargeable lithium batteries, including lithium-ion and LiFePO4 battery packs.

Understanding CC/CV charging is important when selecting or designing a battery charger because the charging voltage, current and termination conditions must match the battery specifications.

## What Does CC/CV Mean?

CC means Constant Current.

During the constant-current stage, the charger supplies a controlled charging current to the battery. As the battery charges, its voltage gradually increases.

CV means Constant Voltage.

When the battery reaches the specified charging voltage, the charger maintains a constant voltage. The charging current gradually decreases as the battery approaches full charge.

The charger normally terminates or reduces charging when the current reaches a specified threshold or when another charging condition is met.

## How Does CC/CV Charging Work?

A typical CC/CV charging process can be described in three stages.

### 1. Constant Current

The charger supplies a controlled current to the battery.

For example, a charger may provide 2 A during the constant-current stage.

The battery voltage increases during this stage.

### 2. Constant Voltage

When the battery reaches its specified charging voltage, the charger changes to constant-voltage operation.

For example, a typical single lithium-ion cell may use a charging voltage of 4.2 V.

For a 4S lithium-ion battery pack, the corresponding full-charge voltage is typically 16.8 V.

### 3. Charging Termination

During constant-voltage charging, the battery current gradually decreases.

When the charging current reaches the specified termination threshold, the charger can stop charging or enter another defined operating state.

The exact termination method depends on the charger design, battery specifications and BMS requirements.

## CC/CV Charging for Lithium-Ion Batteries

Lithium-ion batteries commonly use a CC/CV charging method.

A typical lithium-ion cell has a nominal voltage of approximately 3.7 V and a full-charge voltage of approximately 4.2 V.

For a series-connected battery pack, the charger voltage is determined by the number of cells in series.

Examples include:

- 1S: 4.2 V
- 2S: 8.4 V
- 3S: 12.6 V
- 4S: 16.8 V
- 6S: 25.2 V
- 10S: 42.0 V
- 13S: 54.6 V
- 20S: 84.0 V

The actual charging parameters should be confirmed from the battery manufacturer's specifications.

## CC/CV Charging for LiFePO4 Batteries

LiFePO4 batteries also commonly use CC/CV charging, but their charging voltage is different from conventional lithium-ion batteries.

A LiFePO4 cell typically has a nominal voltage of approximately 3.2 V and a full-charge voltage of approximately 3.65 V.

Examples include:

- 1S: 3.65 V
- 2S: 7.3 V
- 4S: 14.6 V
- 8S: 29.2 V
- 12S: 43.8 V
- 16S: 58.4 V
- 20S: 73.0 V

This is why a charger designed for a conventional 4.2 V lithium-ion cell should not automatically be used for a LiFePO4 battery.

## Why Is CC/CV Important?

The charging voltage and current must be controlled according to the battery chemistry and pack configuration.

A properly designed charger can provide:

- Controlled charging current
- Controlled charging voltage
- Appropriate charging termination
- Over-voltage protection
- Over-current protection
- Short-circuit protection
- Thermal protection when required
- Communication with the BMS when required

The exact protection and charging functions depend on the charger design and application.

## CC/CV Charger vs. DC Power Supply

A DC power supply provides electrical power, but it is not necessarily a complete battery charger.

A battery charger may require specific charging control, current limiting, voltage regulation, termination logic and protection functions.

Some battery systems also require communication between the charger and BMS.

For this reason, selecting a battery charger should consider the complete battery charging system rather than only the DC output voltage.

## How to Select a CC/CV Battery Charger

When selecting a CC/CV charger, check:

1. Battery chemistry
2. Number of cells in series
3. Required full-charge voltage
4. Battery capacity
5. Recommended charging current
6. BMS requirements
7. Charging termination requirements
8. Connector type
9. Input voltage
10. Required safety certifications

For OEM applications, additional requirements may include communication protocols, mechanical dimensions, cable length, enclosure design and custom charging profiles.

## Custom CC/CV Battery Chargers

Some battery-powered products require charging parameters that are not available from standard chargers.

A custom charger can be designed according to the requirements of the battery and end product.

Customization may include:

- Output voltage
- Charging current
- CC/CV parameters
- Charging termination
- Connector
- Cable
- Communication protocol
- BMS integration
- Mechanical dimensions
- Enclosure
- OEM branding

Custom CC/CV chargers can be used in industrial equipment, robotics, drones, medical equipment, electric mobility products, marine equipment and other battery-powered systems.

## Summary

CC/CV is a widely used charging method in rechargeable lithium battery systems.

The charger first operates in constant-current mode and then transitions to constant-voltage mode as the battery reaches its specified charging voltage.

The correct CC/CV parameters depend on battery chemistry, cell configuration, battery capacity, BMS requirements and the application.

For more details about lithium-ion charging, see the [Li-ion Battery Charging Guide](https://github.com/phonixcharger/phonixcharger/blob/main/battery-charger-guide/li-ion-battery-charging.md).

For LiFePO4-specific charging voltage and charging requirements, see the [LiFePO4 Battery Charging Guide](https://github.com/phonixcharger/phonixcharger/blob/main/battery-charger-guide/lifepo4-battery-charging.md).

For custom voltage, current, connectors, BMS integration and OEM/ODM development, see the [Custom Battery Charger Guide](https://github.com/phonixcharger/phonixcharger/blob/main/charger-design/custom-battery-charger.md).

## About Phonix Charger

Phonix Technology provides OEM and ODM battery charger development and manufacturing for lithium-ion, LiFePO4 and lead-acid battery applications.

Custom charging solutions can be developed according to required voltage, current, charging profile, connector, communication protocol and mechanical requirements.

Learn more about PHONIX custom battery charger solutions:

[PHONIX Charger](https://www.phonixcharger.com)
