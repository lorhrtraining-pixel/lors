# Organizational Chart

## Company Structure

```mermaid
graph TD
    %% Executive
    Pres[PRESIDENT] --> Sales[SALES DEPARTMENT]
    Pres --> WH[WAREHOUSE & LOGISTICS<br>Vincent Bayaua - Warehouse Manager]

    %% Sales Department
    Sales --> S_Lights[LIGHTS<br>M. Medina - Area Sales Mngr]
    Sales --> S_Furn[FURNITURE<br>Dom Monterozo - Sales Mngr]
    Sales --> S_Area[AREA SALES<br>Jay Quindao - Area Sales Mngr]
    Sales --> S_LRI[LRI SALES<br>JM Mercene - LRI Sales Mngr]
    Sales --> S_Lev[LEVANTO SALES<br>Carlota Ramos - Sales Mngr]

    %% Sales Sub-nodes
    S_Lights --> SL_B[Neovega<br>Ambient<br>Milana]
    S_Furn --> SF_B[Montini<br>Marrina<br>Bonbonnaire<br>Mazzina/Forma Rossa]
    S_Area --> SA_B[Miscella LRI/MC BGC<br>Daaz Alabang/MC BGC<br>Marque]
    S_LRI --> SLR_B[Neovega<br>Ambient<br>Milana<br>Smarthome]
    S_Lev --> SV_B[Monarq<br>Sistema<br>Venetian]

    %% Warehouse Department
    WH --> WH_Furn[FURNITURE WAREHOUSE<br>Rommel Vejano - Warehouse Officer]
    WH --> WH_Del[DELIVERY & INSTALLATION]
    WH --> WH_Light[LIGHTS WAREHOUSE<br>Edmar Palines - Asst. Warehouse Mngr]

    %% Warehouse Sub-nodes
    WH_Furn --> WHF_S[Pickers<br>Fabricators: Rubin Taylaran<br>Warehousemen]
    
    WH_Del --> WHD_T[Teams: Jeff, Jonathan, Umali, Furnitrue]
    WH_Del --> WHD_I[Roving Installers: Empleo, Flaviano, Quellar]
    
    WH_Light --> WHL_S[Warehouse Asst: Vincent Rivero, Ryan dela Cruz<br>Inventory: Paul Ablay<br>Electricians: Randy Minoza, Ken Abila<br>Painters]
    WH_Light --> WHL_L[Location Assistants<br>LRI: Mack Ramirez<br>Robins: Andy E.]
    WH_Light --> WHL_Log[Logistics<br>Orly Orlanda - Warehouse Asst Logistics]
```

## Department Overview

### Sales Department
Manages 5 key sales divisions:
- **Lights** (M. Medina) - Brands: Neovega, Ambient, Milana
- **Furniture** (Dom Monterozo) - Brands: Montini, Marrina, Bonbonnaire, Mazzina/Forma Rossa
- **Area Sales** (Jay Quindao) - Locations: Miscella LRI/MC BGC, Daaz Alabang/MC BGC, Marque
- **LRI Sales** (JM Mercene) - Brands: Neovega, Ambient, Milana, Smarthome
- **Levanto Sales** (Carlota Ramos) - Brands: Monarq, Sistema, Venetian

### Warehouse & Logistics Department
Managed by Vincent Bayaua, includes 3 sections:
- **Furniture Warehouse** (Rommel Vejano) - Pickers, Fabricators, Warehousemen
- **Delivery & Installation** - Delivery teams and Roving Installers
- **Lights Warehouse** (Edmar Palines) - Warehouse assistants, Inventory, Electricians, Location Assistants, Logistics
