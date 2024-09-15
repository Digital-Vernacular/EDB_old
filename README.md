<center><h1><b><i>EDB Readme</i></b></center>

### About this project

This project was intended to help ease the transition from a setups' `readme` to a dashboard by creating a `standard` on the variables, thereby making it easier for users to share their dashboards almost like having a universal key

![underConstruction](https://github.com/user-attachments/assets/e78e8c9e-5926-4368-bff3-e3b9d27109f6)

## Table of Contents

1. [Requirements](#1-requirements)
2. [Preparing our system](#2-preparing-our-system)
    * [HACS](#hacs)
      * [Integrations](#integrations)
        * [HA Open-Meteo Solar Forecast](#ha-open-meteo-solar-forecast)
        * [Load Shedding](#load-shedding)
        * [Victron GX Modbus TCP](victron-gx-modbus-tcp)
      * [Cards](#cards)
        * [button-card]()
        * [apexcharts-card]()
        * [card-mod]()
        * [layout-card]()
        * [Horizon Card]()
        * [Plotly Graph Card]()
        * [Timer Bar Card]()
        * [Flexible Horse-shoe Card]()
        * [Flexible Table]()
        * [sunsynk-power-flow-card]()
3.
___
___

### 1. Requirements

To be able to use this project we will have to ensure that the environment that we choose to utilize meets the following requirements

* The solar system needs to have internet access
* The device running Home Assistant needs to have internet access
* Both of the above systems need to be on the same `Network`
* A device to access the `Home Assistant` interface from
* `HACS` needs to be configured see below
<br></br>
___
___

### 2. Preparing our system

<b>Getting the ENVIRONMENT ready</b>

This integration relies heavily on the environment variables within <b>Home Assistant</b> (HA) which in turn relies heavily on the variables from the <b>Operating System</b> (OS) therefore in order to use this effectively we need to ensure that we have configured the systems' timezone, date and network. 

<b>Set the time/date on</b>

* <a href="https://www.hivelocity.net/kb/how-to-change-date-time-zone-on-linux-server/" target="_blank">Linux</a>
* <a href="https://learn.microsoft.com/en-us/windows-server/networking/windows-time-service/windows-time-service-tools-and-settings?tabs=config" target="_blank">Windows</a>
* <a href="https://www.acecloudhosting.com/knowledgebase/how-to-change-your-date-and-time-in-mac/" target="_blank">Mac</a>

Thereafter it relies quite heavily on the cards and integrations from the <b>HACS</b> repositories... that said `THANK YOU` to all of the giants that have gone about creating this environment, the folks from <b>Home Assistant</b>, those from the <b>HACS</b> integration and those who created the <b>wonderful repositories</b> and made them available for our use! In the section just below  we will go about configuring the `HACS` integration and then in no particular order the initial setup of the `Integrations` and `Cards`

### HACS

<b>Configuring HACS (Home Assistant Community Store)</b>

There are already plenty of videos showing how to install HACS out there and again in no particular order other than searching `Install HACS 2024` on `Google` here are the first 5 links to `Youtube` Videos showing you how to do so

* <a href="https://www.youtube.com/watch?v=0hDyVoDGFbc" target="_blank">Home Assistant Community Store (2024 HACS Install Guide)</a>
* <a href="https://www.youtube.com/watch?v=Q8Gj0LiklRE" target="_blank">Install HACS in Home Assistant - 2024 COMPLETE HOW TO Guide</a>
* <a href="https://www.youtube.com/watch?v=lhm4y3Gqol4" target="_blank">Install HACS 2024</a>
* <a href="https://www.youtube.com/watch?v=XOnmJ5LPnIw" target="_blank">How to install the Home Assistant Community Store (HACS) in 2024</a>
* <a href="https://www.youtube.com/watch?v=Nzy1ABP4Y_8" target="_blank">STOP Using Home Assistant Without HACS!! | 2024</a>

#### Integrations
___

*

#### HA Open-Meteo Solar Forecast

#### Load Shedding

#### Victron GX Modbus TCP

### Cards

___

#### button-card

#### apexcharts-card

#### card-mod

#### layout-card

#### Horizon Card

#### Plotly Graph Card

#### Timer Bar Card

#### Flexible Horse-shoe Card

#### Flexible Table

# Victron

| Sensor Name | Setting Value | Notes |
| :---------- | :------------ | :---- |
| EDB Inverter Count | # | The number of inverters in our DB
| EDB Date of Installation (YYYY-MM-DD) | (YYYY-MM-DD) | Date that the EDB system was installed


<!-- <a href="https://www.buymeacoffee.com/digi_v" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/white_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a> -->

<a href="https://www.buymeacoffee.com/digi_v" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee" style="height: 40 !important;width: auto !important;" >
</a>