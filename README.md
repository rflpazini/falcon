# [DOJO] - Show me the drones

**Escale** is trying to create a new way to impact our custumers for Black Friday sales and needs to select some of its drones.

Our job is to create a program that selects **'G'** drones with greatest flight range that are available.

For that we are given the following information:
* A list of all drones containing its numeral ID and its flight range in kilometers (Km).
* The required amount of drones (**'G'**)
* A list of dorne IDs that are currently in maintenance and thus ARE NOT AVAILABLE for operations

The program must return a list of the IDs of the **'G'** selected drones, sorted by flight range (greater first).

Assume that there are enough drones available.

### Sample Input:
| Drone ID |      Flight Range      |
|----------|:----------------------:|
| 4 | 11 |
| 2 | 15 |
| 5 | 16 |
| 3 | 40 |
| 1 | 20 |
| 9 | 60 |
| 6 | 22 |

The required amount of drones ('G'): **3**

Drone IDs currently in maintenance: **[1, 5, 9]**

