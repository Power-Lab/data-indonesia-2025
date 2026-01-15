# Indonesian Power System Energy Modeling Data

This repository contains energy systems optimization modeling data for Indonesia's power system and captive power facilities (Industrial Plants/IP). The data is organized by time horizon and regional zones, providing comprehensive datasets for energy system planning and optimization studies.

## Repository Overview

This dataset supports energy system modeling for Indonesia across multiple years and regions, including both the main interconnected power system and captive/industrial power generation facilities.

[Link to the model code](https://github.com/Power-Lab/captive-indonesia-2025)

[Link to the report that uses this data](https://zenodo.org/records/17345968)

## Data Structure

The repository is organized by:

### Time Horizons
- **2030**: Energy system data for year 2030 scenarios
- **2035**: Energy system data for year 2035 scenarios

### Regions
- **Jawa-Bali**: Jawa and Bali region (including Madura)
- **Sumatera**: Sumatera region
- **Kalimantan**: Kalimantan region
- **Sulawesi**: Sulawesi region
- **Nusa Tenggara**: East Nusa Tenggara region
- **Papua**: Papua region
- **Maluku**: Maluku region
- **North Maluku**: North Maluku region

## File Types

Each regional folder contains the following data files:

### Main Power System Files
- **demand.csv**: Hourly electricity demand profiles for the main power system
- **generators.csv**: Generator fleet characteristics (capacity, efficiency, fuel type, etc.)
- **generators_variability.csv**: Variable generation profiles (renewable/weather-dependent generators)
- **fuels_data.csv**: Fuel specifications and availability
- **network.csv**: Transmission network topology and constraints (where available)
- **zones.csv**: Zone definitions and geographic information (where available)

### Captive/Industrial Plant (IP) Files
- **ip_demand.csv**: Electricity demand from industrial plants/captive facilities
- **ip_demandheat.csv**: Thermal demand from industrial plants
- **ip_generators.csv**: Captive power generation fleet characteristics
- **ip_generators_variability.csv**: Variable generation profiles for captive facilities

## Data Coverage

- **Full regional datasets**: Available for Jawa-Bali, Sumatera, Kalimantan, and Sulawesi (both main system and captive data)
- **Partial datasets**: Available for Nusa Tenggara, Papua, North Maluku (does not include internal transmission lines)
- **Limited datasets**: Available for Maluku (this island system does not have any known captive facilities)

## Usage

These datasets are designed for:
- Energy system optimization modeling and planning
- Capacity expansion planning studies
- Renewable energy integration analysis
- Power system operation and dispatch optimization
- Policy and scenario analysis for Indonesia's energy transition

## Data Format

All data files are in CSV format with:
- Headers in the first row
- Time series data indexed by time periods (typically hourly)
- Regional/zone identifiers where applicable

## License

See the LICENSE file for details on data usage and attribution requirements.

## Notes

- Time series data typically covers a full year with hourly resolution
- Some regions have more complete network and geographic data than others
- Captive facility data (IP prefix) represents industrial plants and self-generating facilities
- All values follow standard power system modeling conventions (MW for power, MWh for energy, etc.)

---

For questions or data requests, please contact the [Power Transformation Lab](https://pwrlab.org).
