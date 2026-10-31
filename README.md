# solar-home-energy-manager
An AI-assisted home energy management system integrating solar monitoring, battery storage and smart home automation.


## Project status

🟡 Concept and initial design phase.

## Overview

Solar Home Energy Manager is a personal project aiming to build an intelligent home energy monitoring and automation platform.

The system will integrate an existing photovoltaic installation, battery storage, Solar Assistant monitoring and smart home devices into a unified dashboard.

The goal is to go beyond energy monitoring by using real-time data to make smarter decisions about household energy consumption, solar self-consumption and heating management.

## Existing infrastructure

The project is based on an already operational installation:

- Residential photovoltaic solar panels.
- Battery energy storage.
- Solar Assistant, currently monitoring the installation.
- Solar Assistant API available for data integration.
- Two electric towel radiators.
- One portable electric heater.

The house is a passive house with relatively low heating requirements.

## Main objectives

### 1. Energy monitoring

- Retrieve energy data from Solar Assistant through its API.
- Monitor solar production and household consumption.
- Track battery state of charge.
- Monitor grid import and export.
- Store historical data and provide useful statistics.

### 2. Smart device integration

- Integrate Shelly devices.
- Monitor and control selected heating circuits.
- Support smart plugs for compatible appliances.
- Provide centralized device management.

### 3. Intelligent energy management

Develop an automation engine that considers:

- Available solar surplus.
- Battery state of charge.
- Minimum battery reserve.
- Household energy consumption.
- Indoor temperature and heating requirements.
- User-defined priorities and manual overrides.

The system should prioritize comfort while maximizing the use of locally generated solar energy.

### 4. Custom dashboard

Provide a responsive interface with:

- Real-time energy flows.
- Production and consumption charts.
- Battery monitoring.
- Device status and controls.
- Automation rules and historical reports.

## Proposed technical approach

The architecture and technology choices will be refined during development.

Initial candidates include:

- Python for backend services.
- Solar Assistant API for energy data.
- Shelly API for smart device integration.
- A local database for historical measurements.
- A web-based dashboard.
- Claude Code for AI-assisted development.

Home Assistant may also be evaluated as an integration layer where appropriate.

## Development roadmap

1. Explore the Solar Assistant API and define the data model.
2. Build the initial monitoring backend and dashboard.
3. Integrate Shelly devices with safe manual controls.
4. Implement energy-based automation rules.
5. Add heating optimization and historical analysis.
6. Evaluate predictive features and further improvements.

## Safety and privacy

The system will be designed for local operation wherever possible.

Electrical loads will require appropriately rated switching equipment and suitable electrical protection. Heating automation will include safety limits and manual overrides.

No credentials, API keys or private installation details will be committed to this repository.

## Project motivation

This project addresses a real household need: making better use of existing solar production and battery storage while maintaining comfort and reducing unnecessary grid consumption.

It is intended to be developed and tested against a real, operational installation.
