
# CNR_GR02_SKY130NM

# Who
| Name                        | E-mail                |
| :-                          | :-:                   |
| Alireza Peymanfar           | alirezp@stud.ntnu.no  |
| Sheikha Al-Nasser           | sheikhaa@stud.ntnu.no |
| Bjørn K.T. Solheim          | bksolhei@stud.ntnu.no | 
| Youssef Mohamad Youssef     | youssemy@stud.ntnu.no |

# Why
  

# How
 


# What

| What            | Lib/Folder       | Cell/Name |
| :-              | :-:              | :-:       |
| Schematic       | CNR_GR02_SKY130NM | CNR_GR02 |
| Layout          | CNR_GR02_SKY130NM | CNR_GR02 |
| LPE             | CNR_GR02_SKY130NM | CNR_GR02 |


# Changelog/Plan
| Version | Status | Comment|
| :-| :-| :-|
|0.5.0 | :v: | Convertion from temperature to current, current to time and time to digtial works |


# Signal interface
| Signal       | Direction | Domain  | Description                               |
| :---         | :---:     | :---:   | :---                                      |
| VDD_1V8         | Input     | VDD_1V8 | Main supply                               |
| VSS         | Input     | Ground  |                                           |
| PWRUP_1V8     | Input    | VDD_1V8 | Power up the circuit                       |


# Key parameters
| Parameter           | Min     | Typ           | Max     | Unit  |
| :---                | :-:     | :-:           | :-:     | :---: |
| Technology          |         | Skywater 130 nm |         |       |
| AVDD                | 1.7    | 1.8           | 1.9    | V     |
| Temperature         | -40     | 27            | 125     | C     |



# Status

| Stage                       | TYPE | Status | Comment                        |
| :---                        | :-:  | :---:  | :--:                           |
| Specification               | DOC  | :v:    |                                |
| Schematic                   | VIEW | :v:    |                                |
| Schematic simulation        | VER  | :v:    |                                |
| Layout                      | VIEW | :x:    |                                |
| Layout parasitic extraction | VIEW | :x:    |                                |
| LPE simulation              | VER  | :x:    |                                |
| LVS                         | VER  | :x:    |                                |
| DRC                         | VER  | :x:    |                                |
| ERC                         | VER  | :x:    |                                |
| ANT                         | VER  | :x:    |                                |
