# Welcome to covid19 python module !
A powerful , flexible and modern python module that keeps track of Covid19 infections worldwide or by country name , data is retrieved from [World Meters](https://www.worldometers.info/coronavirus/)
# Getting started
* Install the module with pip : `pip install covid19`
* Import the main core : `from covid19 import main`
* You're set ! Consult the [docs](#api-docs) and get going
# Api docs
The docs <a href="#api-docs">section</a>

## 1- get_infections()
### 1-1 Description
A function that gets the latest infection counts , deaths and more sorted by countries
### 1-2 Returns
Returns an **object**

## 2- get_infections_by_name(country_name=None)
### 2-1 Description
A function that gets the latest infection counts , deaths and more for the country specified
### 2-2 Params
`country_name` : __string__  : Can be one of the countries returned in **get_infected_countries()**
### 2-3 Returns
Returns an **object** 

## 3- get_infected_countries())
### 3-1 Description
A function that gets a list of infected countries
### 3-2 Returns
Returns a **list** 
# Support
Join my discord [server](https://discord.gg/9fhkSZH) for support
