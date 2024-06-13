# BGS experiment protocol
## Purpose of this protocol
This protocol seeks to eliminate, reduce or record potential sources of error in a BGS experiment.
The sources of error include but are not limited to:
- Third party traffic
- System states
- Faction type
- Rounding passes
- Different or rare test conditions 
- Multiple linked variables

## Test validity
-   Any traffic (except yourself) might invalidate the test. A repeat might be required.
-   Any exotic system state going active (pirate attack, infrastructure failure, etc) might invalidate the test.
-   Experiment must be done in isolation for only one faction as much as possible.
-   Test must yield consistent results at least twice, ideally in different systems.
-   Avoid any factor outside the test parameters, for instance: do not involve a Fleet Carrier if not testing that specifically.

## 1. General System Information
1. Date and time of the test
2. What is being tested
3. System name
4. Population

## 2. Start conditions
1. Record date and time
2. Check traffic report in a station. Ensure no traffic in last 24 hours
3. Record full system state before test, including influence and faction states

| Faction Name           | Inf % | Pending | Active States       | Recovering |
|------------------------|-------|---------|---------------------|------------|
| Faction A              | 55.6  |         |                     |            |
| Faction B              | 12.3  |         |  War                |            |
| Faction C              | 12.3  |         |  War                |            |
| ...                    |       |         |                     |            |

## 3. Experiment input
1. Record date and time
2. Try to isolate a single variable for each experiment
3. Record as many details as possible about the experiment input depending on type.

### 3.1 General
- Faction(s) supported and/or undermined
- Station/Settlement if applicable
- Detail any use of a Fleet Carrier in the process

### 3.2 Bonds
- Amount

### 3.3 Bounties
- Amount
- Type of hunting grounds (Low, Med, High, Haz RES, CNB, missions)

### 3.4 Conflict zones
- Space or Ground
- Intensity (Low, Medium, High)
- Side objectives completed

### 3.5 Crimes
- Victim faction
- Breakdown of crimes committed

### 3.6 Exploration
- Amount sold, detail each transaction

### 3.7 Missions
- INF+ total
- Type of mission

### 3.8 Trade - breakdown for each transaction
- Commodity
- Quantity sold
- Sale price (total)
- Profits (total)
- Demand value
- Demand bars (Red, None, Green)
- Supply value
- Supply bars
- Details on any Fleet Carrier usage
- Black Market?
- Illegal good?
- Stolen good?

## 4. Daily Tick
1. Record date and time of daily tick (https://elitebgs.app/ preferred)

## 5. Result conditions
1. Ensure system has finished its tick propagation. (can take up to 12 hours after detection)
2. Record date and time
3. Check traffic report in a station. Ensure no traffic unaccounted for in last 24 hours
4. Record full system state, including influence and faction states. Same as 2.
